# scrumPitch

TOC
@title[Agenda]


## Code

```html
package main

import "fmt"

func main() {
    fmt.Println("Hello, world!")
}
```
@[1](Go package main for executable command)
@[3]
@[5-7]

+++

### Code-Delimiter Slides
##### Using
#### **Code-Presenting**

---

* https://github.com/gitpitch/gitpitch/wiki/Getting-Started
* https://github.com/gitpitch/gitpitch/wiki/Developing-Testing-Locally
* https://github.com/gitpitch/gitpitch/wiki/Slideshow-Offline

---

### Speaker Notes

Note:
Remember to explain why it's for everyone: no sign-up, nothing to install.
Just MD. Then git-commit.

For quick review: add ?n=true e.g. https://gitpitch.com/onetapbeyond/gen_metrics?n=true

+++

### Naturally
### Code-Presenting
### works in exactly the same way on [Code-Delimiter Slides](https://github.com/gitpitch/gitpitch/wiki/Code-Delimiter-Slides) as it does on [Code-Blocks](https://github.com/gitpitch/gitpitch/wiki/Code-Slides).

---

## Images

![Logo](assets/logo.png)

+++

## Font Awesome

@fa[thumbs-up](Sounds good to me!)

---

<canvas data-chart="line">
<!-- 
{
 "data": {
  "labels": ["January"," February"," March"," April"," May"," June"," July"],
  "datasets": [
   {
    "data":[65,59,80,81,56,55,40],
    "label":"My first dataset","backgroundColor":"rgba(20,220,220,.8)"
   },
   {
    "data":[28,48,40,19,86,27,90],
    "label":"My second dataset","backgroundColor":"rgba(220,120,120,.8)"
   }
  ]
 }, 
 "options": { "responsive": "true" }
}
-->
</canvas>

---

<canvas class="stretch" data-chart="bar">
My first dataset, 65, 59, 80, 81, 56, 55, 40
<!-- This is a comment that will be ignored -->
My second dataset, 28, 48, 40, 19, 86, 27, 90
<!-- 
{ 
 "data" : {
  "labels" : ["Enero", "Febrero", "Marzo", "Avril", "Mayo", "Junio", "Julio"], 
  "datasets" : [{ "borderColor": "#0f0", "borderDash": ["5","10"] }, { "borderColor": "#0ff" } ]
 }
}
-->
</canvas>

---

<canvas data-chart="radar">
Month, January, February, March, April, May, June, July
My first dataset, 65, 59, 80, 81, 56, 55, 40
My second dataset, 28, 48, 40, 19, 86, 27, 90
</canvas>

+++

### Do the Math

$$\sum_{i=0}^n i^2 = \frac{(n^2+n)(2n+1)}{6}$$

+++

TOC
@title[Some custom label]

