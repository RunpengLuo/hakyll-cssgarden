---
title: The Professional
author: katychuang
authorurl: http://twitter.com/katychuang
tags: fixed-width
cover: theProfessional-index.png
screens: theProfessional-index, theProfessional-about, theProfessional-archive, theProfessional-contact, theProfessional-index
demo: http://katychuang.com/theProfessional-hakyll
download: https://github.com/katychuang/theProfessional-hakyll
---

# The Professional

A clean layout for showcasing your work. Save your files in the "portfolio" folder as `.markdown` files. 

It features a fixed with and navigation at the top of the page, and an it's sure to give your posts an extra polish.


---

## Installation:

Download the files from the [theProfessional](https://github.com/katychuang/theProfessional-hakyll) repo to your root hakyll installation for the boilerplate. Feel free to tweak site.hs and any of the files.

Compile the site generator with hakyll using the command `ghc --make site.hs` to create a local executable named `site`

Then you can view your site locally with `./site rebuild && ./site watch`

Note: These were the commands I used before stack became available. Now that hakyll can be installed by stack you can you can use stack commands.

---

## Usage

### **Posts**

At the top of each blog post saved in the `posts` folder: 

```markdown
---
title: Carpe Diem
---
```


### **Syntax Highlighting**

Syntax highlighting uses the pandoc formatting.

    ```hs
	fs x = "your code here"
    ```

The colors are defined in syntax.css; which you can edit to your liking.




