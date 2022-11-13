---
name: How I'm learning Rust
slug: how-im-learning-rust
date: 2022-11-09
---

# How I'm learning Rust

Rust is often considered a somewhat hard language to learn, and people often leave it behind as it can be quite hard to feel productive with it when starting out. It certainly feels that way for me. I'm still incredibly interested in the language and I find myself constantly gravitating towards educational material around it.

Still, books, videos and podcasts won't ever make you proficient in a programming language. Eventually we'll have to get our hands dirty and build something. I want to list out some of the principles and rules I've set so that I make sure that I put in my hours with Rust.

## Write Everything in Rust

Crude as it may sound, the number one rule I've set myself is to simply write everything in Rust. Most of the time I wind up dropping Rust because I want to solve my problem with the limited time that I have in my free time. Banging my head against the borrow-checker for hours has been hard to justify, but I've come to the conclusion that I just need to do my time and get through it.

This may sound uninspiring or unsatisfying, and it definitely is sometimes. But I just need to remind myself that my ultimate goal right now is to learn Rust, and I'm sure I'll thank myself in the end despite simple projects taking much longer to finish.

## Don't Write _Everything_ in Rust

Of course, there's always an exception to every rule. While Rust is an incredibly versatile language, there are situations where it may just be downright silly to implement certain things in it. For me this is in web-related scenarios where other languages are more mature or even standard. For example I will still be using JavaScript to implement interactivity in web-projects. Despite things like WebAssembly and Yew making DOM manipulation possible in Rust I think that using the native solution for the browser is more reasonable.

That being said, I still have some rules for situations like these:

1. I may not rely on dependencies for languages other than rust (no npm).
2. I should only solve problems where that language is simply more suitable
3. Keep it to a minimum, there are plenty of things to make where this can be avoided

With this, I make sure that I make sure I focus on Rust by keeping implementations in other languages simple. In the case of JavaScript, it's also an interesting challenge to just rely on the browser platform as much as possible.

## Just Make it Work

To keep my expectations in check, this is an important rule. My main goal with any project is just to make whatever I'm building work. It may not be the most elegant, most performant piece of software out there, but trade-offs must be made so that I can still reach the finish line at some point. I have no goals that any of my projects should be used in the production by other people. But I do want to make things that are useful to me.

## What Will I Build?

Everything! Whether it's a simple script to process some data or something more sophisticated like a video game or embedded software. I do have a particular interest in the latter right now, and I may share my journey in home automation with Rust as this blog grows, but don't hold your breath! As I mentioned, Rust is an incredibly versatile language, and I will make sure to take the opportunity to explore as many of the possibilities as I can.

I started out by building this blog. Or more accurately, a static site generator for it. I will be sharing more about that in a separate post.

## Summary

In order for me to learn rust I will:

1. Write all code in my free time in Rust
2. Write some code in other languages if the platform is more suited to that.
3. Just make it work, and avoid too much optimization and quality work.
4. Have fun and explore, Rust is an awesome language for just that!
