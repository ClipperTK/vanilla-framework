---
collection: layout
title: grid
---

The grid is constructing using `*-col` elements nested inside a single `.row` parent element.

```
<div class="row">
    <div class="six-col">.six-col</div>
    <div class="six-col">.six-col</div>
</div>
```

<div class="row">
    <div class="twelve-col box">.twelve-col</div>
    <div class="eleven-col box">.eleven-col</div>
    <div class="one-col last-col box">&nbsp;</div>
    <div class="ten-col box">.ten-col</div>
    <div class="two-col last-col box">.two-col</div>
    <div class="nine-col box">.nine-col</div>
    <div class="three-col last-col box">.three-col</div>
    <div class="eight-col box">.eight-col</div>
    <div class="four-col last-col box">.four-col</div>
    <div class="seven-col box">.seven-col</div>
    <div class="five-col last-col box">.five-col</div>
    <div class="six-col box">.six-col</div>
    <div class="six-col last-col box">.six-col</div>
    <div class="four-col box">.four-col</div>
    <div class="four-col box">.four-col</div>
    <div class="four-col last-col box">.four-col</div>
    <div class="three-col box">.three-col</div>
    <div class="three-col box">.three-col</div>
    <div class="three-col box">.three-col</div>
    <div class="three-col last-col box">.three-col</div>
    <div class="two-col box">.two-col</div>
    <div class="eight-col box">.eight-col</div>
    <div class="two-col last-col box">.two-col</div>
    <div class="three-col box">.three-col</div>
    <div class="six-col box">.six-col</div>
    <div class="three-col last-col box">.three-col</div>
</div>

<div class="row">
    <h2>Nested grid</h2>
    <div class="twelve-col box u-text-center">
        <div class="eight-col box">.eight-col</div>
        <div class="four-col last-col box">.four-col</div>
    </div>
    <div class="six-col box u-text-center">
        <div class="four-col box">.four-col</div>
        <div class="two-col last-col box">.two-col</div>
    </div>
    <div class="six-col last-col box u-text-center">
        <div class="three-col box">.three-col</div>
        <div class="three-col last-col box">.three-col</div>
    </div>
    <div class="eight-col box u-text-center">
        <div class="one-col box">.one-col</div>
        <div class="seven-col last-col box">.seven-col</div>
    </div>
    <div class="four-col box u-text-center last-col">
        <div class="two-col box">.two-col</div>
        <div class="two-col last-col box">.two-col</div>
    </div>
</div>