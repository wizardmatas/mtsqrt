package main

import (
	"fmt"
	"math"
)

func Sqrt(x float64, lim int, t float64) float64 {
	var z float64 = 1
	var e float64
	for i := 1; i < lim; i++ {
		z -= (z*z - x) / (2 * z)
		fmt.Println("Iteration and z value", i, z)
		e = (z * z) - x
		fmt.Println("Iteration and e value ", i, e)
		if e < t {
			break
		}
		fmt.Println(z)
	}
	return z
}

func main() {
	fmt.Println(Sqrt(2, 100, 0.0000000000001))
	fmt.Println(math.Sqrt(2))
}
