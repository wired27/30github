Got it! Here’s an update with **Day 1** and **Day 2** projects added.  

---

## 30GitHub Challenge  

### Programming Languages  
- Go (Golang)  
- 🚧 Work in Progress  

### Objectives  
🚧 Work in Progress  

📅 **Duration**: 30 Days  

---

## Progress  

| Day  | Project               | Status     |  
|------|-----------------------|-----------|  
| Day 0 | Hello, World!        | ✅ Completed |  
| Day 1 | Even or Odd Checker  | ✅ Completed |  
| Day 2 | Simple Calculator    | ✅ Completed |  

---

## Day 1: Even or Odd Checker in Go  

A simple program that checks whether a number is even or odd.  

```go
package main

import "fmt"

func main() {
    var num int
    fmt.Print("Enter a number: ")
    fmt.Scan(&num)

    if num%2 == 0 {
        fmt.Println(num, "is an even number.")
    } else {
        fmt.Println(num, "is an odd number.")
    }
}
```

---

## Day 2: Simple Calculator in Go  

A basic calculator that performs addition, subtraction, multiplication, and division based on user input.  

```go
package main

import (
    "fmt"
)

func main() {
    var num1, num2 float64
    var operator string

    fmt.Print("Enter first number: ")
    fmt.Scan(&num1)

    fmt.Print("Enter an operator (+, -, *, /): ")
    fmt.Scan(&operator)

    fmt.Print("Enter second number: ")
    fmt.Scan(&num2)

    switch operator {
    case "+":
        fmt.Printf("Result: %.2f\n", num1+num2)
    case "-":
        fmt.Printf("Result: %.2f\n", num1-num2)
    case "*":
        fmt.Printf("Result: %.2f\n", num1*num2)
    case "/":
        if num2 != 0 {
            fmt.Printf("Result: %.2f\n", num1/num2)
        } else {
            fmt.Println("Error: Division by zero is not allowed.")
        }
    default:
        fmt.Println("Invalid operator!")
    }
}
```

---

## References  
🚧 Work in Progress  

## 🛡️ License  
This project is open-source and available under the **MIT License**.  

Let me know if you want more improvements! 🚀