# JAVAScript String methods Class

# JavaScript String Length

The `length` property returns the length of a string:

```html
let text = "ABCDEFGHIJKLMNOPQRSTUVWXYZ";
let length = text.length;
```

# JavaScript String slice()

`slice()` extracts a part of a string and returns the extracted part in a new string.

The method takes 2 parameters: start position, and end position (end not included).

```html
let text = "Apple, Banana, Kiwi";
let part = text.slice(7, 13);
```

# JavaScript String substring()

`substring()` is similar to `slice()`.

The difference is that start and end values less than 0 are treated as 0 in `substring()`.

```html
let str = "Apple, Banana, Kiwi";
let part = str.substring(7, 13);
```

# Replacing String Content

The `replace()` method replaces a specified value with another value in a string:

```html
let text = "Please visit Microsoft!";
let newText = text.replace("Microsoft", "W3Schools");
```

# JavaScript String concat()

`concat()` joins two or more strings:

```html
let text1 = "Hello";
let text2 = "World";
let text3 = text1.concat(" ", text2);
```

# JavaScript String trimStart()

[ECMAScript 2019](https://www.w3schools.com/js/js_2019.asp) added the String method `trimStart()` to JavaScript.

The `trimStart()` method works like `trim()`, but removes whitespace only from the start of a string.

```html
let text1 = "     Hello World!     ";
let text2 = text1.trimStart();
```

# JavaScript String padStart()

The `padStart()` method pads a string from the start.

It pads a string with another string (multiple times) until it reaches a given length.

```html
let text = "5";
let padded = text.padStart(4,"0");
```

# JavaScript String charCodeAt()

The `charCodeAt()` method returns the unicode of the character at a specified index in a string:

The method returns a UTF-16 code (an integer between 0 and 65535).

```html
let text = "HELLO WORLD";
let char = text.charCodeAt(0);
```

# JavaScript String split()

A string can be converted to an array with the `split()` method:

```html
text.split(",")    // Split on commas
text.split(" ")    // Split on spaces
text.split("|")    // Split on pipe
```

# Property Access

ECMAScript 5 (2009) allows property access [ ] on strings:

```html
let text = "HELLO WORLD";
let char = text[0];
```

# JavaScript String ReplaceAll()

In 2021, JavaScript introduced the string method `replaceAll()`:

```html
text = text.replaceAll("Cats","Dogs");
text = text.replaceAll("cats","dogs");
```

# JavaScript String trim()

The `trim()` method removes whitespace from both sides of a string:

```html
let text1 = "      Hello World!      ";
let text2 = text1.trim();
```

# JavaScript String trimEnd()

[ECMAScript 2019](https://www.w3schools.com/js/js_2019.asp) added the string method `trimEnd()` to JavaScript.

The `trimEnd()` method works like `trim()`, but removes whitespace only from the end of a string.

```html
let text1 = "     Hello World!     ";
let text2 = text1.trimEnd();
```

# JavaScript String padEnd()

The `padEnd()` method pads a string from the end.

It pads a string with another string (multiple times) until it reaches a given length.

```html
let text = "5";
let padded = text.padEnd(4,"0");
let text = "5";
let padded = text.padEnd(4,"x");
```

# JavaScript String charAt()

The `charAt()` method returns the character at a specified index (position) in a string:

```html
let text = "HELLO WORLD";
let char = text.charAt(0);
```