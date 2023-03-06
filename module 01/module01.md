# Get started with TypeScript

## About TypeScript

TypeScript is a superset of JavaScript where you can identify the type of variable or parameter by using a **type hint**.

Types are optional if the data type is implicit, like in `let driversNumber = 3`.

## About compilers/transpilers

All JavaScript code is TypeScript code, but TypeScript code needs to be compiled (using `tsc` or `tsc nameOfTheFile.ts`) into JavaScript for the browser to understand it.

### Compilers vs Transpilers

| Compiler | Transpiler |
|---|---|
|Converts high-level language to low-level. | Converts high-level language to another high-level language. |
| The machine can execute it. | The machine can't execute it, it needs to be compiled. |
| The output is harder to comprehend. | The output is similar as the input, so it's easier to understand. |

## How to quickly initiate a TypeScript project

- Enter `tsc --init` on the terminal.
- Set the `outdir` paramater to `./build`.
- Enter `tsc` to reset the options for the project.

Go to [next module >](../module%2002/module02.md)
