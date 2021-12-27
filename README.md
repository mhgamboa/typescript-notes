# Typescript Notes

Learning with [Traversy Media](https://www.youtube.com/watch?v=BCg4U1FzODs).

## Basic Information

- Typescript is a superset of Javascript. It uses **static typing**, meaning variable types are known before compile time.
  - Javascript uses **dynamic typing**.
- Uses `.ts` and `.tsx` extensions
- **Typescript must be compiled into Javascript**with the typescript compiler (TSC)!!
- **tsconfig.js** file is used to help configure how you want your typescript to work, what you want TS to report, where you want your files to compile to, etc.

## Types

Javascript (JS) vs Typescript (TS):

- `let id = 5` vs `let id: number = 5` (although typescript will infer the type if I don't explicitly state it).
  - setting `id = "6"` will give an error in TS, but not in JS

## Compiling

- `tsc index` compiles index
- `"watch": "tsc --watch index"` will watch your file and report errors

## tsconfig.json

- run `tsc --init`
