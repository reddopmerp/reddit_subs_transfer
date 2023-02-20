# Multireddi Auto Sub


```javascript
const sub = () => {
	let btn = document.querySelector("._3P6gMBKOhtWWrytWm-8hc > button._10BQ7pjWbeYP63SAPNS8Ts");
	if(btn) {
		btn.click();
		setTimeout('sub()', 500);
	} else {
		alert("You have subscribed to all the subreddits successfully");
		return;
	}
}
setTimeout('sub()', 500);
```
