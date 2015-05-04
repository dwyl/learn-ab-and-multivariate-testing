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
* [ ] Getting started
* [ ] Setting up your first multivariate test
* [ ] Terminology
* [ ] Resources

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
Dig out your site metrics (see step 0) and figure out where your problem areas are.    
Is there a page that's not doing what you expect it to?    
Are 50% of people leaving your sign up page without signing up?      
Do you get a ton of email asking about your pricing when it's right there on the website already?
Is your homepage bounce rate through the roof?

_Decide what your problem areas are, prioritise them and start with the first one._

####2. What is your goal?
What is it that you want this problem area to achieve?    
 Is it an increase in the number of people who sign up to your newsletter? A drop in the number of people who leave your website without looking at more than your homepage?
 
 _You have to know what you want to achieve in order to determine what you can improve to get there._

####3. How could you reach your goal (hypothesis)?
This is where you **decide what you're going to change** in order to get to your goal.

####4. Design your variations
* **Don't go crazy and try to test everything straight away**

* Don't forget to use your existing web page as a **control**

#Terminology
A quick list of terms you may see 
* **Conversion rate** is the percentage of people who come to your site who _do what you want them to do_ such as sign up to your service, buy your product or share your content
* **Element contribution** allows you to determine the percentage that each element contributes to your site's goal
* A/B testing
* Split testing
* Conversion optimization

#Open Questions
* [ ] How much data do you need to reach a conclusion? Maybe for a different tutorial?

##Resources
* [ ] Multivariate testing 101: http://www.smashingmagazine.com/2011/04/04/multivariate-testing-101-a-scientific-method-of-optimizing-design/
* [ ] What is multivariate testing? https://www.optimizely.com/resources/multivariate-testing/
* [ ] Multivariate Testing in Action: http://www.smashingmagazine.com/2010/11/24/multivariate-testing-in-action-five-simple-steps-to-increase-conversion-rates/

**A/B vs multivariate testing:**
* [x] A/B testing vs multivariate: https://vwo.com/blog/difference-ab-testing-multivariate-testing/
* [x] A/B Split Testing vs. Multivariate: Pros & Cons http://www.widerfunnel.com/conversion-rate-optimization/ab-split-testing-vs-multivariate-pros-cons

**What to test:**
* [ ] Tips to improve your testing: http://marketingland.com/12-tips-to-take-your-ab-multivariate-testing-to-the-next-level-50249
* [ ] http://conversionxl.com/10-useful-findings-about-how-people-view-websites/
* [ ] http://www.wordstream.com/blog/ws/2012/09/25/a-b-testing
* [ ] Unvetted eBook: http://www.sitespect.com/17ideas


**Videos:**
* [ ] A/B & multivariate Testing with Google Web Site Optimizer: https://www.youtube.com/watch?v=pDQsfMZQ44A
* [ ] Best Practices & Lessons Learned from 30,000 A/B and Multivariate Tests: https://www.youtube.com/watch?v=7xV7dlwMChc


**Books:** (affiliate links)
* [Experiment!: Website Conversion Rate Optimization with A/B and Multivariate Testing](http://amzn.to/1EIeB8t)
* [You Should Test That: Conversion Optimization for More Leads, Sales and Profit or The Art and Science of Optimized Marketing](http://amzn.to/1Q6C7zZ)
