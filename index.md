# Solver.News

<ins>Q1 2022</ins>

A Quarterly update on the Mathematical Optimization Solver Industry and Ecosystem.

Exploring the creation, usage and adoption of solvers, soft/middle-ware, bespoke or industry specifc solutions.

So this is purely an idea at the moment. If 10 (ten) people sign up I will write the next one and make some improvements to the content :) Or perhaps people will just make PRs and this can continue to live... Or perhaps this is better on some kind of mailing list?


<div>
	<!-- Begin Mailchimp Signup Form -->
<link href="//cdn-images.mailchimp.com/embedcode/classic-10_7_dtp.css" rel="stylesheet" type="text/css">
<style type="text/css">
	#mc_embed_signup{background:#fff; clear:left; font:14px Helvetica,Arial,sans-serif;  width:600px;}
	/* Add your own Mailchimp form style overrides in your site stylesheet or in this style block.
	   We recommend moving this block and the preceding CSS link to the HEAD of your HTML file. */
</style>
<div id="mc_embed_signup">
<form action="https://news.us14.list-manage.com/subscribe/post?u=97dec9915893172c1826ada8a&amp;id=bc47c8b7e2" method="post" id="mc-embedded-subscribe-form" name="mc-embedded-subscribe-form" class="validate" target="_blank" novalidate>
    <div id="mc_embed_signup_scroll">
	<h2>Subscribe</h2>
	<div> Sign-up below to get Solver.News directly to your inbox.</div>
<div class="mc-field-group">
	<label for="mce-EMAIL">Email Address  <span class="asterisk">*</span>
</label>
	<input type="email" value="" name="EMAIL" class="required email" id="mce-EMAIL">
</div>
	<div id="mce-responses" class="clear foot">
		<div class="response" id="mce-error-response" style="display:none"></div>
		<div class="response" id="mce-success-response" style="display:none"></div>
	</div>    <!-- real people should not fill this in and expect good things - do not remove this or risk form bot signups-->
    <div style="position: absolute; left: -5000px;" aria-hidden="true"><input type="text" name="b_97dec9915893172c1826ada8a_bc47c8b7e2" tabindex="-1" value=""></div>
        <div class="optionalParent">
            <div class="clear foot">
                <input type="submit" value="Subscribe" name="subscribe" id="mc-embedded-subscribe" class="button">
                <p class="brandingLogo"><a href="http://eepurl.com/hYQ_bj" title="Mailchimp - email marketing made easy and fun"><img src="https://eep.io/mc-cdn-images/template_images/branding_logo_text_dark_dtp.svg"></a></p>
            </div>
        </div>
    </div>
</form>
</div>
</div>
<script type='text/javascript' src='//s3.amazonaws.com/downloads.mailchimp.com/js/mc-validate.js'></script><script type='text/javascript'>(function($) {window.fnames = new Array(); window.ftypes = new Array();fnames[0]='EMAIL';ftypes[0]='email';fnames[1]='FNAME';ftypes[1]='text';fnames[2]='LNAME';ftypes[2]='text';fnames[3]='ADDRESS';ftypes[3]='address';fnames[4]='PHONE';ftypes[4]='phone';fnames[5]='BIRTHDAY';ftypes[5]='birthday';}(jQuery));var $mcj = jQuery.noConflict(true);</script>
<!--End mc_embed_signup-->

## All paths lead to ~~Rome~~ **Solvers**

keywords: launch, v0, PoC, optimization, solvers

Here is a first pass at creating some content around the industry and perhaps some valuable discussion. I toyed with the idea of calling the page "not just solvers" after the well known [not just bikes youtube channel](link).

The structure and direction of this is very much in flux and current represents my personal view. But should there be interest in a specific area please feel free to [email me](mailto:f.kauker@gmail.com).

One of the areas I feel is neglected is the "commercial" or "business" part of the optimization industry.

How are companies evaluating and precuring solvers or software, building teams or working with vendors?

To get a better idea we want to understand the market size and key dynamics.

The only report I have been able to find is [this one](https://cdn2.hubspot.net/hubfs/484375/Content/Gartner/Gartner_Market_Guide_for_Optimization_Solutions_2015.pdf) from 2015. Gartner does a good job of finding the right companies and doing some analysis. Whilst the market estimate is over $100 million USD. I think this falls short.

Also the key ingredient price and licensing are not covered in detail. This has been one of the biggest changes in recent years. On top of this there is also now more fragmentation in the market with users adopting open source solvers and building their own for their usecase. Plus a number of new market entrants. One thing to note is there hasn't been a level of development on the scale of Tensorflow/Pytorch in open source. This might be possible in the future, perhaps there might even be unification of these AI/ML frameworks and optimzation. 

Back to the $$$, the total spend in my mind is over a Billion dollars. Why? It's not just the license cost, you have to build the tooling and integrations around it. Not to mention the userbase for such solutions. Hopefully, some of the future discussions can shed more light onto what the actual market spend is. Oh and the hardward to run it all! There are even companies building custom hardware with [optimization baked in](https://synccomputing.com/).

### Creating a Industry index

The creation of a index. Why do we need a index? The larger field of "data science" is murky at best.

We'd like to know how the adoption of "mathematical optimization solvers" is going in industry. The overlap between academic and commerical usecases aswell as how the open source software is evolving.

#### Academia

The origin of practioners at large most have PhDs and connections to research. But metrics like number of papers/publications seem a little afar from what we are seeking to asses.

Lets start with the number of attendees for [INFORMS](https://www.informs.org/Meetings-Conferences), in this case over 6.5K individuals. How does this compare to say the large cloud conferences? AWS ~60K, Google ~26K

#### Jobs, jobs, jobs

Starting with the number or roles advertised/aggregated on Linkedin in the United States for ["Operations Research"](https://www.linkedin.com/jobs/search/?keywords=operations%20research) in the last month.

There are 47,448 this may sound like alot but when we compare to "Deep Learning" at 40,413 it becomes even more clear there is a renewed focus.

Both of which can be encopassed in "Data Science" with 161,544 and "Software Engineer" 174,176.

This might come as a surprise as typically Mathematical Optimization has been somewhat niche.

#### Market signals

Lets looks for content and new ventures/acquistions.

Google Trends doesnt seem like the right tool to gauge the market interest as when we look for the above areas not much registers.

So lets try news publications using [Google Search](https://www.google.com/search?q=%22operations+research%22&client=firefox-b-1-d&channel=nus5&tbm=nws&tbas=0&source=lnt&sa=X&ved=2ahUKEwjWtb3e_4L3AhXRPn0KHQyiASgQpwV6BAgBEBQ&tbas=0&biw=1728&bih=994&dpr=2).

This yields ~22,300 results. Whereas "deep learning" returns 528,000 results. Business analytics comes in at 137,000.

Given this can we also look at how the $$$ are flowing, are there many funding rounds? acquistions? partnership deals? This is left open for further discussion. Though a typical approach can be "solver inside" like [o9 solutions + Gurobi](https://o9solutions.com/news/o9-partners-with-gurobi/). One idea would be to construct a timeline from the orgination of simplex.

### Conversations

Most recently I've had numerous conversations along the following lines:

1. I just learned about "optimization" how can I get started?
2. I want to build a model to prove a usecase for my business whats the "best" solver to use?
3. How should my business determine which commercial solver to utilize?
4. Do we even need a solver?

Before we takle these topics lets figure out if it even matters!

Here @Peter Cacioppi delivers what is in recent times to most expressive answer!

<iframe src="https://www.linkedin.com/embed/feed/update/urn:li:ugcPost:6912093442483380224" allowfullscreen="" title="Embedded post" width="100%" height="500" frameborder="0" scrolling="no"></iframe>

To better inform the decisions lets also look at:

#### Commercial models and Costs

##### SaaS

There are a few SaaS like solutions and this is an interesting space in that it would be useful to remove the complexity of Software Engineering and DevOps from the modeling and PoC process. The current status quo is to perhaps use a notebook and then "productionize" these solutions maybe challenge that.

[IBM - Decision Center](https://www.ibm.com/cloud/decision-optimization-center?utm_content=SRCWW&p1=Search&p4=43700068101114280&p5=p&gclid=CjwKCAjw9LSSBhBsEiwAKtf0nz9PbsOTKwqEkAXf53RxiofXgHn_BL_MLXsExuKac3cId-MkvOZ9sRoCQOsQAvD_BwE&gclsrc=aw.ds)

[Aftermarket Analytics - Rapid Deployment App Builder](https://aftermarketanalytics.com/software/)

[Optano](https://optano.com/en/platform-2/#consultants)

[Cassotis](https://www.cassotis.com/)

[MOOPT](https://moopt.com/)


##### Cloud

##### Server License

##### Floating License

##### Golden Disk/Unlimited usage/deployment/cores

#### Do benchmarks even matter?

One of the most current workflows is to 


#### Customer support and implementation


## Community

### Launches/Conferences/Webinars/Courses et al.


#### JUMP v1.0

<iframe src="https://www.linkedin.com/embed/feed/update/urn:li:share:6912836592311115776" allowfullscreen="" title="Embedded post" width="100%" height="398" frameborder="0" scrolling="no"></iframe>

#### Highs seeks funding to take it to the next level

<iframe src="https://www.linkedin.com/embed/feed/update/urn:li:ugcPost:6915211148581605376" allowfullscreen="" title="Embedded post" width="100%" height="1154" frameborder="0" scrolling="no"></iframe>

#### Google releases new Open Source solver PDLP

<iframe src="https://www.linkedin.com/embed/feed/update/urn:li:share:6913143867521282048" allowfullscreen="" title="Embedded post" width="100%" height="800" frameborder="0" scrolling="no"></iframe>

#### Google productized route planning

[link](https://www.zdnet.com/article/googles-new-tools-should-help-your-packages-arrive-on-time)


#### Gurobi release v2 of log tools

https://github.com/Gurobi/grblogtools/tree/v2.0.0

#### Upcoming:

#### Archive:



#### Optimal Bookshop

<iframe src="https://www.linkedin.com/embed/feed/update/urn:li:share:6913620540561723393" allowfullscreen="" title="Embedded post" width="504" height="784" frameborder="0" scrolling="no"></iframe>


## Project Example

I'm going to cheat this time and share a WASM post I wrote and presented some time ago. Why? I really think that client side solving will become something!

https://gist.github.com/fhk/0aba10a289a5e6b253fb2abf268469ac

Further there are many more projects in the works.

https://github.com/centrifuge/clp-wasm

Perhaps this year we will see a commerical solver on WASM in the browser or desktop!?

Next up I might share a complete C++ example using or-tools as I also believe that [creating binaries](https://www.nextmv.io/blog/binaries-are-beautiful) is very valuable to help with many parts of the software process.

## Jobs

#TODO

Comments:

#TODO
