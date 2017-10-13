---
title: "Visibility"
description: "These utilities make it easy to show and hide content depending on screen sizes."
status: "Alpha"
---
## Hide down responsive utilities
The `hide-*-down`responsive display utilities start out visible on any screen size above the largest breakpoint (1400px) and will **hide content as the screen size becomes smaller**.

Resize your browser window to see how the `hide-*-down` utilities work.

{{< example lang="html" >}}<dl>
    <dt>.hide-sm-down</dt>
    <dd class="hide-sm-down">Hidden at <strong>small breakpoint</strong> down</dd>
    <dt>.hide-md-down</dt>
    <dd class="hide-md-down">Hidden at <strong>medium breakpoint</strong> down</dd>
    <dt>.hide-lg-down</dt>
    <dd class="hide-lg-down">Hidden at <strong>large breakpoint</strong> down</dd>
    <dt>.hide-xl-down</dt>
    <dd class="hide-xl-down">Hidden at <strong>extra large breakpoint</strong> down</dd>
    <dt>.hide-xxl-down</dt>
    <dd class="hide-xxl-down">Hidden at <strong>extra extra large breakpoint</strong> down</dd>
</dl>
{{< /example >}}

## Hide up responsive utilities
The `hide-*-up` responsive display utilities start out visible on small screens and will hide content as the screen **size becomes larger**.
{{< example lang="html" >}}<dl>
    <dt class="color-midnight">.hide-sm-up</dt>
    <dd class="hide-sm-up">Hidden at <strong>small breakpoint</strong> up</dd>
    <dt class="color-midnight">.hide-md-up</dt>
    <dd class="hide-md-up">Hidden at <strong>medium breakpoint</strong> up</dd>
    <dt class="color-midnight">.hide-lg-up</dt>
    <dd class="hide-lg-up">Hidden at <strong>large breakpoint</strong> up</dd>
    <dt class="color-midnight">.hide-xl-up</dt>
    <dd class="hide-xl-up">Hidden at <strong>extra large breakpoint</strong> up</dd>
    <dt class="color-midnight">.hide-xxl-up</dt>
    <dd class="hide-xxl-up">Hidden at <strong>extra extra large breakpoint</strong> up</dd>
</dl>
{{< /example >}}