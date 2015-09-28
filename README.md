# vue-document-title

Declarative, nested, stateful document title for Vue

**WIP.**

## What it does

```javascript
// in your template, like: 
<div id="app">
  <document-title title="HomePage">
    <h1>Hello App!</h1>
    <child-component />
  </document-title>
</div>

// some child component
<document-title title="About">
  <div class="box">
    <h3>Child</h3>
    <p>about me...</p>
  </div>
</document-title>
```

## License

MIT.
