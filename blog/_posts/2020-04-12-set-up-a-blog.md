---
layout: post
title:  "Set up a blog to document stories!"
date:   2020-04-12 19:51:34 -0400
categories: setup
---
...And we have a blog! To make posts, all you have to do is add a new markdown file to the `_posts` folder. Markdown is a super-readable markup language that's perfect for blogging. [Here's](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) a popular cheatsheet. This sample blog is hosted with Jekyll, which has great integration with GitHub Pages. However, you can also blog with Wordpress, Medium, or whatever floats your boat!

Jekyll requires blog post files to be named according to the following format:

`YEAR-MONTH-DAY-title.MARKUP`

Where `YEAR` is a four-digit number, `MONTH` and `DAY` are both two-digit numbers, and `MARKUP` is the file extension representing the format used in the file. After that, include the necessary front matter. Take a look at the source for this post to get an idea about how it works.

To quickly customize this site:
- Update the title, description, email, and url in `_config.yml`
- You can change the logo text to your city in `/_includes/header.html`
- Ditto for the footer links, in `/_includes/footer.html`
- You can customize the CSS theming in `/assets/css/style.css`

![sample-image](/assets/images/sample-image.jpg)

Happy blogging!