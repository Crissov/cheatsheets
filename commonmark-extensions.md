HTTP://a.href

[a-href]  [a-href][]

[[a]]  [[a|href]]

[a][id]
[id]: href (title)

_i_

__b__

____u____

^sup^ ^(sup) ^^sup^^

~sub~ ~(sub) ~~sub~~ _(sub)

~~del~~ --del--

++ins++

==mark==   ???mark???

"q"

""cite""  """cite"""

>>stripped comment<<  <!--- stripped comment --->  {::COMMENT}stripped comment{:/COMMENT}

dl dt
:   dl dd

dl dt
  ~ dl dd

=dl dt=
    dl dd

2. ol[start] li
4. ol li[value]

a. ol li

a) ol li

#. ol li

#) ol li

- [ ] li.task.todo
- [X] li.task.done

text[^id]
  [^id]: note

text^[note]

text[#id]
  [#id]: citation

[@citekey]

abbr
  *[abbr]: title

[abbr](ABBR:title)

[span](CLASS:class)

[span](ID:id)

[](RAW:pass-through verbatim)

<<[transclude](file.ext)

<<(file.ext)

{{file.ext}}

-> p.center <-

C> p.center

A> aside

W> p.warning

T> p.tip

E> p.error

I> p.information

Q> p.question

D> p.discussion

X> p.exercise

G> p.generic

B> p.blurp

>! p.spoiler

> (cite) blockquote[cite]

> %class% 
> div.class

::: class
div.class
:::

| p[style="white-space:pre-wrap"]

(@) p.example
(@id) p.example#id

ca (@href)

!!! class
    div.class.admonition

![alt](img.src "title" =640x480)

=== [figcaption]
![](figure.src)
===

% title
% author
% date

---
metadata: YAML
---

@username  @groupname  @all

#tag  #issue

!request

$snippet

~label

:emoji: [](http://www.emoji-cheat-sheet.com)

{: #id .class attr="value"}

{#id .class attr="value"}

{key=value}

{PAGEBREAK}
{FRONTMATTER}
    {half-title}
    {series-title}
    {title-page}
    {copyright}
    {dedication}
    {epigraph}
    {toc}
    {figures}
    {tables}
    {foreword}
    {preface}
    {acknowledgments}
    {introduction}
    {abbr}
    {chronology}
{MAINMATTER}
{BACKMATTER}
    {appendices}
    {notes}
    {glossary}
    {bibliography}
    {contributors}
    {illustration-credits}
    {index}

[[TOC]]  [TOC]  @[TOC](h3)

$math$ \(math\) \\(math\\) {$$}math{/$$}

$$math$$ \[math\] \\[math\\]

@[videoservice](videoid)

```math
```

```poem
```

```art
```

key: value
…
[%key]

[-[ QR code ]-]
