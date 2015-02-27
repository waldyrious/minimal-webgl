# Minimal WebGL

The absolute minimal code to get a WebGL canvas showing something.
Most defaults are left alone
  (clear color is white, perspective is orthographic, no transformations applied, etc.)
  to make the code as approachable as possible.
A single square is shown, covering the whole canvas,
  but the `vertices` array can be changed to show a different shape.
The texture is (will be, see #1) procedurally generated to illustrate a non-static fragment shader,
  since most minimal examples I've seen
  tend to ignore that and just use a constant-color shader.

This code was heavily inspired by [@guciek](https://github.com/guciek)'s
[Shortest WebGL example](https://sites.google.com/site/progyumming/javascript/shortest-webgl),
but aims to be a fully documented such example (using [Docco](http://jashkenas.github.io/docco/)),
rather than just the code.
