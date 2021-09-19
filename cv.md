#**Volha Dzikun**
##**Contact information:**
###**Phone:** +375 29 1286586
###**E-mail:** dicoun@gmail.com
###**Telegram:** @OlgaDicoun
###**Portfolio links:** 
*[JavaScript examples](https://github.com/dicoun/Homeworks) 
*[React examples](https://github.com/dicoun/FD3-Dicoun)
##**Personal qualities:** Sociability, easy to learn, self-possession, responsibility, single-mindedness, good efficiency. Good communication skills and team spirit gained through my study and work experience.
##**Computer skills and competences:**
*Programming languages and technologies: JS(ES5, ES6), ExtJS, React, Angular, TypeScript, Node.js, Zend-2, PHP, HTML/CSS;
*DBMS: MySQL, PostgresSQL;
*OS: Windows, Linux (Ubuntu);
*IDE: Visual Studio Code, JetBrains PhpStorm, dbForgeStudio for MySQL, pgAdmin;
*Version Control System: Git, SVN;
*Bug tracking system: Jira, Trello;
*Processes understanding of Agile Scrum;
##**Code example:**
*Implement the function which takes an array containing the names of people that like an item. It must return the display text as shown in the examples:*
(/images/task.example.png)
*Note: For 4 or more names, the number in "and 2 others" simply increases.*
```javascript
function likes(names) {
  switch (names.length){
      case 0:
        return 'no one likes this';
       break;
      case 1:
        return names[0] + ' likes this';
       break;
      case 2: 
        return names[0] + ' and ' + names[1] + ' like this';
       break;
      case 3:
        return names[0] + ', ' + names[1] + ' and ' + names[2] +' like this';
       break;
      default:
        return names[0] + ', ' + names[1] + ' and ' + (names.length - 2) +' others like this';
       break;
  }
}
```
