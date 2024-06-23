---
title: Blog writing style
permalink: /demo
mathjax: true
mermaid: true
---

The website supports Markdown style.

## Photo

![photo](/img/img.jpg)

## Video

<iframe 
class="video" 
src="https://embed.ted.com/talks/lang/en/julian_treasure_how_to_speak_so_that_people_want_to_listen"
allowfullscreen>
</iframe>

## Code

```c
int main() {
	printf("hello world!");
	return 1;
}
```

Long code:

```
My father used to say, whatever you do, do it a hundred percent, when you work, work, when you laugh, laugh, when you eat, eat like it is your last meal.
```

## Quote

> the limits of my language mean the limits of my world.

## List

Unordered list:

- Math
- English

Ordered list:

1. Math
2. English

## Table

|       | Math   | English | Chinese | Politics |
| ----- | ------ | ------- | ------- | -------- |
| David | 80     | 80      | 50      | 100      |
| James | 70     | 80      | 90      | 100      |
| Me    | 100    | 90      | 100     | 100      |

Long table:

|       | Math   | English | Chinese | Politics | Japanese | Python | basketball | JS    |
| ----- | ------ | ------- | ------- | -------- | -------- | ------ | ---------- | ----- |
| David | 80     | 80      | 50      | 100      | 98       | 100    | 99         | 1     |
| James | 70     | 80      | 90      | 100      | 12       | 90     | 88         | 2     |
| Me    | 100    | 90      | 100     | 100      | 120      | 50     | 77         | 3     |

## Paragraph

- 2 Enter keys: move to the next line
- 2 spaces + 1 Enter key: line break within the same paragraph

## Text

Different font styles are allowed within a paragraph:

- *Italics* ：`*italics*`
- **Bold** ：`**bold**`
- ~~Delete~~ ：`~~delete~~` 
- <u>Underline</u> ：`<u>underline</u>`

## Formula

The relationship between the circumference $c$ and radius $r$ of a circle is as follows:

$$
c=2 \pi r
$$

## Flowchart

<div class="mermaid">
graph LR
    A --- B
    B-->C[fa:fa-ban forbidden]
    B-->D(fa:fa-spinner);
</div>

## Links

 - MPH APP: [Habitism]({{ site.app }})
