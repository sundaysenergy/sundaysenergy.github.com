---
layout: page
title: Static benefits
header: Pages

---

## The problems with Content Management Systems 

### Complexity and Cost

Using Drupal or Wordpress requires software to be running on a server to dynamically build each page request. So every time a user wants to visit a page, the server has to build it first. The software that does this builds each page dynamically, which requires frequent updates to work correctly and has a lot of "moving parts". The cost to keep all of those parts moving all the time is high. Therefore, the cost to host a website like this will be much more expensive than a static site.

### Constraints on Content Creation

With a typical CMS, content can only be created on that website. This method for adding content was designed to be like a “desktop” type device that was connected to the internet. This approach was fine when everyone did everything on a desktop computer. But now content creators have all kinds of devices they like to use for content creation. A good example is the iPad. It’s often clumsy editing content via a website, and is a much nicer experience using a native app that is a content editor.

### Emphasis on WYSIWYG Editors

It has become standard that WYSIWYG editors are included for content editing in a CMS.  However, this often creates more problems than it solves. First, all editors try to convert WYSIWYG into HTML code, with varying degrees of success. WYSIWYG editors often make mistakes, and most users don't know enough HTML to fix them. Also, a WYSIWYG editor is less precise than editing by hand because it adds a layer between the designer and the code. Lastly, many people write their documents in Microsoft Word, and  paste that content into the WYSIWYG editor.  The WYSIWYG editor then tries to interpret the Word formatting and convert it to HTML, which yields very messy code that confuses web browsers and creates ugly web pages. 

## Why switch to Create Anywhere Publish Everywhere (CAPE)?

### Performance

Content rarely changes. So it is a complete waste of resources to load a database along with the software to handle processing it into the final HTML markup. Also, it's difficult to get higher page-loading performance than when serving static files. Dynamic content can be handled with various third party javascript libraries. Ever get a notice from your host that your website is using too many resources? CPU or Memory issues will be gone forever when your site is statically cached.

### Data Protection

Own your content. If you use a blogging service like Tumblr, you should have a backup of all your posts. Do you? CAPE accepts various sources of information and stores them in plain text files. They are easy to edit anywhere, and can be published everywhere.

### Security

Serving static HTML is inherently safe. There are no server-side scripts to get attacked, or abused. Any time your site is being dynamically generated, that software must be updated regularly or you are at risk for security vulnerabilities.

### Focus on the content

Interfaces change, content remains. So your content needs to be **presentation agnostic**. One of the greatest things about the Web is its universalit, and web-enabled devices are everywhere. Your content should be accessible from any device. A Content Management System should focus on **managing content**, but too often ends up limiting it.

### Responsive Design

The web is responsive by nature. Responsive design gets really difficult to accomplish when there are display rules mixed in with the content. Often times layout breaks on certain devices or layouts. It's nearly impossible to test for all the possibilities. Design for the flexibility and the unknown.

### Versatility

Desktop applications, web applications, mobile applications. All devices can be sources of content! Why limit yourself to creating content to a single place focused toward a single device.

### Don't Repeat Yourself or Reinvent the Wheel

Don't Repeat Yourself (DRY) is a software development goal aimed at reducing repetition in information of all kinds. To reinvent the wheel is to duplicate a basic method that has already previously been created or optimized by others. We think that CAPE helps website users and managers avoid both of these pitfalls.

### Drupal is Slow and Complicated

You'll only be as good as the mean of those around you. The Drupal community is home to many semi-developer freelancers. Drupal enables a ton of functionality without being a programmer. Need some added functionality? There is a module for that. However, this module could have been written for a specific job and the maintainer is no longer getting paid to work on it.

#### Drupal is good for two main groups

1. Small-scale site builders who can leverage the power of Views, Fields, and the rich module ecosystem but aren't building sites complex enough to land them in "maintenance hell".

2. Large organizations with development teams that need a complex content/user model. Drupal does a good job of content modeling, revisions, localization, and has a decent plugin system.

#### The simple things
Say you want to show a specific set of characters in a post. Not easy when there is html involved. You have to exclude the html from the count.
