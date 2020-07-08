```javascript
1) Get Vue from CDN
2) Create HTML
3) Create Vue instance
4) Bind model from Vue instance to HTML

<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <script src="https://cdn.jsdelivr.net/npm/vue"></script>
    <title>Document</title>
  </head>
  <body>
    <div id="app">
      <input type="text" v-model="name" />
      <p>Hello {{name}}</p>
    </div>

    <script>
      new Vue({
        el: "#app",
        data() {
          return {
            name: "John",
          };
        },
      });
    </script>
  </body>
</html>

```