---
layout: solution
title: HTML Solution | Display Message
---

## Display "Hello HTML5" with a doctype and root element

### Source
~~~html
<!DOCTYPE html>

<html>
  <body>
    package main

    import "fmt"

    func main() {
        fmt.Println("Hello, golang!")
    }
  </body>
</html>
~~~

### Result
<section>
package main import "fmt" func main() { fmt.Println("Hello, golang!") }
</section>

### Discussion

{% include html_sol/messline.md %}