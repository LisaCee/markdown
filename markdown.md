## Headings and styling
Lisa is cool. 

Lisa is really cool.

**Bold**

_italic_

~~strikethrough~~

# h1
## h2
### h3

h1
==========================
h2
-------------------

## Links
<https://www.lisacanini.com>

[text link](https://www.lisacanini.com "This is my site")

This is a sentence with a [link][1] and I don't want it to be hard to read.

[1]: https://www.lisacanini.com

![A picture of Prince wearing a purple jacket with two windows behind him, one showing daytime with blue sky and clouds, the other showing a dark sky with a crescent moon](https://www.rollingstone.com/wp-content/uploads/2019/11/prince-1999-feature.jpg "this is the tooltip text")

![alt text][prince]

[prince]: https://www.rollingstone.com/wp-content/uploads/2019/11/prince-1999-feature.jpg

[link]: http://unsplash.it/500/500?image=1000
[thumbnail]: http://unsplash.it/50/50?image=1000

[![](http://unsplash.it/50/50?image=1000)]([[link]](http://unsplash.it/500/500?image=1000))

--or--

[<img src="http://unsplash.it/50/50?image=1000">](http://unsplash.it/500/500?image=1000)

## Image size
<img src="http://unsplash.it/500/500?image=1000" width="50" height="50" alt="">

<style>
img {
	width: 150px;
}
</style>

## Lists
- Bullet
+ Another one
* One more 

1. Item
	- Candy
    	- Thing
			This is inline

			This is a paragraph
2. Item
3. Item

## Line breaks
Lisa is cool.<br>
She is really cool.

I love you.

Something

---

Something else

>This is a quote - **Lisa**
>
> Another line

## Code blocks
Here is a code block:

	var x = 100;
	const dog = 'lola';

```php
$age = 50;
$name = "scott"
echo strtoupper($name);
```

Hey did you try `var x= 100;`?

```diff
var x = 100;
- var y = 200;
+ var y = 300;
```

## Tables
|Dog's Name| Dog's Age| Dog's Color |
|:------------|:------:|-----:|
|Snickers  | 2|brown|
|Prudence  | 8|white|

## Github Treats
* [x] Checkbox 1
* [ ] Checkbox 2

