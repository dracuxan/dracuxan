<!-- Banner -->

<img src="https://i.imgur.com/mz4ym1F.png" style="max-height:550px"/>

<!-- Coded Intro -->

```go
package Nisarg2061

import "Nisarg2061/models"

func InfoGenerator() {
	me := models.Info{
		General: models.General{
			Name:   "Nisarg Khodke",
			OS:     []string{"Windows 11", "Ubuntu", "Arch Linux"},
			IDE:    "Neovim",
			Status: "Currently a Computer Science and Business Systems Student.",
		},

		TechStack: models.TechStack{
			LanguagesProgramming: []string{"Go", "Python", "JavaScript", "Java"},
			LanguagesComputer:    []string{"HTML", "CSS", "YAML", "JSON", "MARKDOWN"},
		},

		Hobbies: models.Hobbies{
			Virtual: []string{"Valorant", "Reverse Engineering"},
			Real:    []string{"Reading", "Origami"},
		},

		Contact: models.Contact{
			Email:    "nisargkhodke@gmail.com",
			LinkedIn: "nisargkhodke",
		},
	}

	me.Says("Thanks for stopping by. Hope you find it in time...")
}
```
