---
layout: post
title: CSV-simplified
---

CSV-simplified: An open-source project to unleash the potential of CSVs
I’ve been working on the basic setup for a potentially powerful CSV reader. Imagine having an enormous CSV file that you know has way more data in it than you need. If you could just choose specific columns to display, or provide ranges of data that your looking for, you could get a CSV file of a more manageable size.

CSV-simplified intends to create a web app that would allow the user to upload a CSV file and be prompted with various options that would parse down the data to the user’s specifications, view the results in the browser, and save it as a new file. With this tool a non-tech-savvy user could take a big CSV file, and by repeating a few parsings on it, accomplish the equivalent of a rather complex SQL query without having to learn a new language.

At the moment I’ve only completed the most basic setup of this app. Using HTML, JavaScript, jQuery, set up using Angular, and using a library called PapaParse, the first attempt just allows the user to upload CSV, and the app displays that CSV on the page. A small first step for sure, but it’s something. I’m currently looking for collaborators to help with both the backend logic and the frontend appearance. As in depth as creating SQL like tools for the back end can get, the potential for displaying a wealth of options and data will require a well executed frontend design. Both of these tings I don’t quite have the experience or time to accomplish on my own.

Anyone curious in how it works in its current version, or, better yet, contribute can find the GitHub repo [here](https://github.com/conkytom/CSV-simplified), and a Codepen of the current mechanics [here](https://codepen.io/anon/pen/JmWygV).
