# Coding-Challenge-3
u2863-9518
//create car class
class Car{
    constructor(make,speed)
    this.make=make
    this.speed=speed
}
// accelerate method to increase speed
    accelerate() {
        this.speed += 10;
        console.log(`${this.make} is going at ${this.speed} km/h`);
    }
   // brake method to decrease speed
    brake() {
        this.speed -= 5;
        console.log(`${this.make} is going at ${this.speed} km/h`);
    }  
// Test accelerate and brake methods on Car instances

const car1 = new Car('BMW', 120);
const car2 = new Car('Mercedes', 95);

console.log('--- Testing car1 ---');
car1.accelerate();  // BMW is going at 130 km/h
car1.brake();       // BMW is going at 125 km/h
car1.accelerate();  // BMW is going at 135 km/h
car1.brake();       // BMW is going at 130 km/h
