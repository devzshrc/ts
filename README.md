TS
What's extra in typescript ?
~ Types
Recognize bug early
JS is costly freedom - no strictness
JS has loose doc generation

developer tooling - less for JS

TS - is an addon to JS
   - TS nevers runs
   - TS requires a process which outputs   a JS
   - Type checker - consistency
Gives a smooth dev-experience

can install globally and projectwise

  "rootDir": "./src",
   "outDir": "./dist", -> distributble
 tsc -p .    -> will run and create dist
 to run : node dist/index.js
 we dont push dist to github
 .gitignore setup - node_modules, .env, dist/
 pnpx gitignore node
change something - no hotreload, no latest code compilation - painful - soln: watcher...
pnpm add tsc-watch -D
