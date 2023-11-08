# Olena Chuikova
## Contacts
**Location:** Lisbon, Portugal

**GitHub:** [awoq](https://github.com/awoq)

**Discord:** Alyona#2530
## About me
*I had worked in the field of info business for some time. Finally, I realized that programming is what attracts me the most. Now I'm learning JavaScript and related technologies. I want to get more practice in front-end development, improve my skills and get new experience.*
## Skills
* HTML5
* CSS3
* JavaScript
* TypeScript
* Git
## Code Example
**7 kyu kata: [Get the Middle Character](https://www.codewars.com/kata/get-the-middle-character)**

Task: *You are going to be given a word. Your job is to return the middle character of the word. If the word's length is odd, return the middle character. If the word's length is even, return the middle 2 characters.*
```javascript
function getMiddle(s) {
    let length = s.length;
    if(length % 2 > 0) {
        let middleIndex = (length - 1) / 2;
        return s.substr(middleIndex, 1)
    }
    else {
        let middleIndex = (length / 2) - 1;
        return s.substr(middleIndex, 2)
    }
}
```
# Experience 
* [Museum](https://rolling-scopes-school.github.io/awoq-JSFE2021Q3/museum-dom/) *Landing page with a form for bying tickets (HTML5, CSS3, JavaScript)*
* [Momentum](https://rolling-scopes-school.github.io/awoq-JSFE2021Q3/momentum/) *Analogue of the self-titled Google Chrome extension (JavaScript, HTML5, CSS3)*
* [Art Quiz](https://rolling-scopes-school.github.io/awoq-JSFE2021Q3/art-quiz/) *SPA quiz on the knowledge of painting masterpieces and their authors (JavaScript, HTML5, CSS3)*
* [Chritmas Task](https://rolling-scopes-school.github.io/awoq-JSFE2021Q3/christmas-task/) *SPA with filters and drag-and-drop (TypeScript, HTML5, CSS3)*