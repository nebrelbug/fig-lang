# fig-lang

This is a hobby language that I'm working on in my spare time.

## Goals:
- Compiler built with LLVM
- Compiler to JavaScript (with libraries for VDOM, etc.)and similar to Elm
- Beautiful and simple syntax

## Random Stuff

```
let x = 'a'
let x:i32 = 300
fn do_stuff ( stuff ) {
	// This is a comment
	/*
	Multi
	line
	comment
	*/
	return "HI"
}

fn return_num:i32 (num) {
	// Uses tabs for indents
	return 32
}

fn return_num:{i32, str} (num) {
	// Uses tabs for indents
	return {32, "HI"}
}

let char = 'a' // Single quotes means character, like Rust
let x = 100 // Block scoping, like 'let' in JS

class something {
	constructor () {
	}
}

fn fn_with_lots_of_params  (
	stuff#i32,
	otherstuff
) {

}
```

- Use Rust's module system
- `mod english`
- `import crate 

Use # for comments? Or for types?

Use & for mutable
https://guide.elm-lang.org/types/type_aliases.html

Use & to shallow copy
Type annotations?

