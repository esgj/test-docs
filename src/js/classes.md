# JS Classes

```javascript
class Camaro {
    #hp;
    #isRunning;

    constructor(hp) {
        this.#hp = hp;
        this.#isRunning = false;
    }

    startEngine() {
        this.#isRunning = true;
    }

    get hp() {
        return this.#hp;
    }

    get isRunning() {
        return this.#isRunning;
    }
}
```

The '#' character thingy of a field/property makes it private.