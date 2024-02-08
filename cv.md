# Santalava Uladzislava

## Junior Frontend Developer
---
## Contact information:
🇵🇱**Location:** Poland, Warsaw.\
📱**Phone:** +48 789 632 433\
✉️**E-mail:** santalova.lada25@gmail.com\
👋**Telegram:** @sunlaa\
🔮**Discord:** @sunlaa\
💾**GitHub:** [sunlaa](https://github.com/sunlaa)

---
## Brief information about me
I am 20 years old and by now I have been studying web technologies for about 1.5 years. I got interested in programming at school. I always liked solving math problems, finding new solutions on my own, and being happy when everything worked out. In addition, my strengths include attentiveness, calmness and immersion in what I do. My goal is to gain knowledge and use it to develop myself. 


---
## Skills
- HTML, CSS
- JavaScript
- React (basics)
- Git, GitHub

---
## Code example
*[Task](https://www.codewars.com/kata/65127141a5de2b1dcb40927e)*

**Description:** we are given an array of a random number of "left" and "right" strings. Each such element rotates something to the right or back to the left by 90 degrees. Our task is to calculate the number of full rotations of 360 degrees.\
*As here:*
```
["left", "right", "left", "right"] ➞ 0
["right", "right", "right", "right", "right", "right", "right", "right"] ➞ 2
```
**My solution:**
```javascript
function spinAround(turns) {
  let a = 0
  let b = 0
  let sum = 0
  for (let dir of turns) {
    if (dir == 'right') {
      a++
    } else if (dir == 'left') {
      b++
    }
  }
  
  (a > b) ? sum = a - b : sum = b - a
  
  return Math.floor(sum/4)
}
```

---
## Training received
- Taking micro-courses on the **Stepik** educational platform
- Learning JavaScript from Ilya Kantor's tutorial **["The Modern JavaScript Tutorial"](https://learn.javascript.ru/)**
- Learning the basics of React through **[the official documentation](https://react.dev/learn)**

---
## My projects
**[Coffee-house](https://rolling-scopes-school.github.io/sunlaa-JSFE2023Q4/coffee-house/home.html)**  
**[Nonograms](https://rolling-scopes-school.github.io/sunlaa-JSFE2023Q4/nonograms/)**  
**[Hangman](https://rolling-scopes-school.github.io/sunlaa-JSFE2023Q4/hangman/)**  

---
## Language
- **Russian**
- **Belarusian**
- **English**
  - [EPAM English test result](https://examinator.epam.com/Main/PersonalAssignments): **B1(Intermediate)**\
  At the moment I live in Poland and I use English to communicate. I am learning English now through lessons, videos and self-talk with recordings.