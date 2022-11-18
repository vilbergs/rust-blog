---
name: 'Stilla: Why I built (yet another) static site generator'
slug: why-i-built-a-static-site-generator
---

I knew I wanted to blog about my journey to learn Rust, if only to have a sort of journal that I could look back on as I become more proficient in the language. I could have spun up a static site from any of the number of JavaScript frameworks out there in a matter of seconds, but as I outlined in my post about [how I'm learning rust](/posts/how-im-learning-rust) I have prohibited myself from actually using JavaScript as a main tool for any of my endeavors.

Rust is very capable within the web sphere and there are a plethora of frameworks to build production ready web solutions in the language. However, none of them really fit my needs for a basic blog site.

## The Problem

It was clear to me that I wanted a statically generated website, seeing as this is very handy for simple blogs, and most of all easy to host for free since the generated site can be dumped onto a CDN and served from there.

The best thing about static-site generators is that they usually abstract away the bulk of the logic for you and allow you to focus on your content, sometimes in the form of a feature complete executable. This is of course fantastic, but it made it a bit hard for me to actually "Write my website in rust". Zola for example, is a popular SSG written in Rust, but it does not expose the user to any Rust code. You just run the Zola binary and call it a day!

I was determined to have the feeling that I had actually built my website, and that's how Stilla was born!

## Stilla

Stilla is a static site generator. It is heavily inspired by Zola, but I've tried to keep the feature set very small, and tailored to the way I find most productive to build sites today. It uses Markdown for content structure and has built in Tailwind support. You can read more about the project on [GitHub](https://github.com/vilbergs/stilla).

While the world may not need another SSG, I'm really happy that I built one from scratch as it helped my understand Rust a whole lot better, especially about crates like `fs`, `serde` and `time`. I focused on getting a simple feature set out the door and I definitely did not have performance in mind, therefore I can't recommend using it in it's current shape.

## What the Future Holds

I will keep fixing things and adding feature as I find the need for them, I've already noted a few oversights that I need to fix, but other than that I don't think I'll focus so much on this project as I have so many ideas for projects I want to build in Rust (and write about here!).

If Stilla's feature set interests you, and you want to contribute to the project. I'd be more than happy to make that as easy for you as possible, so feel free to write an issue or submit a pull request on GitHub!

[https://github.com/vilbergs/stilla](https://github.com/vilbergs/stilla)
