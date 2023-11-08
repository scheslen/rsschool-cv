# Halina Antonik
---

## Contacts
* Phone: +375 29 551 89 07
* e-mail: antgalin@mail.ru
* Discord: Halina A(@scheslen)

---
## About me
Versatile experience in designing, developing, testing, documenting, maintaining software products.
Responsibility, sociability,  learnability.

## Skills
* HTML / CSS
* JavaScript
* PHP
* Figma, Photoshop, 3DSMax
* Git / GitHub


## Education
* BSU, Institute of Business, Web design.
* BSU, Faculty of Applied Mathematics, with honors.


## Work Experience
* 2005 - to present
Leading Software Engineer.
ODO "Programming for You".

* 1989-2005
Leading Software Engineer.
Central Research Institute of Control Technologies.


## English

A2

## Code example

```
function convert(input, source, target) {
  let qBase=source.length;
  let qTarget=target.length;
  let aInput=input.split('');
  let sResult='';
  let r10=0;

  for(i in aInput){
     r10+=source.indexOf(aInput[aInput.length-i-1])*Math.pow(qBase,i);
  }
  while(r10>=qTarget){
    sResult+=target[r10%qTarget];
    r10=Math.floor(r10/qTarget);
  }
  sResult+=target[r10];

return sResult.split("").reverse().join("");
```


## Projects

CV
Hare
Bayan