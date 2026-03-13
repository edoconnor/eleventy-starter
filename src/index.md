---
layout: base.njk
title: Home
---

<!-- 👋 Welcome! This is your home page. Edit the content below to get started. -->
<!-- Delete everything inside this file below the front matter (---) and write your own content. -->

<div class="hero">
  <h1>Hello World</h1>
</div>
<!-- 
  STARTER GUIDE — delete this section when you're ready.
  It shows helpful instructions on the live page for new users.
-->
<div class="guide">
  <div class="guide-card">
    <div class="guide-icon"><i class="bi bi-file-earmark-plus"></i></div>
    <div class="guide-content">
      <h3>Adding a New Page</h3>
      <p>Create a new file in <code>src/</code> e.g. <code>src/about.md</code> and add the following to the top:</p>
      <pre>---
layout: base.njk
title: About
---</pre>
    </div>
  </div>

  <div class="guide-card">
    <div class="guide-icon"><i class="bi bi-list-ul"></i></div>
    <div class="guide-content">
      <h3>Adding a Nav Link</h3>
      <p>Open <code>src/_includes/partials/header.njk</code> and add a new item inside the <code>&lt;ul&gt;</code>:</p>
      <pre>&lt;li&gt;&lt;a href="/about"&gt;About&lt;/a&gt;&lt;/li&gt;</pre>
    </div>
  </div>
</div>
