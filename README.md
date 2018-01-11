# Separation of Content and Presentation

## We Are HTML Authors

We now know what HTML is. We know how to create a properly-formatted HTML
document and we know how to browse the HTML documentation. We have everything
we need to be HTML authors.

However, if we look at our rendered HTML pages, we can't help but notice that
they look incredibly spartan. We could be forgiven for thinking we've travelled
through time back to 1994!

HTML lets us define content with semantic _structure_ but we would like a means
to say "Browser, when you see a `p` tag, or any tag with `id` of `intro`, or a
`p` tag with a `class` of `warning`, change its presentation from the spartan
default to some more-attractive alternative."  That "attractive" alternative
might be "make the font larger" or "make the background red."

Technologists recognize a difference between _content_ (the HTML document) and
_presentation_ the rules for decorating or adorning the rendered elements with
display rules.

## Decorate HTML with Cascading Style Sheets (CSS)

The means for defining rules to HTML structure in order change presentation is
a rule specification format called "Cascading Style Sheets" or "CSS."
