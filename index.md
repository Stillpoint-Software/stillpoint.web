---
layout: default
---

   <div class="container">
   <div class="row" style="padding-top: 60px;" ></div>
    <div class="row" >
        <div class="col-6" style="padding-top: 20px;">
        <img class="lazy" data-src="//wsrv.nl/?url={{ site.imageurl | absolute_url }}/assets/section1.jpg" alt="Startup thinking at enterprise scale" />
        </div>
        <div class="col-6" style="padding-top: 20px;">
            <h1 style="text-transform: uppercase;text-align: center">Startup thinking at enterprise scale</h1>
            <p>We are a product and development consultancy. We work with forward-thinking teams to improve actionability with their products, customers, partners, and one another.</p>  
            <p>We provide a full range of software development services, and technology, for startups and enterprises that want to move quickly. We specialize in solving complex productization
                and development problems across industries, including healthcare, telecommunications, financial services, and media companies.</p>            
            <p>If you want to improve your organizations technical agility, we want to talk.</p>
       </div>
    </div>
<div class="row" style="padding-top: 60px;" ></div>
    <div class="row">
        <div class="col-6">
         <h1 style="text-transform: uppercase;text-align: center; font-size: 2rem;">Be Relevant - Act</h1>
            <p>Companies that can't keep up quickly fall out of touch. When your systems get in the way your best people will either find creative ways to circumvent them or they'll leave. This creates deep security and compliance concerns on the one hand while risking your best customers, employees, and partners on the other.</p>  
            <p>The pathway to relevance, and the ability to innovate, is to leverage the human communication networks within your organization. Free people to innovate while also driving measurable action through a communications first strategy.</p>            
        </div>
        <div class="col-6">
          <img class="lazy" data-src="//wsrv.nl/?url={{ site.imageurl | absolute_url }}/assets/sub-section-1.jpg" alt="Startup thinking at enterprise scale" />
        </div>
    </div>
<div class="row" style="padding-top: 60px;" ></div>
    <div class="row">
      <div class="col-6">
        <img class="lazy" data-src="//wsrv.nl/?url={{ site.imageurl | absolute_url }}/assets/sub-section-2.jpg" alt="Use Your Stuff" />
        </div>
        <div class="col-6">
            <h1 style="text-transform: uppercase;text-align: center">Use Your Stuff</h1>
            <p>You already have the systems; in-fact you probably have dozens of them. What if you had the ability to creatively recombine and reuse your existing IT investments to address new opportunity, while being mindful of compliance and data security?</p>  
            <p>We build software that lets you integrate your business data and back-end systems directly into your communications flow and to quickly integrate with partners and vendors.</p>            
       </div>
    </div>
<div class="row" style="padding-top: 60px;" ></div>
    <div class="row">
        <div class="col-6">
         <h1 style="text-transform: uppercase; text-align: center">Let's Make a plan</h1>
         <h4 style="text-align: center">Discover → Propose → Design → Engineer</h4>
            <p>Relevance is about doing the right-thing, at the right-time, in the right-way. It is about effecting action and measuring results.</p>  
            <p>We are experts at mapping the processes necessary to design, implement, and deploy successful initiatives that make your interactions more meaningful; from discovery and ideation, through turn-up, analytics, and operation.</p>          
        </div>
        <div class="col-6">
          <img class="lazy" data-src="//wsrv.nl/?url={{ site.imageurl | absolute_url }}/assets/sub-section-3.jpg" alt="Let's Make a Plan" />
       </div>
    </div>
<div class="row" style="padding-top: 60px;" ></div>
     <div class="row">
      <div class="col-6">
        <img class="lazy" data-src="//wsrv.nl/?url={{ site.imageurl | absolute_url }}/assets/sub-section-4.jpg" alt="Our Technology" />
        </div>
        <div class="col-6">
            <h1 style="text-transform: uppercase;text-align: center">Our Technology</h1>
            <p>We have out-of-the-box solutions for collaboration, rules, meta-data, integrations, security, deployment, and continuous integration that allow you to focus your resources on what matters. Our technology stacks and APIs will get you to MVP faster on a foundation that will grow with you.</p>  
       </div>
    </div>
</div>

<div class="container">
    <div class="row">
        <div class="col col-12 col-d-10 col-m-12 push-m-0 push-d-1">
            <div class="contaniner__inner">
                <div class="row grid">
                    {% if site.posts.size > 0 %}
                    {% for post in site.posts limit: 3%}
                    {% include article-content.html %}
                    {% endfor %}
                    {% endif %}
                </div>
            </div>
        </div>
    </div>
</div>