- 👋 Hi, I’m @Lilpresh-hub
- 👀 I’m interested in ...***Getting more ideas in creating a multi-device almighty WhatsApp bot***
- 🌱 package main

import "fmt"

type Person struct {
  name string
  username string
  age int
  hobbies []string
  job string
}

func main() {
  var me = new(Person)
  
  me.name     = "Lilpresh-hub"
  me.username = "Lilpresh-hub"
  me.age      = "20"
  me.job      = "AI developer | Web developer"
  me.hobbies  = []string{"code", "anime", "music","gaming"}
  
  fmt.Println(me)
}
