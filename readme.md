<!-- Coded Intro -->

```go
package main

import "fmt"

func main() {
	me := Info{
		General: General{
			Name:   "Nisarg Khodke",
			OS:     []string{"Windows 11", "Ubuntu", "Arch Linux"},
			IDE:    "NeoVim",
			Status: "Currently a Computer Science and Business Systems Student.",
		},

		TechStack: TechStack{
			LanguagesProgramming: []string{"Go", "Python", "JavaScript", "Java"},
			LanguagesComputer:    []string{"HTML", "CSS", "YAML", "JSON", "MARKDOWN"},
		},

		Hobbies: Hobbies{
			Virtual: []string{"Valorant", "Reverse Engineering"},
			Real:    []string{"Reading", "Origami"},
		},

		Contact: Contact{
			Email:    "nisargkhodke@gmail.com",
			LinkedIn: "nisargkhodke",
		},
	}

	me.FindIt()
}

func (me *Info) FindIt() {
	fmt.Println("Thanks for stopping by. Hope you find it in time...")
}

type Info struct {
	General
	TechStack
	Hobbies
	Contact
}

type General struct {
	Name   string
	OS     []string
	IDE    string
	Status string
}

type TechStack struct {
	LanguagesProgramming []string
	LanguagesComputer    []string
}

type Hobbies struct {
	Virtual []string
	Real    []string
}

type Contact struct {
	Email    string
	LinkedIn string
}

```

<!-- Stats  -->

 <div align="center">
	 
 <p>
	 
![Nisarg's Github Stats](https://github-readme-stats.vercel.app/api?username=Nisarg2061&show_icons=true&theme=tokyonight&hide_border=true)
![Nisarg's Github Streak](https://streak-stats.demolab.com?user=Nisarg2061&theme=tokyonight&hide_border=true)

 </p>
  
 </div>
