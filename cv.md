
# **Berik Bazarov**

### You can contact me via:
  - **Mobile Phone:** +7 708 501 01 95
  - **Email:** berikbazar@yandex.com
  - **Telegram:** @alanapapa


### Summary
>Hello. I make site layouts. Always ready to learn something new and interesting. At the moment, I received a grant from the 01 alem programming school and am learning the Go programming language.
>I will be happy to work with open, responsible and helpful people who love their work.


### Skills
##### *Go, HTML/CSS, Bootstrap, CMS Wordpess.*


### Code example (LATEST) 
```Go
// code for ascii art in Golang

package main

import (
    "bufio"
    "fmt"
    "os"
    "strings"
)

func main() {
    file, _ := os.Open("standard.txt")
    fileVal := ScanFile(file)
    arg := os.Args[1]
    for _, v := range os.Args[2:] {
        arg += " " + v
    }
    narg := strings.Split(arg, "\\n")
    for _, v := range narg {
        printLetter(string(v), fileVal)
    }
}

func printLetter(s string, fileVal []string) {
    for i := 1; i <= 8; i++ {
        for _, arg := range s {
            indexBase := int(rune(arg)-32) * 9
            fmt.Print(fileVal[indexBase+i])
        }
        fmt.Println()
    }
}

func ScanFile(arg *os.File) []string {
    var fileValue []string
    scanner := bufio.NewScanner(arg)
    for scanner.Scan() {
        lines := scanner.Text()
        fileValue = append(fileValue, lines)
    }
    return fileValue
}
```


### Experience
[![N|Solid](https://i.pinimg.com/600x315/2c/b6/70/2cb670b6ddd8922a1c1b2fee4f6f758c.jpg)](https://github.com/alanapapa)
[![N|Solid](https://upload.wikimedia.org/wikipedia/commons/thumb/6/6c/Codecademy.svg/1280px-Codecademy.svg.png)](https://www.codecademy.com/profiles/berikBazarov1552389791)


### Education:
- _College **«Kazakh Academy of Transport and Communication»**, Logistician_
- _Coding school **«01 alem»**, Golang developer_


### English level: **A2**
*Currently studying with a native speaker.*

