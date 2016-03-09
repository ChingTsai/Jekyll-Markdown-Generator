# Jekyll-Markdown-Generator

This is a simple shell script for generating Jekyll Markdown post template

### Supported Platforms

Linux, OS X or other Unix-like.

### How to use

Place `jekyll_md_generator.sh` in your Jekyll folder which is the directory has the `_posts` folder in it.

``` bash
> sh jekyll_md_generator.sh
  Title : Shell Script : Jekyll Markdown Generator
  Tags : code
> ls _posts/
  2016-03-07-Shell-Script-Jekyll-Markdown-Generator.md
> cat _posts/2016-03-07-Shell-Script-Jekyll-Markdown-Generator.md
  ---
  layout : post
  cover: false
  title: 'Shell Script : Jekyll Markdown Generator'
  date: '2016-03-07 22:56:00'
  tags: code
  subclass: 'post tag-code'
  categories: ''
  cover: ''
  ---
```

### Feature

- Title punctuations and space handling
- Auto generate date

### How it works
