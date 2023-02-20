# Multireddi Auto Sub

- Visit any multireddit link/page

- Right click & Copy link address of multireddit of your subscriptions from right side

- Press CTRL+SHIFT+I to open Developer Tools window, then open the Console tab from there

- Paste the code bellow on the console input and press enter. Voila!


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
