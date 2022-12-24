---
layout: page
title: About
permalink: /about/
---

This is the base Jekyll theme. You can find out more info about customizing your Jekyll theme, as well as basic Jekyll usage documentation at [jekyllrb.com](https://jekyllrb.com/)

You can find the source code for Minima at GitHub:
[jekyll][jekyll-organization] /
[minima](https://github.com/jekyll/minima)

You can find the source code for Jekyll at GitHub:
[jekyll][jekyll-organization] /
[jekyll](https://github.com/jekyll/jekyll)


[jekyll-organization]: https://github.com/jekyll


#### Highlight block

For **highlight** block, you need only to write in your css file
```
pre {
  overflow-x: auto;
}
```

#### Markdown table

To write an overflow horizontally scrollable **markdown** table, one can first add a line in your css file
```
.overflow-wrapper {
  overflow-x: scroll;
}
```
and then write
```
<div class="overflow-wrapper" markdown="block">

| asd Test | asl kj | askdjl aksj  |asdlk jlak |aslkdjalksjd|asldjalksjdlak|alskdjalkjsdlak|alksdjalkjsdlka|alksdjlaksjdl|alksdjlaksjdlkJA| asd Test | asl kj | askdjl aksj  |asdlk jlak |aslkdjalksjd|asldjalksjdlak|alskdjalkjsdlak|alksdjalkjsdlka|alksdjlaksjdl|alksdjlaksjdlkJA|
| asd Test | asl kj | askdjl aksj  |asdlk jlak |aslkdjalksjd|asldjalksjdlak|alskdjalkjsdlak|alksdjalkjsdlka|alksdjlaksjdl|alksdjlaksjdlkJA| asd Test | asl kj | askdjl aksj  |asdlk jlak |aslkdjalksjd|asldjalksjdlak|alskdjalkjsdlak|alksdjalkjsdlka|alksdjlaksjdl|alksdjlaksjdlkJA|

</div>
```
The output would be like:
<div class="overflow-wrapper" markdown="block">

| asd Test | asl kj | askdjl aksj  |asdlk jlak |aslkdjalksjd|asldjalksjdlak|alskdjalkjsdlak|alksdjalkjsdlka|alksdjlaksjdl|alksdjlaksjdlkJA| asd Test | asl kj | askdjl aksj  |asdlk jlak |aslkdjalksjd|asldjalksjdlak|alskdjalkjsdlak|alksdjalkjsdlka|alksdjlaksjdl|alksdjlaksjdlkJA|
| asd Test | asl kj | askdjl aksj  |asdlk jlak |aslkdjalksjd|asldjalksjdlak|alskdjalkjsdlak|alksdjalkjsdlka|alksdjlaksjdl|alksdjlaksjdlkJA| asd Test | asl kj | askdjl aksj  |asdlk jlak |aslkdjalksjd|asldjalksjdlak|alskdjalkjsdlak|alksdjalkjsdlka|alksdjlaksjdl|alksdjlaksjdlkJA|

</div>

P.S. For overflow **HTML** table, one can just add to css file the following lines
```
.table {
  display: block;
  overflow-x: auto;
  white-space: nowrap;
}
```
I do not quite understand why this would not work for a **markdown** table (not being a programmer), but it would be good to know the reason.

