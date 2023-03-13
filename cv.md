## Irina Azizova
***
### Contacts
**tel, viber:** +79200388837

**email:** devazizova@mail.ru

**telegram:** @devazizova

**github:** [IrinaAzizova](https://github.com/IrinaAzizova)
***
### Briefly About Myself
I have good interpersonal skills, am an excellent team worker and very willing to learn and develop new skills.
I am reliable and dependable and often seek new responsibilities within a wide range of employment areas.
***
### My Skills
+ [x] HTML 5
+ [x] CSS 3
+ [x] JavaScript (ES 6+)
+ [x] SASS(SCSS), LESS, 
+ [x] Bootstrap 5
+ [x] Figma, Photoshop, Avocode
+ [x] Git & github
+ [x] Node.js, NPM
+ [x] Gulp
+ [x] Python (basic knowledge), SQL (basic knowledge), PHP (can read code)
***
### Code example
**function for countdown timer:**
```JavaScript
import addZero from "./addZero"; // function for adding zero, if number < 10

const timer = (deadLine, daysSelector, hoursSelector, minutesSelector, secondsSelector) => {

    const days = document.querySelector(daysSelector),
        hours = document.querySelector(hoursSelector),
        minutes = document.querySelector(minutesSelector),
        seconds = document.querySelector(secondsSelector),
        end = (new Date(deadLine)).getTime();
    let time;
    
    let startTimer = setTimeout(setTime, 1000);
    setTime();

    function getTime() {
        time = end - (new Date()).getTime();
        
        const d = Math.floor(time /(1000 * 60 * 60 * 24)),
              h = Math.floor(time / (1000 * 60 * 60) % 24),
              m = Math.floor(time /(1000 * 60) % 60),
              s = Math.floor(time /1000 % 60);

        return {time, d, h, m, s};
    } 
    
    function setTime() {   
        const result = getTime();

        days.textContent = addZero(result.d);
        hours.textContent = addZero(result.h);
        minutes.textContent = addZero(result.m);
        seconds.textContent = addZero(result.s); 
        
        if (result.time > 0) {
            startTimer = setTimeout(setTime, 1000);
        }
    }   
};

export default timer;
```
more code examples in my github **[IrinaAziova](https://github.com/IrinaAzizova)**
***
### Experience
1. pharmacist
2. I have no experience in commercial development, but created a landing page, business card sites with a landing on CMS if necessary, web applications do not requiring a complex backend.
***
### Education
| year | higher education | educational institution |
|---|:---:|:---|
|2016 | Specialist, Pharmacist, Management and Economics of Pharmacy | Nizhny Novgorod Medical Academy |

| year | course | educational institution |
|---|:---:|:---|
| 2020 | Python Programming Fundamentals | HSE |
| 2021 | Python Data Structures, Using Python to Access Web Data | University of Michigan |
| 2021 | - Internet History, Technology, and Security | University of Michigan |
| 2021 | Introduction to Structured Query Language (SQL) | University of Michigan |
| 2021 | Animation, Data Manipulation and Interactivity with JavaScript and jQuery | University of California, Davis |
| 2021  | Foundations of User Experience (UX) Design | Google |
| 2021 | Subtleties of layout (HTML5, CSS3) | MIPT together with Yandex |
| 2021 | Advanced Styling with Responsive Design | University of Michigan |
***
### Languages
* Russian - native
* English  - Intermediate (B1) (according to the results of the test on puzzle-english.com)