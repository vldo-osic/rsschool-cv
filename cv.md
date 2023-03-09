# **Vlad Makshanov** #
---
### **Contact info**:
* __phone:__ *+7 931 221 32 13*
* __e-mail__: *vldo.osic@gmail.com*
* __telegram__: *@vldoosik*
* __VK__: *vldo_osik*
---
### **About me**
#### I'm a 19-year-old frontend developer from Moscow. At the moment I'm creating pet projects using html+css+js. I also participate in math and programming Olympiads like ICPC and RUcode. ##
##### __My strengths:__ 
* ##### *communication skills*
* ##### *quick learner*
* ##### *curiosity*
* ##### *algorithmic thinking*
---
### **Skills**
* ##### *algorithms*
* ##### *OOP ( Patterns, SOLID, GRASP, KISS)*
* ##### *React + Redux*
* ##### *JavaScript (Fundamentals, ES6+, DOM, JSON, Asynchrony, functional programming)*
* ##### *Git/GitHub*
* ##### *HTML*
* ##### *CSS(SCSS, BEM)*
---
### **Code Example**
> __Replace With Alphabet Position__
You are required to, given a string, replace every letter with its position in the alphabet.
If anything in the text isn't a letter, ignore it and don't return it. 
"a" = 1, "b" = 2, etc.
**Example**
alphabetPosition("The sunset sets at twelve o' clock.")
Should return
"20 8 5 19 21 14 19 5 20 19 5 20 19 1 20 20 23 5 12 22 5 15 3 12 15 3 11"

**Solution**
```js
function stringToLetterArray(string) {
    const comparator = /[\d\W_]?/
    return string.toLowerCase()
                 .split(comparator)
                 .filter(element => element !== '')
                 
}
function alphabetPosition(text) {
    const UNICODE_DIFF = 96;
    return stringToLetterArray(text)
        .reduce(
            (accum, letter) => 
                `${accum} ${letter.charCodeAt(0) - UNICODE_DIFF}`
                    , '')
        .slice(1)
}
```
---
### **Education**
#### National University of Science and Technology "MISIS" (2022 - 2026)
##### Studying in a specialized group with a focus on mathematics and data analysis
---
### **Languages**
* #### Russian - native speaker
* #### English - B2