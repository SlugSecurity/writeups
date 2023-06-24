# Slug Security Writeups
Welcome to the home of [Slug Security](https://slugsec.ucsc.edu)'s writeups. Our repository, which is synced via Github submodules, is automatically updated and organized in the [writeups section](https://slugsec.ucsc.edu/writeups/) of our website.

## What Are Writeups?
Writeups are basically our way of sharing knowledge. They're reports or guides where we talk about security concepts, techniques, or solutions to security competitions/challenges. Think of them as in-depth pieces on what we've learned, what we've seen, or what we think is cool in security.

## Purpose
The idea behind these writeups is to share and spread information. We want to help others understand complex security topics, learn from incidents we've analyzed, or just get to get a head start or a glimpse into the world of security. It's our way of contributing to the community and fostering a culture of knowledge sharing.

## Structure
Each writeup can be represented as a folder under a general year folder. For example, `2023/` would contain all writeups from 2023. This is to avoid confusion as competitions are often held across multiple years. Let's say you wanted to make a writeup for a competition called `Amazing Test CTF 2023`. You would create the folder `/2023/` and then create a folder called `/2023/Amazing Test CTF/`.

Each writeup should contain an `_index.md` file, which serves as the homepage of the writeup and is the main page that will be shown on our website. For challenge categories such as `web`, `pwn`, `crypto`, etc., you can make a folder for each category and put the corresponding writeups in there. For example, a `web` challenge writeup would be in `/2023/Amazing Test CTF/web/`, then create the subsequent challenge writeups in there.

If you want to add images or other files, you can create a folder called `/_assets/` in the root of your writeup folder. This is where you can put images, files, or other assets that you want to use in your writeup. For example, if you wanted to add an image to your writeup, you would put it in `/2023/Amazing Test CTF/_assets/`.

For any code/programs you want to link to your writeup, you can create a folder called `/_sources/` in the root of your writeup folder. This is where you can put any code or programs that you want to link to in your writeup. For example, if you wanted to link to a program called `exploit.py`, you would put it in `/2023/Amazing Test CTF/_sources/`.

Example structure of a writeup for `Amazing Test CTF 2023`:
```
.
└── 2023
    └── Amazing Test CTF
        ├── index.md
        ├── _assets
        │   ├── graph.png
        │   └── header.png
        ├── _sources
        │   ├── exploit.py
        │   └── sampleBinary
        ├── pwn
        │   └── Challenge1.md
        ├── Another Category
        │   ├── Challenge1.md
        │   └── Challenge2.md
        └── web
            ├── Challenge1.md
            ├── Challenge2.md
            └── Challenge3.md
```

## Technical Details
Our main site uses Jekyll and Liquid to statically generate our website. We use a custom plugin to automatically generate structures for writeups and posts using Ruby scripts and Github submodules. We also use several markdown enhancement libraries such as [Mathjax](https://www.mathjax.org/), [Mermaid.JS](https://mermaid.js.org/), [Chart.JS](https://www.chartjs.org/), and a few more miscellaneous libraries to make our writeups more interactive and engaging. Viewing our writeups outside of our website may not be as pretty or as easy to read, but it should still be functional.
