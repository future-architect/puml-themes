# puml-themes

PlantUML themes for all developers. 

## Abstract

These themes were created as part of a standardization effort to help design teams mass-produce business functions' processing flows. It is mainly intended for use in sequence diagrams.

For more details, please check [here(日本語)](https://future-architect.github.io/articles/20200203/). (available in Japanese only)

## Usage

Write `!include <This repository plantuml path>` between @startuml and @enduml block.

### Example of 'toy' theme

Use the theme from your diagram:

```
@startuml 
!include https://raw.githubusercontent.com/future-architect/puml-themes/master/themes/puml-theme-toy.puml

actor Foo1
boundary Foo2
control Foo3
entity Foo4
database Foo5
collections Foo6
note over Foo1: Event
Foo1 -> Foo2 : To boundary
Foo1 -> Foo3 : To control
Foo1 -> Foo4 : To entity
Foo1 -> Foo5 : To database
Foo1 -> Foo6 : To collections

@enduml
```

Output is bellow.

![](example/example_toy.png)


### Example of 'vibrant' theme

```
@startuml 
!include https://raw.githubusercontent.com/future-architect/puml-themes/master/themes/puml-theme-vibrant.puml

actor Foo1
boundary Foo2
control Foo3
entity Foo4
database Foo5
collections Foo6
note over Foo1: Event
Foo1 -> Foo2 : To boundary
Foo1 -> Foo3 : To control
Foo1 -> Foo4 : To entity
Foo1 -> Foo5 : To database
Foo1 -> Foo6 : To collections

@enduml
```

Output is bellow.

![](example/example_vibrant.png)



## License
This version of puml-themes is released under the Apache License, Version 2.0 (see [LICENSE](https://github.com/future-architect/puml-themes/blob/master/LICENSE)).
