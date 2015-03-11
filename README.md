# craft-knife

Parameterized knife model.

### Install
	$ npm install craft-knife

### Parameters
- size: scales model
- length: adjusts length of knife

### Example
```html
<craft>
	<craft name="knife" module="craft-knife"/>
	<lineup spacing = "2">
		<knife length="15" size="2"></knife>
		<knife length="20"></knife>
		<knife></knife>
	</lineup>
</craft>
```

![example](example.png)