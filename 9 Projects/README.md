# Projects related to DOM

## project link 
[Click here](https://github.com/abdulrahmans0414/MasteryJavaScript)

# Solution code 

## Project - 1 
## Color Scheme Switcher

```javascript
console.log("Abdul Rahman");

// Select Body and Button 
const body = document.querySelector("body")
const buttons = document.querySelectorAll(".button")


// event
buttons.forEach(function (button) {
    // console.log(button);
    button.addEventListener("click", function (e) {

        // console.log(e);
        // console.log(e.target);

        if (e.target.id === "grey") {
            body.style.backgroundColor = e.target.id;
        }
        if (e.target.id === "white") {
            body.style.backgroundColor = e.target.id;
        }
        if (e.target.id === "blue") {
            body.style.backgroundColor = e.target.id;
        }
        if (e.target.id === "yellow") {
            body.style.backgroundColor = e.target.id;
        }

    });
})
```