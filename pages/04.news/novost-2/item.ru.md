---
title: 'Новость 2'
---

Go in your pages/ folder, create a 01.blog page (change the number to reflect your menu structure), add a blog.md file in it. In this file, add this content:


> content:
> items: '@self.children'
Copy
This tells Grav to iterate over the subpages (the blog posts).

Create a subfolder for each post you want to add, and add in each folder an item.md file, with the content of the blog post.