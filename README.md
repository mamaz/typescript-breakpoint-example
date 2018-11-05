# Add Breakpoint To Your Typescript

This example will show you how to activating breakpoint in `.ts` file.

Adding breakpoint is crucial for debugging your app.

## Basics

You need to add and configure `launch.json` and `tasks.json`.

`launch.json` needs to be set so that debugger can read the source maps. It needs to have `sourceMaps` field to be set to `true`.

`tasks.json` needs to be set to run `tsc` before the debugging is running.

## How to Run The Example

1. Clone this repo.

2. Install typescript: `npm install -g typescript`.

3. Go to Debug section on the VSCode (Shift+Cmd D).

4. Add breakpoint in `src/index.ts`.

5. Run the `Debug Typescript in Node.js` config.

6. See breakpoint in action.

## Reference

Kudos to [jyuhuan](https://github.com/jyuhuan/node-ts) for the nice example.

## License

MIT License.
