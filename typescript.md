#Answer

```js
function speak(value: string): void {
  document.body.textContent = value;
}

var greeted: string = 2;
var greeting: string = 3;
var whatToSay: string = greeting + greeted;

speak(whatToSay);
```
