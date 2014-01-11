---
layout: post
title: "Donation flow improvements"
date: {9 January 2014}
categories: technology
author: Brian VanderZanden
"author-initials": bv
banner: "/img/banner/funnel-money.jpg"
published: true
---

One of our long-term clients, Project Open Hand approached us in late 2013 to look at ways to help improve its donation system. Project Open Hand does great work in the local community providing 2,500 nutritious meals and 400 bags of groceries every day. As a non-profit, they rely heavily on donations to sustain their work. The majority of the giving occurs in the last six weeks of any given year. We were asked to help make them even better.
![Multi-year December peak chart](/img/post/funnel-optimization/multiyearanalytics-thanks.png)

When we heard the challenge, we were keen to see how we could help. We began with an analysis of how people were progressing through the donation process, took measurements of key criteria, and started to form hypotheses about methods of improvement. The client had clear ideas about usability improvements as well.

One of the first findings that begged for optimization was the number of steps to complete a donation.

1. Click "Donate."
2. Land on the Donation page, then decide if the donation is a single donation, or the start of a recurring donation.
3. Land on appropriate donation page and fill out the necessary information.
4. Continue to Project Open Hand's Confirmation page.
5. Continue to the payment processor's page to fill enter credit card details and confirm payment.
6. Land on the Thank You page back on Project Open Hand's site.

![before flow](/img/post/funnel-optimization/before01.jpg)
![before flow](/img/post/funnel-optimization/before02.jpg)
![before flow](/img/post/funnel-optimization/before03.jpg)
![before flow](/img/post/funnel-optimization/before04.jpg)
![before flow](/img/post/funnel-optimization/before05.jpg)
![before flow](/img/post/funnel-optimization/before06.jpg)
![before flow](/img/post/funnel-optimization/before07.jpg)


The completion rates along the donation path reflected the arduousness of the process. People were spending almost five and a half minutes to complete a donation and of the percentage of people who started the process, only 14% got to the end.

The donation system Project Open Hand uses imposes several legacy constraints on available changes, so we worked to streamline where we could. The new donation flow focused on combining steps and reducing complexity.

1. Click "Donate."
2. Land on Donation page and fill out the necessary information.
3. Continue to Project Open Hand's Confirmation page.
4. Continue to the payment processor's page to fill enter credit card details and confirm payment
5. Land on the Thank You page back on Project Open Hand's site.

![after flow](/img/post/funnel-optimization/after01.jpg)
![after flow](/img/post/funnel-optimization/after02.jpg)
![after flow](/img/post/funnel-optimization/after03.jpg)
![after flow](/img/post/funnel-optimization/after04.jpg)
![after flow](/img/post/funnel-optimization/after05.jpg)

That's one less step, but there's more happening behind the scenes to help reduce the complexity.

The old single donation page had 21 fields to be selected from before continuing. The new design has 13 total fields by default, with only eight of them being required. When a donor wants to make a gift in honor of someone else, that choice is recognized and further interface options present themselves. Additionally, the site's menu structure has been simplified so that at any time while visiting the site, a user is only one click away from the donation form.

Using the same relative dates, we've measured conversion rates and time in the donation process, and found improvements in both. Not only did the conversion rate increase more than 23%, the time in the funnel decreased by over 20 seconds.

## What's left to be improved?

1. Increase the total number of donations.
2. Decrease the number of steps required to make a donation.
3. Decrease the time required to make a donation.
4. Increase the donation conversion rate even higher than the 23% currently being achieved.

Number 1 can be addressed through various awareness campaigns. You, dear reader, can [donate](http://www.openhand.org/donate/) and spread the word.
Numbers 2 and 3 can both be addressed directly by switching to a more modern payment processing system. The current system is based upon a core technology piece that's about 15 years old! A newer approach could collapse three of the existing steps into one. [Stripe](https://stripe.com/blog/stripe-checkout) shows us how streamlined a payment system can be.
Lastly, increasing donation conversion rates can be addressed indirectly through optimizations of the second and third items. Additionally, a more wide-ranging set of [A/B](https://en.wikipedia.org/wiki/A/b_testing) or [MAB](https://en.wikipedia.org/wiki/Multi-armed_bandit) tests could be used to hone in on a more effective design/workflow approach.

We were able to bring a significant enhancement to Project Open Hand's donation work flow and we are happy we could contribute to their further success. Do you have a situation that's similar, or want to talk with us about how these techniques could be applied in your situation? If so, be in touch at <contact@wordspicturesideas.com>.

### Caveats: 

We are many things, but economists and statisticians we aren't. Therefore, our data isn't scientifically valid. Our only "control" was to look at the same metrics across the same time period over successive years. We may be measuring influences of general economic growth, a general uptick in charitable giving, tax law incentives or phases of the moon on the data. That being said, we established a 99% statistical [confidence](http://testsignificance.com) that the new version's data is valid with over 900 total participants.
