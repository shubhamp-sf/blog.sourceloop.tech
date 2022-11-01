# blog.sourceloop.tech
In order to contribute an article on sourceloop's blog, create a markdown file `example-post.md`

Please make sure below points:

*   the file ends with .md extension, we support markdown files only.
*   you added the correct blog domain in your markdown file i.e. `blog.sourceloop.tech`.
*   Frontmatter: Make sure each article has these details at the top of the file.
    
```
---
title: YOUR_TITLE_HERE **(Required)**
subtitle: YOUR_SUBTITLE_HERE
/* The pathname of your article url 
 * Ex. In https://blog.sourceloop.tech/what-are-microservices 
   "what-are-microservices" is the slug */ 
slug: CUSTOM_ARTICLE_SLUG_HERE (Will be created automatically if not provided)
tags: TAG_SLUG_1, TAG_SLUG_2 **(Required)** - You can find the list of tags here https://github.com/Hashnode/support/blob/main/misc/tags.json
/* You need to upload your image to https://hashnode.com/uploader 
and use the uploaded image URL as COVER_IMAGE_URL */ 
cover: COVER_IMAGE_URL
domain: blog.sourceloop.tech
/* When you have a team publication and a publication member has created an article */ 
/* Please note that this param is only supported while creating an article and not updating */ 
publishAs: USERNAME_OF_AUTHOR_OF_ARTICLE 
/* When your article is republished and you want to use  the origin url as canonical url */
canonical: CANONICAL_URL_OF_ARTICLE
/* Only if you don't want this article to be published yet */ 
ignorePost: true
---

Enter article body here
```        
*   List of tags can be found here https://github.com/Hashnode/support/blob/main/misc/tags.json
*   Make sure you haven't included **ignorePost** in the frontmatter by mistake.
*   Uninstalling app via Github will remove it from all the publications that the repo was connected to. If you want to specifically remove the installation from a particular publication, do it from it's Dashboard (Integrations section).
*   Creating an article with same slug as another article in the publication will overwrite the old article.
*   Do note that maximum of 10 file changes are respected in one particular commit.



