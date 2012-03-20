---
title: Building Dreamworld Ecommerce (PurpleSmoke)
date: 2012-03-21
layout: post-dk
categories:
- DK
tags: []
---

<p>
	For the last 12 months or so I have been working on a project for Ardent Leisure.
	This project, codenamed <strong style="color:#843DC6;">PurpleSmoke</strong>, was to completely rebuild the Dreamworld, WhiteWater World and SkyPoint ecommerce engine.
	Which is a massive project, shop.dreamworld.com has over 1700 visits per day and averages about 250 transactions a day during off-peak.
</p>

<h3>Firstly, a bit of background:</h3>
<p>Dreamworld, WhtieWater World and SkyPoint all share the same instance of their Point of Sale system (Siriusware) which is the reason we combined them into the same ecommerce solution.</p>
<p>The old ecommerce system was an off the shelf product from our Point of Sale vendor (Siriusware). This ecommerce system did its job but we had a few issues with it: 1, It wasn't very customisable. 2, Since the site was hosted off site and required a real time connection to the onsite database performance was terrible.</p>

<h3>So what did we need?</h3>
<ul>
    <li>Integreated with existing POS system</li>
    <li>Fast!</li>
    <li>Customisable</li>
    <li>Stable/Scalable (Whatever that means)</li>
	<li>Able to support multiple sites (Dreamworld, SkyPoint, Reseller, etc.)
</ul>

<h4>We started with a new architecture</h4>
<p>One that supported local storage instead of relying on a database over the internet for every request.</p>

<h3>How we handle releases</h3>
<p>This part is probably where I put my cowboy hat on and yell "Yeeha!".</p>
<p>We try to follow a scrum/agile approach to development.</p>

<h4>v0.1 (12 Sept 2011)</h4>
<p>This was somewhat of a 'pilot' of the platform as it was only for SkyPoint even though it was a full functioning site.</p>
<ul>
	<li>PurpleSmoke Ecommerce platform (Basic ecommerce stuff, items, cart, checkout, payment, etc.)</li>
	<li>Siriusware Integration. Syncing Guests, Items, Accounts. Pushing transactions into POS to generate barcoded ETickets for scanning</li>
	<li>Support for Affiliates</li>
</ul>

<h4>v0.2 (7 Nov 2011)</h4>
<ul>
	<li>Dreamworld Online Shop (<a href="https://shop.dreamworld.com.au">.dreamworld.com.au</a>)</li>
	<li>My Account section for guest to view previous orders, edit details, download ETickets, etc.</li>
</ul>

<h4>v0.3 (12 Dec 2011)</h4>
<ul>
	<li>Dreamworld Mobile Ecommerce (<a href="http://shop.dreamworld.com.au/m/">http://shop.dreamworld.com.au/m/</a>)</li>
	<li>Upsell module for Dreamworld</li>
	<li>Adopt an Animal Product and Content pages</li>
	<li>Admin Dashboard with sales graphs</li>
	<li>Custom Google Analytics Tracking events</li>
</ul>

<h4>v0.4 (9 Jan 2012)</h4>
<ul>
	<li>Dreamworld Ticket Agent Program (Reseller site)</li>
	<li>Basic Site Admin Tools</li>
</ul>

<h4>v0.5 (8 Feb 2012)</h4>
<ul>
	<li>Refactoring</li>
	<li>Improved support for Affiliates/Resellers (Page Filtering, Homepage design, etc.)</li>
	<li>Better Logging</li>
	<li>Bug fixes</li>
</ul>

<h4>v0.5.1 (15 Mar 2012)</h4>
<p>PERFORMACE! Lots of updates to improve performance across the entire site.</p>
<ul>
	<li>Optimized Database Queries</li>
	<li>Added Caching where possible</li>
	<li>Decreased Javascript footprint</li>
</ul>

<h3>About our team</h3>
<p>Over the past 12 months our team has changed several times, we have had staff leave, new staff come on and even had a 3rd party development firm join the project.</p>

