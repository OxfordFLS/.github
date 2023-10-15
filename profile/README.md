# Intro to managing the website

## Website

Update team here: https://github.com/OxfordFLS/oxfordfls.github.io/blob/main/team.html

Images in: https://github.com/OxfordFLS/oxfordfls.github.io/tree/main/assets/images/team

````html
<div class="col-lg-3 col-sm-6">
	<div class="single-member">
		<div class="thumb relative" style="background: url(assets/images/team/haylee.jpg);">
			<div class="overlay overlay-member marketing d-flex flex-column justify-content-end align-items-center">
				<p class="text-white">Haylee is a <b>BA candidate in Law</b> (2021). She oversees aspects of online and offline marketing of OFLS and its sponsors.</p>
				<div class="line"></div>
				<div class="social d-flex align-items-center justify-content-center">
					<a href="https://www.linkedin.com/in/hayleecheam/" target="_blank"><i class="fa fa-linkedin"></i></a>
				</div>
			</div>
		</div>
		<div class="desc text-center">
			<h5 class="text-uppercase"><a href="mailto:contact@oxfordfls.org" target="_blank">Haylee Cheam</a></h5>
			<p>Marketing Officer</p>
		</div>
	</div>
</div>
````

Different colours for hovering over the people are possible: marketing,legaltech,fintech,exec (need to replace in the fourth line)

 ## Blog

Add new posts in the folder: https://github.com/OxfordFLS/blog/tree/master/_posts

-   Need to start the filename with the current date (yyyy-mm-dd) and end with “.md”.

-   Files must be in Markdown format (can be easily created with Markdown editors like “Typora” – or also just a regular text editor) and start with the same “YAML” header with additional information on the file contents.

```yaml
---
layout: post
title: "Challenges Automating the Law: AI in the Legal Sector" 
author: dom
categories: [ legaltech ]
image: assets/images/AI-in-SA-legal-space.jpeg
---
```

 Add new authors to this file (but keep old entries): https://github.com/OxfordFLS/blog/blob/master/_config.yml

 ```yaml
  dom:
    name: Domenico
    display_name: Domenico
    avatar: 'assets/images/dom.jpg'
    linkedin: in/domenico-piers-de-martino-753410148/
    description: "Domenico is a former President of the Oxford Fintech and Legaltech Society, and is an alumnus of the Masters in Law and Finance (2019)"
  d
 ```

The name in the blog article has to match the top-level entry in the “.yml” file exactly (e.g. “dom” – and not “Domenico) so as to establish a correspondence with the right author.
