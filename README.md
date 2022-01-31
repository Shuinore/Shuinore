```js
class Shuinore {
  constructor(...options) {
    this.height = "1.69"
    this.weight = "64"
    this.type = "human"
    this.job = "student"
    this.sex = "male"
  }
}

class CreateMan extends Shuinore {
  constructor(...options) {
    super(options);
  }
  
  private _eating() {
    void "eating 🥩 🍷"
  }
  
  private _coding() {
    void "coding... ❤️"
  }
  
  private _sleep(ms) { return new Promise(resolve => setTimeout(resolve, ms)) }
  
  async createDay() {
    this._eating();
    this._coding();
    await this._sleep(18000000);
    
    this.createDay();
  }
}

let Shuinore = new CreateMan()
Shuinore.createDay();
```

[![Discord Presence](https://lanyard-profile-readme.vercel.app/api/453576139240112138?hideDiscrim=true)](https://discord.com/users/453576139240112138)

## 🔧 Languages
- ![](https://img.shields.io/badge/Code-JavaScript-black?style=flat-square&logo=javascript&logoColor=brightgreen)
- ![](https://img.shields.io/badge/Code-Java-black?style=flat-square&logo=java&logoColor=white)
- ![](https://img.shields.io/badge/Tools-MongoDB-black?style=flat-square&logo=mongodb&logoColor=cyan)

<img src="https://komarev.com/ghpvc/?username=Shuinore&label=Ziyaretçi%20Sayısı&color=723F98" alt="Shuinore"/>
