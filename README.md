

<div align="center">
    <img src="https://media.tenor.com/hD56X-Q5AzMAAAAi/gopher-shaking.gif" alt="Gopher Shaking">

<img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=500&pause=1000&color=FFFFD5&width=435&lines=Hello,+I'm+diegodev2.">
        
</div>

```go
package main

import "fmt"

type User struct {
    Name           string
    Age            int
    NativeLanguage string
    Languages      []string
    Knowledge      []string
    Tools          []string
    Challenge      string
}

func main() {
    diegodev := User{
        Name:           "diegodev2",
        Age:            15,
        NativeLanguage: "ES",
        Languages:      []string{"Español", "Ruso", "Inglés"},
        Knowledge: []string{
            "Python", "Ethical Hacking", "NextJS", "React", "HTML", "CSS", "JavaScript",
            "Tailwind CSS", "Node JS", "Astro", "TypeScript", "Photoshop", "Docker", "Kubernetes",
            "Bash", "Go", "MacOS", "Kali Linux", "Black Arch", "ParrotSec OS", "C++", "C(Learning)",
            "Assembly(Learning)", "Git", "GitHub", "Figma",
        },
        Tools: []string{"React", "Node", "Docker", "Kubernetes", "Tailwind CSS"},
        Challenge: "I am focused on improving my skills in ethical hacking and expanding my programming knowledge.",
    }

    fmt.Printf("User Info: %+v\n", diegodev)
}
