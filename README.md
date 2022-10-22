<img src="https://komarev.com/ghpvc/?username=Shuinore&label=Ziyaretçi%20Sayısı&color=723F98" alt="Shuinore"/>

```js
class Shuinore {
  constructor(...options) {
    this.height = "1.75"
    this.weight = "64"
    this.age = "17"
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

[![Discord Presence](https://lanyard.cnrad.dev/api/453576139240112138)](https://discord.com/users/453576139240112138)

- ![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
- ![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white)
- ![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
- ![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white)
- ![Visual Studio](https://img.shields.io/badge/Visual%20Studio-5C2D91.svg?style=for-the-badge&logo=visual-studio&logoColor=white)
