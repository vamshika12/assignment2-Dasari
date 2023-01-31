# Vamshika Dasari
I am from most popular country in the world that is INDIA. I am Ambivert and want to be independent. Happiness looks gergeous on me. I love photography and travelling. I like chocolates and pizza.I came to USA for my master's.

![link](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQMz_14NjxRFlG6Qff2dZWaYJca_TIdi9SVsA&usqp=CAU)

*******

# Country Table

|Country Name    |   Reason                      | Time to spent(Days)
|----------------|:-----------------------------:|------------------:|
|Paris           |For site seeing and crossiants | 15-20days         |
|Maldives        |For best snorkelling and diving| 10-15days         |
|America         |To experience culture          | 1 month           |
|Indonesia       |Beaches and magical temples    | 20 days           |

********

# Quotes

> Even in hard times there's a possibility to have fun. _Vamshika_

> Live for today and let tomorrow come later. _Vamshika_

*********

>SVG patterns scaling the way pattern is not cut off
>I'm trying to discover the way to scale svg patterns so that the pattern is not cut by the bounds of the element using it. And yet so that pattern is beeing repeated to cover that element.Let's say i have a 20px radius circle as a pattern. Applying it to 80px width element.

```php

<svg style='display: block; height: 60px; width: 95px; '>
    <defs>
        <pattern patternUnits='userSpaceOnUse' viewBox='0 0 20 20' width='20'  height='20' id='the_pattern'>
            <circle cx='10' cy='10' r='10' stroke-width='0' fill='black'></circle>
        </pattern>
    </defs>

    <rect x='0' y='0' width='80' height='20' fill='url(#the_pattern)'></rect>
    <rect x='0' y='20' width='90' height='20' fill='url(#the_pattern)'></rect>
    <rect x='0' y='40' width='95' height='20' fill='url(#the_pattern)'></rect>

</svg>
```
Answer

```
.circle-border {
  border-top: 30px solid;
  border-image: url('https://interactive-examples.mdn.mozilla.net/media/examples/border-diamonds.png') 30 / 20px 0 0 0;
  border-image-repeat: round;
}

div {
  width: 80px;
  height: 0px;
  margin-bottom: 50px;
}

div:nth-child(2) {
  width: 90px;
}

div:nth-child(3) {
  width: 100px;
}
```
