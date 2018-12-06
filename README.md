### jsduck
---
https://github.com/senchalabs/jsduck

```
gem install jsduck
jsduck --builtin-classes --output docs
jsduck ext-4.2.1/src --output docs
jsduck ext-4.2.1/src my-project/js --output docs
jsduck ext-4.2.1/src my-project/js --output docs \
  --warnings=-all:ext-4.2.1/src
```

```js
show: function(){
  alert("not implemented");
},

Ext.define("MyClass", {
  config: {
    store: ndefined
  }
});

Ext.define("MyClass", function(){
  return{
    config: {
      store: undefined
    }
  };
});

Ext.define("MyClass", {
  eventedConfig: {
    store: undefined
  }
});

@alias prefix.name
Ext.define("Ext.panel.Table", {
  alias: [
    "widget.grid",
    "widget.gridpanel"
  ]
});

```

```
```

