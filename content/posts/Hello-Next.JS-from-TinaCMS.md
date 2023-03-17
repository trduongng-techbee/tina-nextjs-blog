---
title: Hello Next.JS from Tina
date: '2023-03-15T17:00:00.000Z'
tags:
  - Next.JS
  - Tina
---

### **Today I learnt how to apply Tina to existed Next.JS app.**

Follow the instruction from [https://tina.io/docs/frameworks/nextjs/](https://tina.io/docs/frameworks/nextjs/)

After finish running all command, there is some stuff to pay attention.

1. **The config.js file**: It's will be automatically generated in .tina folder. Here is the place to define everything we will do on TinaCMS, such as: The token and clientID to use Tina Cloud for production, the folder to save media, the git branch Tina will work on, the schema for our data which we want to manipulate with Tina Editor.
2. **The markdown file**: This is the filetype which Tina understand our data. These data file must be in content folder.
3. **The file decides how the editor page should be in contextual-editing**: After generated it will be the \[filename].js in /demo/blog path. Learn more about this on [https://tina.io/docs/contextual-editing/react/](https://tina.io/docs/contextual-editing/react/)
