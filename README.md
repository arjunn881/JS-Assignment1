// Question 1:
var str1 = 'Today is';
var str2 = '      a beautiful day     '
var str3 = ' In Hawaii.     '

var result = str1.trim() + " " + str2.trim() + str3.trim()

console.log(result.trim())

//Question 2

var input = 'd' || "D"
// you can also input by uncommenting
//var input= prompt("input:")


switch (input) {
    case "a":
        console.log("vowel")
        break
    case "e":
        console.log("vowel")
        break
    case "i":
        console.log("vowel")
        break
    case "o":
        console.log("vowel")
        break
    case "u":
        console.log("vowel")
        break
    case "A":
        console.log("vowel")
        break
    case "E":
        console.log("vowel")
        break
    case "I":
        console.log("vowel")
        break
    case "O":
        console.log("vowel")
        break
    case "U":
        console.log("vowel")
        break
    case "d":
        console.log("consonant")
        break
    case "D":
        console.log("consonant")
        break
    default:
        console.log("non-Alphabet")


}

//Question 3

var valA = parseInt(prompt("A :"))
var valB = parseInt(prompt("B :"))



var operator = prompt("operator :")

switch (operator) {
    case "+":
        console.log(valA + valB)
        break

    case "-":
        console.log(valA - valB)
        break

    case "*":
        console.log(valA * valB)
        break

    case "/":
        console.log(valA / valB)
        break

    default:
        console.log("NOT AN OPERATOR")
}

//Question 4

var a = parseInt(prompt('a :'))
var b = parseInt(prompt('b :'))
var c = parseInt(prompt('c :'))


if (a == 0 || b == 0 || c == 0) {
    console.log("side of triangle can't be 0")
}

if (a == b && b == c) {
    console.log("triangle is said Equilateral Triangle")
}
else
    if (a == b || b == c || c == a) {
        console.log("triangle is said Isosceles Triangle")
    }

    else


        console.log("triangle is said Scalene Triangle")



//Question 5

var unit = 300
var total
var result

if (unit <= 50) {

    total = (unit * 0.50)
    result = total + (total * 0.20)
    console.log(result)
}
else
    if (unit <= 150) {
        total = (50 * 0.5) + ((unit - 50) * 0.75)
        result = total + (total * 0.20)
        console.log(result)

    }
    else
        if (unit <= 250) {
            total = (50 * 05) + (100 * 0.75) + ((unit - 150) * 1.20)
            result = total + (total * 0.20)
            console.log(result)
        }
        else {

            total = (50 * 0.5) + (100 * 0.75) + (100 * 1.2) + ((unit - 250) * 1.50)
            result = total + (total * 0.20)
            console.log(result)
        }
