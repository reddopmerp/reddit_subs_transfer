# Transfer Reddit Account Subs

- Visit https://old.reddit.com/subreddits/ using your old account

- Right click & Copy link address of **_multireddit of your subscriptions_** from right side
    > It will give you a link address like this: https://old.reddit.com/r/[subreddit1+subreddit2...+subredditXYZ] <br>
    > <sub>Please note that if you have a lot of subreddits the link won't work because there's a limit to the link's length, you can simply split it to two or three links</sub>
    
- Visit that link using your new account.

- Press **_CTRL+SHIFT+I_** to open _Developer Tools_ window, then open the **Console** tab from there

- Paste the code bellow on the console input and press enter. Voila!

```javascript
const sub = () => {
	let btn = document.querySelector(".add.active");
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
