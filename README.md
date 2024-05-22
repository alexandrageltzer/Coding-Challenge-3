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
