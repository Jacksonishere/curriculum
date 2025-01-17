### Introduction

This is a brief catch-all section designed to make sure you understand not just what elements and selectors and attributes you **CAN** use, but which ones you **SHOULD** use in each situation.  When you go visit several "normal" webpages (preferably one that isn't too massively corporate, since they do some abnormal stuff), there are a lot of similarities in the way they are structured (which you can see in your developer tools).  They all tend to judiciously use container divs for grouping elements and they use classes and IDs as necessary to determine styles.

You'll also get the chance to review what was covered in previous sections by checking out [LearnLayout](http://www.learnlayout.com) and doing their exercises.

### Learning Outcomes

* What is a "container `<div>`"?
* When should you use `<span>` vs `<div>`?
* When should you use `id` vs `class`?
* What are good situations for breaking out styles into multiple classes?
* How can you use margins for alignment?

### Assignment

<div class="lesson-content__panel" markdown="1">
1. Do the exercises for [Learning CSS Layouts at LearnLayout](http://learnlayout.com/)
</div>

### Additional Resources
This section contains helpful links to other content. It isn't required, so consider it supplemental.

* Put a box around every div on the page with [this Chrome extension](https://chrome.google.com/webstore/detail/pesticide-for-chrome-with/neonnmencpneifkhlmhmfhfiklgjmloi) by Bradley Flood, or [this Firefox extension](https://addons.mozilla.org/en-US/firefox/addon/pesticide-for-firefox/) by Daniel Oshiro.  It can help you deconstruct an existing page or debug your own layouts.
* (A lightweight way to mimic above extension) If you don't want to install yet another extension, then you can add this simple line in any website using **devtools -> styles** or add it inside your own project's CSS file.
`* {
    outline: 2px solid red !important;
}`
 ( The asterisk (\*) is known as the CSS universal selector. It can be used to select any and all types of elements in an HTML page. )
* [CSS Style Guide](http://codeguide.co/#css) by [Mark Otto](https://github.com/mdo), one of the creators of Bootstrap.
* [CSS Reference](http://cssreference.io/), a visual guide to CSS, by [Jeremy Thomas](https://github.com/jgthms).
* Add some!
