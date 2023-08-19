---
layout: page
title: About
permalink: /about/
---

Some information about you!

### More Information

A place to include any other types of information that you'd like to include about yourself.

```mermaid
classDiagram
      Animal <|-- Duck
      Animal <|-- Fish
      Animal <|-- Zebra
      Animal : +int age
      Animal : +String gender
      Animal: +isMammal()
      Animal: +mate()
      class Duck{
          +String beakColor
          +swim()
          +quack()
      }
      class Fish{
          -int sizeInFeet
          -canEat()
      }
      class Zebra{
          +bool is_wild
          +run()
      }
```

### Contact me

[email@domain.com](mailto:email@domain.com)
