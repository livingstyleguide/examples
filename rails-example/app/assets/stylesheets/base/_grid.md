# Grid

The layout is based on <var class="$columns-count"></var> Columns with <var class="$column-width"></var> width each and a gap of <var class="$gap-width"></var>. Most elements can span or skip several columns.

~~~ layout-example
<div class="layout--container">
  <div class="some-class grid">
    <div class="some-other-class grid--spans-1"></div>
    <div class="some-other-class grid--spans-3 grid--skips-1"></div>
    <div class="some-other-class grid--spans-1 grid--skips-2"></div>
  </div>
  <div class="some-class grid">
    <div class="some-other-class grid--spans-2 grid--skips-5"></div>
  </div>
  <div class="some-class grid">
    <div class="some-other-class grid--spans-2 grid--starts-new-line"></div>
  </div>
</div>
~~~
