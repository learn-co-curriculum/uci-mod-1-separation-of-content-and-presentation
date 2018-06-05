# Separation of Content and Presentation

## Problem Statement

We now know what HTML is. We know how to create a properly-formatted HTML document and we know how to browse the HTML documentation. We have everything we need to be HTML authors. However, if we look at our rendered HTML pages, we can't help but notice that they look a little plain. How do we make them look more attractive to use and why can't we do that with HTML itself?

## Objectives

1. Identify the separation of content and presentation
2. Identify the role of CSS

## Identify the Separation of Content and Presentation

HTML lets us define content with semantic _structure_. This is what lets us build solid foundations for our content and it's the chief purpose of HTML. But it would be useful to be able to say "Browser, when you see a `p` tag, or any tag with `id` of `intro`, or a `p` tag with a `class` of `warning`, change its presentation from the plain default to some more-attractive alternative." That "attractive" alternative might be "make the font larger" or "make the background red."

Technologists recognize a difference between _content_ (the data within the HTML document) and _presentation_: the rules for displaying the rendered elements. We keep them separate so that we can apply particular tools to each purpose. We use HTML for content and for presentation we use CSS.

## Identify the Role of CSS

CSS, or "Cascading Style Sheets," is the rule specification format that defines how we change the presentation of HTML. It has its own syntax and definitions and often lives in a file apart from our HTML. CSS handles all of the ways we want to customize our content's look and feel, and does so much more efficiently and powerfully than HTML possibly could. 

## Resources

* [CSS Guidelines: The Separation of Concerns](https://cssguidelin.es/#the-separation-of-concerns)
* [CSS Zen Garden](http://www.csszengarden.com/)

## Conclusion

We separate the content of our HTML pages from their presentation, which we style with CSS. By keeping the two separate, we not only utilize the best tools for each job, but we can change code for one without necessarily disturbing the code for the other.
