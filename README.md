<p align="center">
  <h3 align="center">👋 Howdy, I'm Pao, nice to meet you</h3>
</p>

<p align="center">
  <a href="https://github.com/woonmapao?tab=stars"><img src="https://readme-typing-svg.demolab.com?font=Noto+Sans&duration=1000&pause=200&color=FF6E96&background=282A3600&center=true&vCenter=true&random=false&width=200&lines=%E6%94%B9%E5%96%84;mejorando;%D8%AA%D8%AD%D8%B3%D9%8A%D9%86;%E0%B8%9E%E0%B8%B1%E0%B8%92%E0%B8%99%E0%B8%B2;Improving" alt="Hello I'm Pao" /></a>
  
  
[![GitHub Streak](https://streak-stats.demolab.com?user=woonmapao&theme=dracula&hide_border=true&border_radius=6.9&card_width=1080)](https://github.com/woonmapao?tab=stars)
<a href="https://github.com/woonmapao?tab=stars"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&duration=100&pause=500&color=79DAFA&background=282A3600&vCenter=true&multiline=true&repeat=false&random=false&width=1080&height=350&lines=%F0%9F%9A%80+Greetings+fellow+Gophers!+I'm+a+23-year-old+enthusiast+in+pursuit+of+Go+mastery.;Working+on+something+cool%2C+and+also+learning+other+tech+stacks...;%F0%9F%93%9A+Learning+Go+is+a+lifestyle%2C+not+just+a+task.;%F0%9F%8C%90+Simultaneously+diving+into+other+technologies+while+mastering+the+basics.;Working+on+something+cool%2C+and+also+learning+other+tech+stacks...;Working+on+something+cool%2C+and+also+learning+other+tech+stacks...;%E2%9A%99%EF%B8%8F+Goroutines%2C+channels%2C+idiomatic+Go+code;Working+on+something+cool%2C+and+also+learning+other+tech+stacks...;%F0%9F%92%A1+Efficient+use+of+CPU+cores;Working+on+something+cool%2C+and+also+learning+other+tech+stacks...;%F0%9F%8C%90+Building+scalable+and+concurrent+systems;%F0%9F%93%88+Still+in+the+basics%2C+but+committed+to+learning+24%2F7.;Go+has+become+second+nature+to+me.+Time+to+master+the+intricacies+of+concurrency!" alt="Typing SVG" /></a>

<!-- markdownlint-enable MD033 -->

```go
package main

import (
	"fmt"
	"time"
)

const (
	birthYear   = 2001
	currentYear = 2023
)

var age = currentYear - birthYear

func main() {
	fmt.Printf("🚀 Greetings fellow Gophers! I'm a %d-year-old enthusiast in pursuit of Go mastery.\n", age)

	// Go-routine to simulate the asynchronous nature of my learning journey
	go learnGo()

	// Main thread focuses on other tasks
	for i := 0; i < 5; i++ {
		fmt.Println("Working on something cool, and also learning other tech stacks...")
		time.Sleep(500 * time.Millisecond)
	}

	// Waiting for the Go-routine to complete
	<-time.After(2 * time.Second)
	fmt.Println("Go has become second nature to me. Time to master the intricacies of concurrency!")
}

func learnGo() {
	fmt.Println("📚 Learning Go is a lifestyle, not just a task.")
	fmt.Println("🌐 Simultaneously diving into other technologies while mastering the basics.")

	topics := []string{"⚙️ Goroutines, channels, idiomatic Go code", "💡 Efficient use of CPU cores", "🌐 Building scalable and concurrent systems"}

	for _, topic := range topics {
		time.Sleep(1 * time.Second)
		fmt.Println(topic)
	}

	fmt.Println("📈 Still in the basics, but committed to learning 24/7.")
}

```
