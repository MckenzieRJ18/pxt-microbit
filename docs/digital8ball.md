input.onGesture(Gesture.Shake, function () {
    basic.clearScreen()
    randomNumber = randint(0, 7)
    if (randomNumber == 2) {
        basic.showString("YES")
    } else if (randomNumber == 1) {
        basic.showString("INDEED")
    } else if (randomNumber == 3) {
        basic.showString("MAYBE")
    } else if (randomNumber == 4) {
        basic.showString("OF COURSE")
    } else if (randomNumber == 5) {
        basic.showString("ABSOLUTELY")
    } else if (randomNumber == 6) {
        basic.showString("CERTAINLY")
    } else if (randomNumber == 7) {
        basic.showString("I DON'T KNOW")
    }
    basic.showNumber(8)
})
let randomNumber = 0
basic.showString("ASK A QUESTION")
basic.showNumber(8)
