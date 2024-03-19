# Theory Assignment:
● - What is `NPM`?  
● - What is `Parcel/Webpack`? Why do we need it?
● - What is `.parcel-cache` ? The .cache folder (or .parcel-cache in parcel v2) stores information about your project when parcel builds it, so that when it rebuilds, it doesn't have to re-parse and re-analyze everything from scratch. It's a key reason why parcel can be so fast in development mode. I think committing it to git would be a bad idea - it would add a large number of (unnecessary) changes to your commit history, and it could easily get out-of-sync with the code that generated it.
● - What is `npx` ? https://www.warp.dev/terminus/npx-vs-npm#:~:text=Executing%20a%20package%20using%20npx,app%20in%20the%20current%20directory.&text=With%20this%20approach%2C%20no%20global,of%20the%20package%20is%20installed.https://www.warp.dev/terminus/npx-vs-npm#:~:text=Executing%20a%20package%20using%20npx,app%20in%20the%20current%20directory.&text=With%20this%20approach%2C%20no%20global,of%20the%20package%20is%20installed.
● - What is difference between `dependencies` vs `devDependencies` ? A dependency is a library that a project needs to function effectively. DevDependencies are the packages a developer needs during development
● - What is Tree Shaking? Algorithm used by bundlers to remove deadcode. for example if something is exported and never used or if somethings is imported but never used.
● - What is Hot Module Replacement? Hot Module Replacement (or HMR) is one of the most useful features offered by webpack. It allows all kinds of modules to be updated at runtime without the need for a full refresh.
● - List down your favourite 5 superpowers of Parcel and describe any 3 of them in your
own words.
● - What is `.gitignore`? What should we add and not add into it?
● - What is the difference between `package.json` and `package-lock.json`
● - Why should I not modify `package-lock.json`?
● - What is `node_modules` ? Is it a good idea to push that on git? No
● - What is the `dist` folder? Contains builds be it development or production. Both have different commands though.
● - What is `browserlists` ? It is a package used by parcel to make sure that our application is compaitible with most of the browsers. We have to mention it in the package.json file of the project. The value of the 'browser-list' key is a string which decides how many browsers will be compaitible.
Read about dif bundlers: vite, webpack, parcel
● Read about: ^ - caret and ~ - tilda
~version: “Approximately equivalent to version”, will update you to all future patch versions, without incrementing the minor version. ~1.2.3 will use releases from 1.2.3 to <1.3.0.

^version: “Compatible with version”, will update you to all future minor/patch versions, without incrementing the major version. ^1.2.3 will use releases from 1.2.3 to <2.0.0.
● Read about Script types in html (MDN Docs) : https://developer.mozilla.org/en-US/docs/Web/HTML/Element/script/type
