# Julia Sinkova

👋 I'm a QA engineer based in Batumi, Georgia with experience in test automation using JS. My goal is to deepen my knowledge in javascript and become a front-end developer

### **Contact**

📧 juliasinkova97@gmail.com

📞 +7 923 714 85 40

👾 discord:  @juliasinkova

🔗 https://github.com/JuliaSinkova

# Skills

- HTML
- CSS/SCSS
- JavaScript/Typescript
- React
- Redux
- Git
- Linux
- SQL
- Figma

# Code examples

```jsx
/*
Morse code decoder function
(The Morse code table MORSE_CODE is imported additionaly)
*/

let decodeMorse = function(morseCode){
  let words = morseCode.split("   ");
  words = words.filter(i => i != '');
  let result = [];
  words.forEach(i => {
    let word = [];
    let letters = i.split(" ");
    letters.forEach(i => word.push(MORSE_CODE[i]));
    word = word.join('');
    result.push(word);
  })
  result = result.join(' ');
  return result;
  
}
```

```jsx

/* Function maskify changes all but the last four
 characters of a credit card number into '#'.
*/

function maskify(cc) {
 let arr = cc.split('');
  let result = [];
  let num = arr.length - 4;
  arr.forEach((item, indx) =>{
    if(indx < num) result.push("#");
    else{result.push(item)}
  });
  result = result.join('');
 
 return result;
}
```

# Experience

### Frontend intern

Responsibilities:

• Development of responsive web pages using React and Typescript.

### QA Engineer

Responsibilities:

- Performing functional, regression, integration, smoke testing
- Identifying, recording, documenting and tracking bugs
- Writing automated test scripts using javascript (webriver io), evaluation of the results, making reports based on the results of execution
- API testing using Postman
- Writing test and user documentation (english and russian languages)


# Education

FRONTEND DEVELOPER course at https://hexlet.io/

## Altai State University (2015 - 2019)

 Bachelor's Degree in Linguistics

# Languages:

- **Russian** -  Native speaker
- **English** - Proficient
- **German** - Intermediate level