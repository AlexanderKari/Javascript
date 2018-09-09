1
``` javascript
let alex = {
    nafn:"Alexander",
    hsimi:5612323,
    gsm:8967452,
    
};
console.log(alex.gsm)
```
2
``` javascript
let family = {
    "parents":
        {
        "fathers": [{"name":"Jakob"},{"name":"Nonni"}],
        "mothers":[{"name":"Rakel"},{"name":"Sara"}]
        }
 };
console.log(family.parents.fathers[1].name)
```
3
``` javascript
let breakfast = {
    name:"The Lumberjack",
    price:9.95,
    ingredients:["eggs","sausage","toast","hashbrowns","pancakes"]
};
```
4
``` javascript
var savingsAccount = {
    balance: 1000,
    interestRatePercent: 1,
    deposit: function addMoney(amount) {
        if (amount > 0) {
            savingsAccount.balance += amount;
        }
    },
    withdraw: function removeMoney(amount) {
        var verifyBalance = savingsAccount.balance - amount;
        if (amount > 0 && verifyBalance >= 0) {
            savingsAccount.balance -= amount;
        }
    },
    // your code goes here
    printAccountSummary: function(){
        return "Welcome!\nYour balance is currently $"+this.balance+ " and your interest rate is "+this.interestRatePercent+"%."
    }
};

console.log(savingsAccount.printAccountSummary());
```
5
``` javascript
var donuts = [
    { type: "Jelly", cost: 1.22 },
    { type: "Chocolate", cost: 2.45 },
    { type: "Cider", cost: 1.59 },
    { type: "Boston Cream", cost: 5.99 }
];

// your code goes here
donuts.forEach(function(hae){
    console.log(hae.type+" donuts cost $"+hae.cost+" each")
    
})
```
6
``` javascript
function Pizza(verd, staerd, alegg) {
    this.verd = verd;
    this.staerd = staerd;
    this.alegg = alegg;   
}

let fpizza = new Pizza(8520,"stór","ostur,pepperoni")
let spizza = new Pizza(8420,"Lítil","ostur,skinka")
```

