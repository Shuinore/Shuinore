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

<img src="https://komarev.com/ghpvc/?username=Shuinore&label=Ziyaretçi%20Sayısı&color=723F98" alt="Shuinore"/>
