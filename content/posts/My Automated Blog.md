---
title: My First Contribution on Next.js
tags:
  - nextjs
  - opensource
  - contributions
---
Contributing to open source has always felt intimidating, especially when the project is as big as **Next.js**. But recently, I made my very first pull request (PR) to the Next.js repository — and it actually got recognized by the maintainers. Here’s how it happened.

---

## 🐣 How It Started

I wanted to contribute something small and beginner-friendly. Instead of diving straight into fixing bugs deep in the framework, I looked for documentation issues.

That’s when I came across an **open issue**:

> The Middleware documentation didn’t mention how `pageExtensions` affects the filename of `middleware.js|ts`.

At first glance, it looked minor. But actually, this could trip up a lot of developers customizing their project extensions.

## 🛠 What I Did

I:

- Opened the **Middleware documentation file** in the Next.js repo.
    
- Added a missing **note** explaining that if a project uses custom `pageExtensions`, the middleware filename follows those extensions.
    
- Clarified that the file does not always need to be named `middleware.js` or `middleware.ts`.
    

Commit message:

`docs: add pageExtensions note to Middleware and clarify default filename`

---

## 💡 Why It Matters

It might look like “just a docs fix,” but small changes like this:

- Save developers time when debugging why their `middleware` isn’t being picked up.
    
- Prevent frustration for those customizing `pageExtensions`.
    
- Make Next.js more beginner-friendly, which is important since docs are often the first entry point.
    

---

## 🚀 The Outcome

- My PR was reviewed by the maintainers.
    
- The issue was marked as **completed**.
    
- The author of the issue even tagged and thanked me by name! 🎉
    

This wasn’t just about one line of documentation — it was about **getting through the full contribution cycle**:

- Finding an issue
    
- Forking the repo
    
- Making the change
    
- Writing a clear commit message
    
- Opening a PR
    
- Having it acknowledged and closed
    

---

## 🌱 Lessons Learned

1. You don’t have to start by fixing complex bugs. Docs are a great entry point.
    
2. Maintainers notice effort — even small fixes are valued.
    
3. Every contribution adds up to visibility in the community.
    

---

## ✨ What’s Next

Now that I understand the workflow, my next goal is to dive deeper into Next.js’s inner workings:

- Explore routing, middleware, and server components in the codebase.
    
- Look for issues labeled `good first issue` and `help wanted`.
    
- Slowly move from docs to bug fixes and feature improvements.

