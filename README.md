<h1 align="center"><code>bfcomp.js</code></h1>

<p align="center">Compile and convert text to brainfuck code</p>

## ⚙️ Installation

```js
npm i bfcomp
```

**CDN Links:**
- https://cdn.jsdelivr.net/npm/bfcomp@1.0.0/bfcomp.js
- https://www.unpkg.com/bfcomp@1.0.0/bfcomp.js

## 📖 Usage

#### ◎ Import

```js
// ES6
import bfcomp from "bfcomp";

// commonjs
const bfcomp = require("bfcomp");
```

#### ◎ Compile / To text

```js
const code = "++++++++[>++++[>++>+++>+++>+<<<<-]>+>+>->>+[<]<-]>>.>---.+++++++..+++.>>.<-.<.+++.------.--------.>>+.>++.";

const text = bfcomp.compile(code);
const text2 = bfcomp.toText(code);

console.log(text); // "Hello World!"
console.log(text2); // "Hello World!"
```

#### ◎ Run

```js
// code variable declared in the previous example
bfcomp.run(code);
```

This will `console.log()` the compiled BF code.

#### ◎ To code

```js
const code = bfcomp.toCode("Hello!");

console.log(code); // returns BF code
```

```js
const code = bfcomp.toCode("Hello!");

bfcomp.run(code);
```

---

[Support me on Patreon](https://www.patreon.com/axorax) - 
[Check out my socials](https://github.com/axorax/socials)