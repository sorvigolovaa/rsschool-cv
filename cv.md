# Shahrimirzo Xayitboyev

### Junior Frontend Developer

---

### Contact information:

**Phone:** +99893-280-55-66<br>
**E-mail:** shahriking505@gmail.com<br>
**Telegram:** @sbknugaara<br>

---

### Briefly About Myself:

I am 21 years old. I am studying economics while studying programming this year, I finished courses, now I want to develop further in front-end development.<br>

---

### Skills:

- HTML5, CSS3, SCSS
- JavaScript Basics
- Git, GitHub
- VS Code, Figma

---

### Code example:

**Fizz Buzz**

_This function checks the entered number, and if this number is divisible by 3, then returns Fizz , and if the number is divisible by 5, then returns Buzz, and if the number is divisible by 3 and 5, then returns Fizz Buzz, and otherwise it prints the number itself._

```javascript
const elForm = document.querySelector("form");
const elInput = document.querySelector("input");
const elResult = document.querySelector(".result");

elForm.addEventListener("submit", function (e) {
  e.preventDefault();
  elResult.textContent = "Natija:";
  if (elInput.value % 3 === 0 && elInput.value % 5 === 0) {
    elResult.textContent += "FizzBuzz";
  } else if (elInput.value % 3 === 0) {
    elResult.textContent += "Fizz";
  } else if (elInput.value % 5 === 0) {
    elResult.textContent += "Buzz";
  } else {
    elResult.textContent += elInput.value;
  }
});
```

---

### Courses:

- HTML and CSS Tutorials on It academy in Tashkent<br>

---

### Languages:

- English \- A2
- Russian \- Native