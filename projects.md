---
layout: default
title: Projects
permalink: /projects/
---

<div class="row">
  <div class="col-md-8 col-md-offset-1">
    <div class="page-header">
      <h3>BIS 2 <small><a href="https://github.com/jrasky/bis2">github</a></small></h3>
    </div>

    <div class="container-fluid">
      BIS is better search for bash. It's something that I built when I got tired of readline's default search, and wanted something like flx in emacs, but for bash.<br>
      <br>
      The search algorithm is similar to how flx does search, using a character-based heatmap search. The UI is event-based, which was somewhat tough to get right in Rust.
    </div>
  </div>
</div>

<div class="row">
  <div class="col-md-8 col-md-offset-1">
    <div class="page-header">
      <h3>Wash <small><a href="https://github.com/jrasky/wash">github</a></small></h3>
    </div>

    <div class="container-fluid">
      Wash, or the whatever shell, is a project that I worked on mainly to learn how to make effective UIs in terminal, and to learn how to use Linux kernel APIs to manage processes and the like.<br>
      <br>
      I also used this project to learn Rust to a certain degree. It's one of my larger project, totaling to about 8000 lines. I also learned to write a simple compiler to bytecode for a simple scripting language.
    </div>
  </div>
</div>

<div class="row">
  <div class="col-md-8 col-md-offset-1">
    <div class="page-header">
      <h3>Half 2 <small><a href="https://github.com/jrasky/half2">github</a></small></h3>
    </div>

    <div class="container-fluid">
      Half 2 was originally going to be a version control system, but it ended up being an opportunity for me to learn how about b-trees. I worked on that implementation for several weeks, eventually getting it nearly as fast as Rust's standard implementation.<br>
      <br>
      In the end, it didn't really go anywhere, but it did inspire me to care more about performance and algorithms. I also learned to use GDB and debug binaries, as I ended using a number of somewhat dicey memory hacks to make things faster.
    </div>
  </div>
</div>
