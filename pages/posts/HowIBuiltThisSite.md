# How I Built This Site

---

[Home](../../README.html)

---

## Automatically converting markdown to html

### Technical work

1. Gulp
    * Install Gulp via npm
    * Create a [Gulp task](../../gulpfile.js)
    * Choose your markdown styling, I chose the github theme (_at the time I wrote this post_).
    * Create a task via VScode to automate the creation of html from markdown
2. Upload to Github & Enjoy

### Shortcomings
* Lack of html embedding features
    * Let's say you want to add collapsable points in your markdown via html, that can only happen if you go into your rendered html file and manually add the code
    * Should you save your md file, it'll overwrite any manual changes you made prior

### May 17, 2022