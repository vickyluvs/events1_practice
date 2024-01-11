#[Exercise Link:](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/Test_your_skills:_Events#dom_manipulation_considered_useful)
#Instructions: 
In our first events-related task, you need to create a simple event handler that causes the text inside the button (btn) to change when it is clicked on, and change back when it is clicked again.
The HTML should not be changed; just the JavaScript.
#My Solution:
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
