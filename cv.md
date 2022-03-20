# Aliaksei Pauliuchyk
- Discord: [alx (@Alexey0795)](https://discord.com/users/Alexy796#9678) 
- GitHub: [@Alexey0795](https://github.com/Alexey0795)
- Telegram: [t.me/alx795](https://t.me/alx795)

### About Me

### Skills
- VBA
- C#, NUnit, ASP.Net, Blazor server
- SOLID, gof patterns
- GitHub, GitLab
- python, js
- vs code, Visual Studio, PyCharm
- mongoDB, MySql
- Docker

### Code Examples
Detect Pangram
```
function isPangram(string){
  let arr = [...Array(26).keys()].map(i => i++ + 65);
  arr = arr.map(x => String.fromCharCode(x));
  for(let i = 0; i < string.length; i++)
    {
      arr = arr.filter(element => element != string[i].toUpperCase())
      if (arr.length == 0) return true
    }
    return false;
}
```

### Education
- FoxmindEd  GRASP and GoF Design patterns Advanced On-line Course
- FoxmindEd  С#/.Net
- RS Schools Course «JavaScript/Front-end. Stage 1» (in progress)

### Languages
- English A2/B1 (reading documentation, listening to lectures, watching films and educational videos)
- Russian (native speaker)