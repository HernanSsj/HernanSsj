```javascript
function Developer(name, age) {
    this.name = name
    this.age = age
    this.languajes = ["Javascript","Python"]
    this.frameworks = ["React", "ReactNative"]
    this.otherTools = ["Sequelize", "Express","Expo","Node"]
    this.databases = ["PostgreSql", "GoogleFirestore"]
}

Developer.prototype.getResume = function () {
  console.log(`Hi mi name is ${this.name} im a backend developer mainly working with: ${this.languajes}`);
}

       
const me = new Developer("Hernan", 22)

me.getResume()
