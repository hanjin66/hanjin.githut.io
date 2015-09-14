---
layout: post
title: Your First Post
published: false
date: 2015-09-13
categories: [blogging]
tags:[blogging]
---
##### Highlighting text without the code highlighting Start the line with a tab and it will automatically do it for you. you will get text like this if you start the line with a tab. ##### Further Reading on Markdown Github documentation on their markdown: [https://help.github.com/articles/github-flavored-markdown/](https://help.github.com/articles/github-flavored-markdown/). ### Section 4: Saving as draft most of the time you are not going to write and publish the blog post in one sitting but you need to save your work without it showing up in the website. This is called saving a draft and it is super simple to do. By setting the front matter published tag to false it will tell jekyll to not publish it. --- .. other front matter tags published: false --- You can also create a drafts folder and save the file in the but if you do that then you will need to move the file to the _post folder when you are ready to publish. ### Section 5: Publishing post Publishing a post is as simple as changing the front matter published to true and committing the change to the github repository. --- .. other front matter tags published: true --- Github will take care of the conversion from markdown to an html page. This should happen automatically within a minute and show up on the blog home page at the top. If it doesn't show up then check your email that you registered on github with to see if there was a jekyll compile error email. ### Conclusion This lesson is one of the key lessons as you need to kow how to create new blog post. Creating new blog post is really easy with Jekyll and a little bit of markdown. Once you learn the different markdown tags, you will be writing blog post in no time at all. See you in the next lesson, where we will discuss how to add the ability to comment on blog post.

