# Reproduction Case for SWC/VSCode Debug Issue

1. Open up a JavaScript debug terminal
2. Place a breakpoint in `index.ts`
3. Run `yarn start` from the JS debug terminal

Expected: Breakpoint is hit in original `index.ts`
Actual: Breakpoint is hit in transpiled code
