**#Exercise Link:**<br>

https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/Test_your_skills:_Events#events_1<br>

**Instructions:** <br>

In our first events-related task, you need to create a simple event handler that causes the text inside the button (btn) to change when it is clicked on, and change back when it is clicked again.
The HTML should not be changed; just the JavaScript.<br>

**My Solution:**<br>

```
// Add your code here
      const changeText = () => {
        if (btn.innerHTML === "Machine is off") {
          btn.innerHTML = "Machine is on";
        } else {
          btn.innerHTML = "Machine is off";
        }
      };

      btn.addEventListener("click", changeText);
```
