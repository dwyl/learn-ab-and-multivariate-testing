#Multivariate Testing [WiP]

>"Insanity is doing the same thing over and over again and expecting different results"  -  Albert Einstein

You've decided to start or improve a website or app, so presumably you've read up on [user experience](http://www.smashingmagazine.com/2014/01/27/pragmatic-ux-techniques-for-smarter-websites/) and have a ton of ideas.    

But which design **will work best for your audience**?    
Which piece of [micro-copy](https://econsultancy.com/blog/64951-six-brilliant-bits-of-micro-copy-you-can-implement-today/) will get people to share things with their friends?    
If you [make your form shorter](http://blog.crazyegg.com/2014/08/11/form-conversion-facts/) will more people sign up to your service?


##Tutorial outline
* [x] [Why learn this?](#why-learn-this)
* [x] [What is multivariate testing?](#what-is-it)
* [x] [Multivariate vs A/B testing](#multivariate-vs-ab-testing)
* [x] [Getting started](#getting-started)
* [ ] Setting up your first multivariate test
* [ ] [Terminology](#terminology)
* [ ] [Resources](#resources)

##Why learn this? 
>By changing different things _in a controlled environment_ and **_measuring the outcome_** of these changes, you **know \*exactly\* which changes achieve your site's goals** (increase your [conversion rate](#terminology)) and by how much.

Now you know where to focus your efforts! Multivariate testing allows you to **get your message across** to the people already coming to your site or app **in the best way possible**.

![is-the-information-youre-sharing-what-your-audience-is-looking-for?](http://imgs.xkcd.com/comics/university_website.png) 

##What is it?
People decide whether to leave or engage with a site [in the first 8 seconds](https://blog.kissmetrics.com/what-converting-websites-do/) - that's not much time to capture people's attention so you've got to get it right _for your audience_.

>Multivariate testing (MVT) aims to test a number of things on a site to understand **which combination of things best achieves the site's purpose** (for example increasing sign ups, sales or people clicking on articles).

A few of the more obvious things to test include:
* A [call to action](http://en.wikipedia.org/wiki/Call_to_action_%28marketing%29) (including wording and placing)
* Titles and [copy](http://untamedwriting.com/the-difference-between-web-copy-and-web-content-and-why-your-site-needs-both/)
* Placement & colour of elements
* Form fields a layout

**_NB. MVT can also be used to taste anything from email layouts to sales ads. For simplicity, in this introduction we'll stick with websites._**

##Multivariate vs A/B Testing

In [**A/B testing**](http://www.widerfunnel.com/solutions/website-testing/ab-split-testing) you test 2 (or more) different versions of your website by splitting the traffic evenly between them and seeing which one performs better. You can either test 2 completely different designs of your site _or_ you can pick just **one element** you want to change and keep all other things equal.

![ab-testing-two-versions](https://cloud.githubusercontent.com/assets/4185328/7446931/a4cfa1c2-f1e0-11e4-9117-c897a8ebaa3b.jpg)

In **multivariate testing** you pick a certain number of elements on a page and **simultaneously test multiple combinations of them** to understand which provides the best results. You could see it as running many A/B tests at once.

In the illustration below, I've used testing 2 different headlines, 2 different colour buttons and having a video on the homepage as an example.    
Just these 3 elements mean testing _8 different versions of your site at once_.

![mvt-graphic-it](https://cloud.githubusercontent.com/assets/4185328/7446084/0846e944-f1c4-11e4-94a2-28bb5379faba.jpg)

|       | A/B testing   | Multivariate testing |
| ------------- |:-------------:| :-----: |
| **What can you test?**     | Different layouts & designs or changes to single elements | Effects of changes to combinations of elements |
| **Number of visitors required for meaningful results**    | Relatively low      |   High |
| **Time required for meaningful results** | Short      |    Considerably longer |
| **Best used for**  | Significantly different layouts & designs or low traffic sites | Tweaking and optimising combinations of elements |

#Getting started
Before you can start your tests, you have to do a little analysis to determine **what you're testing**.

####Step 0: Get your analytics on
If you don't already have a [web analytics](http://en.wikipedia.org/wiki/Web_analytics) package on your site, I'm surprised you even found this article. Sign up to [Google Analytics](analytics.google.com) at the very least and start collecting some data that you can base decisions and tests on.

####1. What are your problem areas?
Dig out your site metrics (see step 0) and figure out where your problem areas are. Understanding web analytics is a whole other post but here are a few examples to start you off:    
* Is there a page that's not doing what you expect it to?    
* Are 50% of people leaving your sign up page without signing up?      
* Do you get a ton of email asking about your pricing when it's right there on the website already?
* Is your homepage bounce rate through the roof?
* Are you just not sure whether you should use one image or another or your homepage?

_Decide what your problem areas are, prioritise them and start with the first one._ Go for the areas of most impact.

####2. What is your goal?
What is it that you want this problem area to achieve?    
 Is it an increase in the number of people who sign up to your newsletter? A drop in the number of people who leave your website without looking at more than your homepage?
 
 _You have to know what you want to achieve in order to determine what you can improve to get there._

####3. Consider why it's not working as you expect (hypothesis)
You've decided that your problem area is your eBook download page and your goal is to get more people to download a free chapter (for example). So **why do you think** not 'enough' people downloading it now?    
* Is it that they don't see your download link?     
* They don't realise that they're a free chapter without having to buy the book?    
* That they input their email address but never submit it to you?

**This shouldn't be pure guesswork.** Use your [**metrics**](http://en.wikipedia.org/wiki/Web_analytics) to understand what's going on as best you can and if possible [**watch real users use your website or app** and ask them questions at the end](http://amzn.to/1IcNpA0). 


_You have to have some educated deductions as to why things aren't working as expected in order to know what you should try changing._

####4. Design your variations
This is the **fun part**. Based on what you think isn't working (step 3), decide what you're going to change and create your variations.

* **Don't go crazy and try to test everything straight away.** Remember that the more variations you have, the more visitors you'll need to your website to get meaningful results, so just test what you truly think will have an impact.
* Remember that you will be using your existing website as a [control](#terminology) so some visitors will still be split off to that variation. 

**_Now you're ready to run your test!_**

#Terminology
A quick list of terms you may see when reading up about this around the web.
* A/B testing
* **Control** - your control is the _existing_ webpage that gives you your **base metrics**; you want to have a control so that you know whether your variations are performing _better or worse_ than what you already have over the same period of time
* **Conversion rate** is the percentage of people who come to your site who _do what you want them to do_ such as sign up to your service, buy your product or share your content
* Conversion optimization
* **Element contribution** allows you to determine the percentage that each element contributes to your site's goal
* **Full Factorial testing** is a multivariate test that includes variations of _every_ element on a given page (remember you need **_a LOT_** of traffic to pull this off!)
* **Fractional (partial) Factorial testing** is a multivariate test which tests variations on 2 or more elements on a page (not _all_ of them)
* **Split testing** is the same as _A/B testing_, sometimes it's used to refer to A/B tests with more than 2 version (i.e. if you're testing your control headline against 3 different headlines rather than just 1 variation)

#Open Questions
* [ ] How much data do you need to reach a conclusion? Maybe for a different tutorial?

##Resources
* [x] Multivariate testing 101: http://www.smashingmagazine.com/2011/04/04/multivariate-testing-101-a-scientific-method-of-optimizing-design/
* [x] What is multivariate testing? https://www.optimizely.com/resources/multivariate-testing/
* [ ] Expert Guide to Multivariate Success: http://www.optimizeandprophesize.com/jonathan_mendezs_blog/2008/05/expert-guide-to.html

**A/B vs multivariate testing:**
* [x] A/B testing vs multivariate: https://vwo.com/blog/difference-ab-testing-multivariate-testing/
* [x] A/B Split Testing vs. Multivariate: Pros & Cons http://www.widerfunnel.com/conversion-rate-optimization/ab-split-testing-vs-multivariate-pros-cons

**What to test:**
* The [WiderFunnel blog](http://www.widerfunnel.com/blog) is quite opinionated but a good source of inspiration
* An excellent article on A/B testing filled with example on what Buffer have tested: https://blog.bufferapp.com/how-buffer-ab-tests
* [ ] Tips to improve your testing: http://marketingland.com/12-tips-to-take-your-ab-multivariate-testing-to-the-next-level-50249
* [ ] http://conversionxl.com/10-useful-findings-about-how-people-view-websites/
* [ ] http://www.wordstream.com/blog/ws/2012/09/25/a-b-testing
* [ ] Unvetted eBook: http://www.sitespect.com/17ideas


**Videos:**
* [ ] Best Practices & Lessons Learned from 30,000 A/B and Multivariate Tests (from the folks at Optimizely on the Obama campaign): https://www.youtube.com/watch?v=7xV7dlwMChc


**Books:** (affiliate links)
* [Experiment!: Website Conversion Rate Optimization with A/B and Multivariate Testing](http://amzn.to/1EIeB8t)
* [You Should Test That: Conversion Optimization for More Leads, Sales and Profit or The Art and Science of Optimized Marketing](http://amzn.to/1Q6C7zZ)
