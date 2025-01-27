# Intro to Markdown
## Headings
If you would like titles or subtitles, use the # symbol followed by a space and your word.
Increasing the number of # symbols up to six decreases the size of the header.
```
# Heading 1 for Big Impact Titles
## Heading 2 for Small impact Titles or Subtitles
### Heading 3 for small impact subtitles
```
# Heading 1
## Heading 2
### Heading 3


## Emphasis

Italicizing Text - Any text you would like to see itilicized should be wrapped with single astrix 
Bolding Text - Any text you would like to bold should be wrapped with a double astrix 
Striking Text - Any text you would like to strikethrough should be wrapped with double tildas
Highlighting Text - Any text you would like to highlight should be wrapped with a backtick
```
*This is Italicized*
**This is Bold**
***This is a Bold Italicization***
~~This is strikethrough~~
`This is highlighted`
```
*This is Italicized*\
**This is Bold**\
***This is a Bold Italicization***\
~~This is strikethrough~~\
`This is highlighted`

## New Line
If you are writing in markdown and want to move to a new line, simply put a \ immediately after your sentence.
```
Line 1\
Line 2\
Line 3
```
Line 1\
Line 2\
Line 3

## Hide Text with Dropdown Menus
If you want to make a dropdown menu with more info inside, use the following code:
```
<details>
<summary>How do I dropdown?</summary>
<br>
This is how you dropdown.
</details>
```
<details>
<summary>How do I dropdown?</summary>
<br>
This is how you dropdown.
</details>

## Lists
You can create bulleted lists or numbered lists by using a single astrix
or a number and period before your item, just like you would in Microsoft Word.
If you are doing a bulleted list, you can use tab to add a sub item.
```
1. Item 1
2. Item 2
3. Item 3
* Item 1
* Item 2
  * Subitem 2
* Item 3
```
1. Item 1
2. Item 2
3. Item 3
* Item 1
* Item 2
  * Subitem 2
* Item 3

## Todo Lists
Todo lists can be rendered by making a dashed list and boxed x's next to completed items
```
- [x] @mentions, #refs, [links](), **formatting**, and <del>tags</del> supported
- [x] list syntax required (any unordered or ordered list supported)
- [x] this is a complete item
- [ ] this is an incomplete item
```
- [x] @mentions, #refs, [links](), **formatting**, and <del>tags</del> supported
- [x] list syntax required (any unordered or ordered list supported)
- [x] this is a complete item
- [ ] this is an incomplete item
## Tables
Colons can be used to align columns.
```
| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |
```
| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |

There must be at least 3 dashes separating each header cell.
The outer pipes (|) are optional, and you don't need to make the 
raw Markdown line up prettily. You can also use inline Markdown.

```
Markdown | Less | Pretty
--- | --- | ---
*Still* | `renders` | **nicely**
1 | 2 | 3
```
Markdown | Less | Pretty
--- | --- | ---
*Still* | `renders` | **nicely**
1 | 2 | 3

## Block Quotes
If you have long strings that you would like to have wrapped, start the sentence with the > symbol
```
> This is a really long sentence that I want to make sure goes far enough to where you have to scroll, but the markdown example should be formatted properly!
```
> This is a really long sentence that I want to make sure goes far enough to where you have to scroll, but the markdown example should be formatted properly!

## References
If you want to add references, box the word you would like to reference with a boxed number next to it. Provide a link to the boxed number.
```
**The quick brown [fox][1], jumped over the lazy [dog][2].**

[1]: https://en.wikipedia.org/wiki/Fox "Wikipedia: Fox"
[2]: https://en.wikipedia.org/wiki/Dog "Wikipedia: Dog"
```
**The quick brown [fox][1], jumped over the lazy [dog][2].**

[1]: https://en.wikipedia.org/wiki/Fox "Wikipedia: Fox"
[2]: https://en.wikipedia.org/wiki/Dog "Wikipedia: Dog"

## Footnotes
By adding a ^ in the box, you can have footnotes
```
The quick brown fox[^1] jumped over the lazy dog[^2].

[^1]: Foxes are red
[^2]: Dogs are usually not red
```
The quick brown fox[^1] jumped over the lazy dog[^2].

[^1]: Foxes are red
[^2]: Dogs are usually not red
## Images, Gif, Video
If you want to add an image, gif, or video use the following:
```
![Alt Text](url) for photos and gifs
[![Alt Text](url to thumbnail)](video url) for videos
```
![Alt Text](https://www.bu.edu/files/2024/08/Hey-BU-Blog-Headers.jpg)
![Alt Text](https://media3.giphy.com/media/v1.Y2lkPTc5MGI3NjExOW83MnZodXNmZWc1MHJxampsNG5jcjRmYjJmdms2YXpiaHNyMWpmdCZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/UO5elnTqo4vSg/giphy.gif)
[![Alt Text](https://thumbs.dreamstime.com/z/r-214795421.jpg?w=768)](https://www.youtube.com/watch?v=dQw4w9WgXcQ)
