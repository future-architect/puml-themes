# puml-themes

PlantUML theme for all developper.

## Usage

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
Foo1 -> Foo2 : To boundary
Foo1 -> Foo3 : To control
Foo1 -> Foo4 : To entity
Foo1 -> Foo5 : To database
Foo1 -> Foo6 : To collections

@enduml
```

## License
This version of giglocal is released under the Apache License, Version 2.0 (see [LICENSE](https://github.com/future-architect/puml-themes/blob/master/LICENSE)).
