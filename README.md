# WriXt

WriXt is a fork of [Writ CSS]("https://writ.cmcenroe.me/").

Simplistic, responsive, classless styles for semantic <abbr>HTML</abbr> with inbuilt dark mode support.

## Usage

Just copy the line below to the `head` tag of you HTML file

```html
<link rel="stylesheet" href="https://wrixt.hrst.in/wrixt.min.css">
```

or download the [full template here][template].

[template]: template.html

## Goals

These were the original goals of [writ](https://writ.cmcenroe.me/):

- Drop-in stylesheet
  - No classes
  - No extra elements
- Responsive, without special-casing
- Visually pleasing

They remain the same with wrixt.

## Motivation

WriXt was born by extending Writ to support dark mode. I implemented dark mode using the latest CSS function [`light-dark`](https://developer.mozilla.org/en-US/docs/Web/CSS/color_value/light-dark).
		
The original motivation of Writ was this:

<abbr>HTML</abbr> is super easy to write. Markdown is even easier to write and
generate <abbr>HTML</abbr> from. But what does it look like?

<p style="text-align: center;">
  <img alt="Default styles" width="285" src="screenshot/default.png">
</p>

Not very nice, and it gets worse the more there is. Applying the Writ
stylesheet makes it better.

<p style="text-align: center;">
  <img alt="Writ styles" width="285" src="screenshot/writ.png">
</p>

## Caveats

Writ was designed for modern, standards compliant browsers only. Same goes for WriXt. I have used the very
new `light-dark` <abbr>CSS</abbr> function. So again, there are no
compatibility hacks. Some things might (should not, i guess) break.

## License

Copyright © 2015, Curtis McEnroe <curtis@cmcenroe.me>

Modified in 2025 by Harshit Katiyar <harshitk31dec@gmail.com>

Permission to use, copy, modify, and/or distribute this software for any
purpose with or without fee is hereby granted, provided that the above
copyright notice and this permission notice appear in all copies.

THE SOFTWARE IS PROVIDED "AS IS" AND THE AUTHOR DISCLAIMS ALL WARRANTIES
WITH REGARD TO THIS SOFTWARE INCLUDING ALL IMPLIED WARRANTIES OF
MERCHANTABILITY AND FITNESS. IN NO EVENT SHALL THE AUTHOR BE LIABLE FOR
ANY SPECIAL, DIRECT, INDIRECT, OR CONSEQUENTIAL DAMAGES OR ANY DAMAGES
WHATSOEVER RESULTING FROM LOSS OF USE, DATA OR PROFITS, WHETHER IN AN
ACTION OF CONTRACT, NEGLIGENCE OR OTHER TORTIOUS ACTION, ARISING OUT OF
OR IN CONNECTION WITH THE USE OR PERFORMANCE OF THIS SOFTWARE.
