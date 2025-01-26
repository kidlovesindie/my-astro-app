---
title: 'Learning about Astro and Cloudflare Pages by Building This Blog'
description: 'Learn how I use hands-on practices to learn about technologies like Astro and Cloudflare Pages.'
pubDate: 'Jan 26 2025'
heroImage: '/blog-placeholder-2.jpg'
---

One of the best ways I learn is by doing. I like to get my hands on the tech, tool, or item and tinker with it. It's the easiest way for me to quickly conceptualize and use the thing.

This has served me well in my profession. By day, I'm a manager of technical writers, content strategists, and documentation program managers. Over nine years ago, when I was an entry-level technical writer, one of the best pieces of advice given to me by my mentor was to install the software and learn how to use it. The guidance pushed me to dive into the product I was writing about instead of treating it like a conceptual, hard-to-understand thing. Soon, I was able to complete some of the basic workflows in the software, assess the state of the docs from an informed place, and chat with the dev team about its features and functionality at length. Following this advice helped me to deliver comprehensive, accurate, and useful documentation release over release–and it helped me gain the respect from devs and tech writers alike. In fact, I credit this advice (and a few other things) to my success as a tech writer and writer manager over the years because it’s simple, practical, and highly effective.

So it’s no surprise I like to do the same thing when I want to learn about new technology, concepts, and practices. Recently, I learned how the Cloudflare Product Content Experience team [deploys their documentation](https://blog.cloudflare.com/open-source-all-the-way-down-upgrading-our-developer-documentation/#2024-update-say-hello-world-to-our-new-developer-documentation-powered-by-astro). They chose to use Astro, Github, and Cloudflare Pages to push their content live to production. Intrigued by this doc tech stack, I chose to try my hand at creating and deploying a static website using these same tools. **Spoiler alert:** You are reading this post on the very site I created using these tools. 

#What I did first

I wouldn’t be a tech writer if I didn’t consult the docs first. Luckily, there’s an [Astro guide](https://developers.cloudflare.com/pages/framework-guides/deploy-an-astro-site/) on developers.cloudflare.com. It gave me everything I needed to know to quickly build and deploy a website.

#Prerequisites

There were two prerequisite tasks: 

Create a Cloudflare account.
Access to a Git repo, like GitHub or GitLab. 

So, I created a free Cloudflare account and ensured I was logged into my GitHub account.

If you’re thinking, “Is that all?” Yes, yes it is–and you can expect the same experience while you set up your astro app, push it to GitHub, and then deploy it using Cloudflare Pages. 

#It’s giving Command Line Interface

I’m not going to recreate the process here–mostly because that’s inefficient and unnecessary. I encourage you to follow the Astro guide or [watch the video tutorial](https://www.youtube.com/watch?v=c_IBs1crl4k). 

#Focus on the content–not the technical bits and bobs (unless you *really* want to)

You will get a placeholder-like blog deployed within minutes after following the guided help in the command line interface and then connecting your GitHub repo in Cloudflare Pages. 

One of the cool things about this build is Cloudflare Pages makes it *incredibly* easy to rebuild your website with every new commit and PR approval. After 30 deployments at this point, I have not had to troubleshoot a single build. Instead, I have only had to focus on the content I’m changing or adding to the blog at this point. This means I can just enjoy the act of writing vs. digging deep in the code and dependencies to build and deploy successfully. That’s a win in my book–not because I don’t enjoy investigating and learning how to use the tech, but because it made for a great user experience.

#Et voila

I’m still in the process of building out this blog to be more custom and, well, *me*. This blog post is proof that I’m continuing to learn about this tech by interacting with it and continuing to rebuild and deploy using it. I am becoming more familiar with all it has to offer and am planning to learn about [Starlight](https://starlight.astro.build/), Astro’s documentation site build, so I can offer it up at [Write the Docs ATX](https://www.linkedin.com/company/write-the-docs-atx/) events as an option for documentarians to consider when they’re tasked to research and build their next doc site. 

I’m looking forward to continuing this learn-by-doing journey. I’ll keep you updated on how it’s going.
