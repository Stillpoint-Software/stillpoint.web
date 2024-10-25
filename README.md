# Site information

This site is using the Mangila theme[link](https://jekyllthemes.io/theme/mangila-blog-jekyll-theme) and Sveltia-cms [Link](https://github.com/sveltia/sveltia-cms) for admin.

The site is being hosted on Netlify and source code is on Sillpoint's github 


# Mangila

Mangila is a minimalistic and elegant theme that will highlight your personality. This theme can be used in almost any niche and is perfect for any modern website from travel magazines to corporate blogs.

All elements complement each other creating a harmonious combination of simplicity and convenience. Be unique with Mangila.

[link](https://jekyllthemes.io/theme/mangila-blog-jekyll-theme)
* * *

### Demo

Check the theme in action [Demo](https://mangila.netlify.app/)

* * *

### Deployment

## Local Setup

1.  Install Ruby 3.0.0 [link](https://rubyinstaller.org/)
2.  Install Ruby Gems [link](https://rubygems.org/)
3.  Open the project in VS Code
4.  From the terminal, install Jekyll `gem install jekyll`
5.  From the terminal, run bundle install
6.  To run the site locally, run `bundle exec jekyll serve` the Jekyll server.
7.  to run the admin, start the server and add `admin` to the end of the url

## Netlify Setup

1. Login to Netlify
2. Click on "New site from Git"
3. Select `GitHub` under connect to Git provider
4. You will need to authorize Netlify
5. Pick a respository
6. Configure your setting
7. Enter an `Environment Variable` as follows:  RUGY_VERSION   3.0.0


## Github 
1.  Add the source code to a github repository.
2.  In the Settings of the `Github` organization, go to `Oauth`
3.  Click on `New OAuth app`
4.  Enter an appplication name, homepage url and application description
5.  Under Authorization callback URL enter `https://api.netlify.com/auth/done`
6.  Copy the ClientID and Secret, you will need this for netlify
7.  Under third-party access, click on `GitHub Apps`
8.  Click on `Configure` next to "Netlify"
9.  Scroll down to `Repository access`
10. Select the repository you want to give Netlify access to


* * *

### Documentation

Before using the Mangila theme, please read the attached documentation.