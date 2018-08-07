---
layout: blogpost
comments: true
title: 5 Steps To Adding A Custom Domain To Github Pages
subtitle: Setting Up A Custom Google Domain For Your GitHub
lang: pt
date: 2018-08-06
true-dt: 2018-08-06
tags: [Blog]
author: "Lisa Jiamsirioungkul"
comments: true
header-img: "img/dark-ann.jpg"
---
## 5 Steps To Adding A Custom Domain To Github Pages 

<br>
### Content

1. [Introduction](#intro)
2. [Setup in Github Repository](#repos)
3. [Configuring the Google Domain](#domain)
4. [Conclusion](#conclusion)


#### Introduction <a name="intro"></a>

This guide is to simplify the process of setting up a personal, customized website domain using Google Domains and GitHub Pages.  

#### Setup in Github Repository <a name="repos"></a>

##### Step 1:

Let's start with your Github Repository. If you don't have a repository started, head to this [link](https://github.com/new) to create with the name <b><u>USERNAME</u>.github.io</b>. In the picture example, I'm using my personal github.io. 

<img src="/img/blog-img/step1.png" width="718px">

##### Step 2:

In your new repository, create a <b>CNAME</b> file in the root directory and add the following:
    - <b>www.<u>YOUR-WEBSITE-NAME</u>.com</b>
    - <b><u>YOUR-WEBSITE-NAME</u>.com</b>
 By doing this, we add the domain name in the CNAME file to specify and redirect any request to <b><u>USERNAME</u>.github.io</b>
<img src="/img/blog-img/step2.png" width="718px">

##### Step 3:

Now verify that <b><u>USERNAME</u>.github.io</b> is directing to <b>www.<u>YOUR-WEBSITE-NAME</u>.com</b>.
    -Head to repository's the 'Setting' page. 
    -Under 'GitHub Pages', your site should be published at "<b>www.<u>YOUR-WEBSITE-NAME</u>.com</b>."
<img src="/img/blog-img/step3.png" width="718px">    
    
#### Configuring the Google Domain <a name="domain"></a>

##### Step 4:

Let's get your custom domain from Google. Head to ['My Domains'](https://domains.google.com/registrar) and select the DNS button to configure your DNS record.
<img src="/img/blog-img/step4.png" width="718px">

Go to the '<b>Custom Resource Records</b>' section. You will be adding a following:

 <thead>
    <tr>
      <th>Name</th>
      <th>Type</th>
      <th>TTL</th>
      <th>Data</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>@</th>
      <td>A</td>
      <td>1h/td>
      <td>192.30.252.153</td>
    </tr>
    <tr>
      <th></th>
      <td></td>
      <td></td>
      <td>192.30.252.154</td>
      <td>4854.67</td>
    </tr>
    <tr>
      <th>www</th>
      <td>CNAME</td>
      <td>1h</td>
      <td><b><u>USERNAME</u>.github.io</b></td>
    </tr>
  </tbody>
</table>

##### Step 5:

It should look like this when you're done.

<img src="/img/blog-img/step5.png" width="718px">

#### Conclusion <a name="conclusion"></a>

Now we're done! The DNS records can sometime take more than 24 hour to display your website, so you may not see it immediately. In the time being, adding new pages to your Github website should be accessible from your new domain. 

To test the page, I would use to see if your DNS record has come through:
    - USERNAME.github.io
    - www.YOUR-WEBSITE-NAME.com
    - USERNAME.github.io/about
    - www.YOUR-WEBSITE-NAME.com/about


