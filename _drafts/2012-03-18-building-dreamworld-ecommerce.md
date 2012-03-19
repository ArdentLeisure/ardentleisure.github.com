---
title: Building Dreamworld Ecommerce (PurpleSmoke)
date: 2012-03-15
layout: post-dk
categories:
- Projects
tags: []
---

<p>For the last 12 months or so I have been working on a project for Ardent Leisure. This project, codenamed PurpleSmoke, was to completely rebuild the Dreamworld, WhiteWater World and SkyPoint ecommerce engine.</p>

<h3>Firstly, a bit of background:</h3>
<p>Dreamworld, WhtieWater World and SkyPoint all share the same instance of their Point of Sale system (Siriusware) which is the reason we combined them into the same ecommerce solution.</p>
<p>The old ecommerce system was an off the shelf product from our Point of Sale vendor (Siriusware). This ecommerce system did its job but we had a few issues with it: 1, It wasn't very customisable. 2, Since the site was hosted off site and required a real time connection to the onsite database the site wasnt designed for such a setup so performance was terrible.</p>

<h3>So what did we need?</h3>
<ul>
    <li>Integreated with existing POS system</li>
    <li>Fast!</li>
    <li>Customisable</li>
    <li>Stable/Scalable (Whatever that means)</li>
</ul>

<h4>We started with a new architecture</h4>
<p>One that supported local storage instead of relying on a database over the internet for every request.</p>

<h3>How we handle releases</h3>
<p>This part is probably where I put my cowboy hat on and yell "Yeeha!".</p>

<h3>About our team</h3>
<p>Over the past 12 months our team has changed several times, we have had staff leave, new staff come on and even had a 3rd party development firm join the project.</p>

<h3>Future Releases</h3>