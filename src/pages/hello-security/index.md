---
title: Hello Security
date: "2017-05-01T22:12:03.284Z"
---

This is a demo of evil input data. Lets start with an script:
<script type="text/javascript">document.write("<h1 class='hacked'>I was written from an inline script... You are owned</h1>")</script>

And also inline-styles. You notice this if the background is grey and the above text is red
<style>*{background-color: grey} .hacked{background-color: red}</style>
