---
title: Rich Content
layout: post
New field 2: Rich Content
categories:
- formatting
author:
- Dhruv Suthar
- Kiran Vadodariya
tags:
- formatting
- content
- rich
tweets:
- https://twitter.com/SpaceX/status/1257328055816601600
- https://twitter.com/narendramodi/status/1263384064616103937
---

This post shows, what possibly rich content could mean, and how it becomes so easy to use, the following content. We'll be looking onto Twitter, Youtube, UML Diagrams, Mathematical Expressions with Symbols and Emojis.

### Let's Tweet
Consider the following Tweets from SpaceX and Narendra Modi :

{% for tweet in page.tweets %}
  {% twitter tweet maxwidth=350%}
{% endfor %}

### Let's Youtube
Consider this beautiful video :

![](https://www.youtube.com/watch?v=fVsONlc3OUY)

### Rich Tables

|--|--|--|--|--|--|--|--|
|♜| |♝|♛|♚|♝|♞|♜|
| |♟|♟|♟| |♟|♟|♟|
|♟| |♞| | | | | |
| |♗| | |♟| | | |
| | | | |♙| | | |
| | | | | |♘| | |
|♙|♙|♙|♙| |♙|♙|♙|
|♖|♘|♗|♕|♔| | |♖|

### Rich Mathematics
$ a * b = c ^ b $

$ 2^{\frac{n-1}{3}} $

$ \int\_a^b f(x)\,dx. $

### Rich UML Diagrams

Class Diagram of a Cat

```plantuml
skinparam classAttributeIconSize 0
class Cat {
 -breed
 -color
 +meow()
 +purr()
}

```

Random Class Diagram


```plantuml
Class01 <|-- Class02
Class03 *-- Class04
Class05 o-- Class06
Class07 .. Class08
Class09 -- Class10
```

### Last but not Least : Emojis :

:india: Jai Hind!!  :india:
