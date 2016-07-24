---
layout: page
title: Links
long_title: Useful Links
permalink: /links/
---
{% capture algorithms %}
- [Extra, Extra - Read All About It: Nearly All Binary Searches and Mergesorts are Broken](https://research.googleblog.com/2006/06/extra-extra-read-all-about-it-nearly.html) - Joshua Bloch, a Software Engineer at Google, showcases a bug that can be found in many merge sort and binary search implementations including those in educational texts.
{% endcapture %}

{% capture college %}
- [Making the Most Out of CMU](http://notes.willcrichton.net/making-the-most-out-of-cmu/) - Will Crichton offers his suggestions on making the most of Carnegie Mellon.
{% endcapture %}

{% capture compilers %}
- [Rust: The New LLVM](http://notes.willcrichton.net/rust-the-new-llvm/) - Will Crichton discusses the advantages and disadvantages of writing compilers that target Rust.
{% endcapture %}

{% capture humor %}
- [CommitStrip](http://www.commitstrip.com/) - CommitStrip is a series of comics about "the daily life of web agency developers."
{% endcapture %}

{% capture programming %}
- [Autotools Tutorial](https://www.lrde.epita.fr/~adl/autotools.html) - Alexandre Duret-Lutz offers a great way to get up and running with the GNU Build System.
- [The other kind of JavaScript fatigue](http://chrismm.com/blog/the-other-kind-of-javascript-fatigue/) - Christian Maioli Mackeprang questions the current state of the JavaScript community.
- [Reading C type declarations](http://www.unixwiz.net/techtips/reading-cdecl.html) - Steve Friedl explains C type declarations and the reasoning behind their syntax in an arguably better way than that of K&R.
{% endcapture %}

##### Below is a collection of things on the web that I've found useful or interesting in one way or another.

{% include accordion.html type='begin' name='links' %}
{% include accordion.html type='item' name='Algorithms' md=algorithms %}
{% include accordion.html type='item' name='College' md=college %}
{% include accordion.html type='item' name='Compilers' md=compilers %}
{% include accordion.html type='item' name='Humor' md=humor %}
{% include accordion.html type='item' name='Programming' md=programming %}
{% include accordion.html type='end' %}

##### If you notice a broken link, a PR or issue on [GitHub](https://github.com/lachm/lachm.github.io/blob/master/links.md) would be greatly appreciated.
