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
        ├── _index.md
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