---
title: Separating publishing from hosting on the web
author: lmorchard
layout: post
permalink: /2014/10/09/separating-publishing-from-hosting-on-the-web
response_url:
  - 
response_title:
  - 
response_quote:
  - 
categories:
  - Uncategorized
tags:
  - facebook
  - metablogging
  - social
  - tootr
  - twitter
  - webdev
---
<div id="toc_container" class="toc_wrap_right no_bullets">
  <p class="toc_title">
    Contents
  </p>
  
  <ul class="toc_list">
    <li>
      <a href="#Hosting_made_stupid_simple"><span class="toc_number toc_depth_1">1</span> Hosting made stupid simple</a>
    </li>
    <li>
      <a href="#There8217s_an_app_for_publishing_that"><span class="toc_number toc_depth_1">2</span> There&#8217;s an app for publishing that</a>
    </li>
    <li>
      <a href="#It8217s_complicated_but_worth_it"><span class="toc_number toc_depth_1">3</span> It&#8217;s complicated, but worth it</a>
    </li>
    <li>
      <a href="#Challenges"><span class="toc_number toc_depth_1">4</span> Challenges</a>
    </li>
  </ul>
</div>

Social media like Twitter and Facebook combine web publishing and hosting. You can&#8217;t run different software, and you can&#8217;t move your stuff. So, if you&#8217;re unhappy, your choices are a) deal with it or b) abandon your stuff and your friends. Those are pretty rough options.

But, what if you *could* move your stuff? And what if you *could* switch apps?

<!--more-->

## <span id="Hosting_made_stupid_simple">Hosting made stupid simple</span>

Imagine a dead simple hosting service that puts stuff on the web for you. The main thing they do is support an API for apps. It&#8217;s not free-as-in-beer, but it&#8217;s cheap. Say $10 / year or maybe even $25 / year if you get serious and rent your own domain name. It could charge per usage, which might mean pennies-per-month if you&#8217;re a not yet a superstar celebrity.

They also make it easy to get backups and move to a competitor. If they annoy you or go down often or get hacked, you can just pack up and leave. And since your web stuff is made up of static <a target="_blank" title="HTML" href="https://developer.mozilla.org/docs/Web/HTML?utm_source=wordpress%20blog&utm_medium=content%20link&utm_campaign=promote%20mdn">HTML</a> / <a target="_blank" title="JS" href="https://developer.mozilla.org/docs/JavaScript?utm_source=wordpress%20blog&utm_medium=content%20link&utm_campaign=promote%20mdn">JS</a> / <a target="_blank" title="CSS" href="https://developer.mozilla.org/docs/Web/CSS?utm_source=wordpress%20blog&utm_medium=content%20link&utm_campaign=promote%20mdn">CSS</a> / image resources, moving is simple. All your URLs will change, unless you splurged on that domain name. But, I think we can smooth over that problem, like in the olden days when your phone number changed.

## <span id="There8217s_an_app_for_publishing_that">There&#8217;s an app for publishing that</span>

Now, imagine a publishing app. This could run on a device you own &#8211; like your phone or tablet or laptop. It could also run on someone&#8217;s server in the cloud. When you start using a publishing app, it asks where you keep your stuff. Then, it does a permission dance with you and your hosting service &#8211; &#8220;so-and-so wants to do such-and-such, is this okay?&#8221;

Having gotten permission, the publishing app can manage some or all of your stuff at the hosting service. A Twitter-alike could maintain some <a target="_blank" title="HTML" href="https://developer.mozilla.org/docs/Web/HTML?utm_source=wordpress%20blog&utm_medium=content%20link&utm_campaign=promote%20mdn">HTML</a> pages for your random thoughts, help you upload a header image & a picture of yourself. If the authors of the Twitter app disappoint you, you can switch to the Ello-ish app. You don&#8217;t abandon anything or anyone.

Ideally, these competing apps support the same formats. Or, they offer a way to convert between the two. They&#8217;d have incentive to make transitions easy, because they want you to switch. And that&#8217;s because you can pay for these apps &#8211; say $1 or $5 or $10. They could even offer in-app purchases for themes or analytics or scheduled posts or whatever.

## <span id="It8217s_complicated_but_worth_it">It&#8217;s complicated, but worth it</span>

There&#8217;s complexity introduced, here. But, it&#8217;s not that bad, relatively speaking: You don&#8217;t need to deal with configuring web servers, uploading PHP scripts, or logging in with SSH. The hosting service, again, is stupid simple and commoditized.

Apps can be as complex as their authors like, but that can be hidden from you with great UX & UI. The main thing is that you manage the permissions between your hosting service and your apps &#8211; not nothing, but it&#8217;s not much.

And, remember, the reason you might choose to accept this extra complexity is because it gives you choice. Both the hosting services and the publishing apps have incentive to serve you &#8211; because you&#8217;re a paying customer and because you can leave.

## <span id="Challenges">Challenges</span>

What&#8217;s the incentive for bootstrapping this? I&#8217;m not really sure, beyond thinking it&#8217;s a neat idea. Is there a profit potential, even if just in the range of a lifestyle business?

It&#8217;s a chicken-and-egg problem: There aren&#8217;t really many (any?) super simple web hosts with great UX, and there aren&#8217;t apps that use them. Which comes first? Probably a little of both, most likely from a web host who also offers their own apps.

Also, a central challenge in building this kind of ecosystem is to make sure the signup process for a hosting service and the permission dances with apps are easy. This is an opportunity to provide a great user experience, so that the only extra burden is the novelty of considering hosting & publishing as separate concerns.

I&#8217;m not sure if all the above is a solution. It&#8217;s not a new idea, either. But, I think it deserves revisiting. It might make for some fun tinkering, at least.