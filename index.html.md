```
some-div (compile)
app.js:9 parent (compile)
app.js:9 ..first-child (compile)
app.js:9 ..second-child (compile)
app.js:6 some-div (controller)
app.js:12 some-div (pre-link)
app.js:15 some-div (post-link)
app.js:6 parent (controller)
app.js:12 parent (pre-link)
app.js:6 ..first-child (controller)
app.js:12 ..first-child (pre-link)
app.js:15 ..first-child (post-link)
app.js:6 ..second-child (controller)
app.js:12 ..second-child (pre-link)
app.js:15 ..second-child (post-link)
app.js:15 parent (post-link)
```