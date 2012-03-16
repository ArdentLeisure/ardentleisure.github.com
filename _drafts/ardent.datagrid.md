---
title: Ardent.DataGrid
date: 
layout: post-dk
categories:
- Code
tags: []
---


We needed a generic datagrid for the Admin section of Dreamworld Ecommerce.

I looked at a few around the place but most of them were either overkill and thus had a larger footprint or terrible to implement server side under ASP.NET.

DataTables looks nice but too much to get the server component of it working (<a href="http://datatables.net/development/server-side/asp_net">http://datatables.net/development/server-side/asp_net</a>)

JQGrid is pretty good and loaded with features but its probably overkill for our needs and still has the same issue with server side being messy or too complicated.
The MVC example requires a seperate ViewModel for each grid you want to create and the column filtering isnt generic enough to support querying on linq objects <a href="http://www.trirand.net/demoaspnetmvc.aspx">http://www.trirand.net/demoaspnetmvc.aspx</a>.

DHTMLX Grid is another we looked at but again its 

So I decided to write my own with a few main goals in mind:
<ul>
    <li>Easy to add a new DataGrid to a page</li>
    <li>Customisable columns based on Linq-to-sql objects</li>
    <li>Single server side method to be used across all DataGrids</li>
    <li>Sorting, Pagination, per column filtering </li>
    <li>Lightweight on the client side</li>
</ul>




<h4>Current limitations</h4>
<ul>
    <li>No in-grid editing - The grid was designed to be readonly to make it lightweight</li>
    <li>DateTime values output is not the same format as searching ()</li>
</ul>