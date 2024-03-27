import Foundation


func add(_ num1: Double, _ num2: Double) -> Double {
    return num1 + num2
}

func subtract(_ num1: Double, _ num2: Double) -> Double {
    return num1 - num2
}

func multiply(_ num1: Double, _ num2: Double) -> Double {
    return num1 * num2
}

func divide(_ num1: Double, _ num2: Double) -> Double? {
    guard num2 != 0 else {
        print("Error: Division by zero")
        return nil
    }
    return num1 / num2
}

func calculate(_ num1: Double, _ operatorSymbol: String, _ num2: Double) -> Double? {
    switch operatorSymbol {
    case "+":
        return add(num1, num2)
    case "-":
        return subtract(num1, num2)
    case "*":
        return multiply(num1, num2)
    case "/":
        return divide(num1, num2)
    default:
        print("Error: Invalid operator")
        return nil
    }
}

// Example usage
let num1 = 10.0
let num2 = 5.0
let operatorSymbol = "/"
if let result = calculate(num1, operatorSymbol, num2) {
    print("Result: \(result)")
}
