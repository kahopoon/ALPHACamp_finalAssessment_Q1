# ALPHACamp_finalAssessment_Q1
```swift
// first odd + last odd * count 's half... hahaha
let totalOfOneToHundred_A = (1 + 99) * 50 / 2

// array of 1 to 100, filter out even number, map ? we dont need to manipulate this time, reduce by adding up...
let totalOfOneToHundred_B = Array(1...100).filter{ $0 % 2 != 0 }.reduce(0){ $0 + $1 }

// ok back to human lanugage...
var totalOfOneToHundred_C = 0
for loop in 1...100 where loop % 2 == 1 {
    totalOfOneToHundred_C += loop
}
```
