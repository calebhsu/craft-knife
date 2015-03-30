# craft-knife

Parameterized knife model.

### Install
    $ npm install craft-knife

### Parameters
- length: adjusts length of knife

### Example
```html
<craft>
    <craft name="knife" module="calebhsu/craft-knife"/>
    <lineup spacing = "2">
        <scale factor="2">
            <knife length="15"></knife>
        </scale>
        <knife length="20"></knife>
        <knife></knife>
    </lineup>
</craft>
```

![example](example.png)