# Instance
Template coding made easy

```
<script src = "Instance-0.0.1.js"></script>
<script>
  var browser = new Instance(document, function(e) { 
      // this code executes when the DOM is loaded, with the `this` scope set to `document`
      console.log(e);
  });
</script>
```

OR

```javascript
 <script>
   var browser = new Instance(function(e) { // shorthand for above
      console.log(e);
   });
 </script>
```

```javascript
 <script>
    if (browser.supports('void','let')) {
        browser.loadScript("test.js");
    }
</script>
```
