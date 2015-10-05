# Review

Markdown: If you're going to use Markdown (e.g., a `#` creates a heading), then be sure to use the correct syntax. For example, there is a space after the `#` and the text. With the space, you get a heading; without it, you just prepend `#` to your text. Check the [Markdown syntax](https://daringfireball.net/projects/markdown/syntax) for details.

## Mistakes to avoid

Looks good! See note above about Markdown syntax. Also, if you're numbering for a numbered list, do it this way:

```
1. First item
2. Second item
```

Not this way:

```
#1 First item
#2 Second item
```

Try it and you'll see the difference. You don't have to use Markdown, but you're welcome to.

## HTML

Watch out on copying and pasting. In HTML, the quotation marks are actually "ditto" marks. They're the straight up and down kind, not the curly kind. You pasted the link to the Bootstrap CDN and got one set of bad quotation marks, which screws up the syntax highlighting if not the code itself.

This:

```html
<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.5/css/bootstrap.min.css">
```

Not this (note the closing quotation mark):

```html
<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.5/css/bootstrap.min.css”>
```

Watch your indentation. For example, your closing `</style>` tag is indented too far. Meanwhile, lines 26 to 31 are not indented far enough.

Keep your line length to 80 characters or less. Unless paragraphs are really short, indent the contents. And use single blank lines to separate sections. For example:

```html
<article>
  <h2>Commuter Bikes</h2>

  <h3>Avanti inc</h3>

  <div class="pull-quote">
    <p>The Avanti inc is strong and simple.</p>
  </div>

  <p>
    Speacial features include a carbon belt and back-wheel hub. No mess, no
    worries.
  </p>

  <img src="inc-black.png" alt="inc">

  <h3>Specialized Sirrus</h3>

  <div class="pull-quote">
    <p>You can't look past one of these bikes.</p>
  </div>

  <p>
    It's sleek and slender, and will whip in and out of traffic like a snake.
  </p>

  <img src="sirrus-red" alt="sirrus">
</article>
```

Much easier to read, no? Readability is very important to debugging and code maintenance.

**Please close all tags with content (even if the standard and the validator don't require it). It greatly improves the readability and it's safer. Just because browsers are *supposed* to supply those closing tags doesn't always mean they will.**

## Accessibility

You probably noticed from the HTML Validator that adding landmark roles to HTML5 is redundant. There's some discussion, however, as to whether the validator's recommendations are really the best. (You asked if the validator is wrong. Well, probably not. But there are some strong differences of opinion about what's *best*, and the )


## Empathy

Congratulations. You have hit on my number one complaint about *Search Inside Yourself*, which is that it tries to sell altruism with selfish benefits. Talk about unclear on the concept. There is, however, some valuable information in the book. Don't let the "Bay Area Narcissist" approach scare you off from the good stuff, but nice catch, Sam!

Excellent insights. Good luck on the privilege. It's pretty difficult to spot if you're the recipient. Oh, and the path to curmudgeon is well trodden. Been down that path myself. :-)
