# Math
This theme uses KaTeX to render math client-side.
The implementation was inspired by
[this post](http://latkin.org/blog/2016/08/07/better-tex-math-typesetting-in-hugo/).

However, instead of one shortcode, we use two:
`texi` for inlined math and `texd` for display math.
You have to set `hasTex` to `true`; otherwise, KaTeX isn't loaded.

TODO: Server-side pre-rendering.
