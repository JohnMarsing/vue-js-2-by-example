
# Comparisons

## React
- [see](https://vuejs.org/v2/guide/comparison.html#React)
- high level [cheat sheet](https://vuejs-tips.github.io/cheatsheet/)
- detailed [cheat sheet](https://flaviocopes.com/vue-cheat-sheet/)

### React and Vue share many similarities. They both:
- utilize a virtual DOM
- provide reactive and composable view components
- maintain focus in the core library, with concerns such as routing and global state management handled by companion libraries

#### More
- React outshines Vue, for example in the richness of their ecosystem and abundance of their custom renderers.

### HTML & CSS JavaScript/JSX vs Templates
- In React, everything is just **JavaScript** via **JSX** to make render functions
- In Vue, we also have [render functions](https://vuejs.org/v2/guide/render-function.html) and even [support JSX](https://vuejs.org/v2/guide/render-function.html#JSX), because sometimes you do need that power. However, as the default experience we offer templates as a simpler alternative. Any valid HTML is also a valid Vue template, and this leads to a few advantages of its own:
- HTML-based templates make it much easier to progressively migrate existing applications to take advantage of Vue’s reactivity features and easier for less experienced developers.
-  pre-processors such as **Pug** (formerly known as **Jade**) ???
- On a higher level, we can divide components into two categories: **presentational** ones (more common) and **logical** ones. We recommend using templates for presentational components and render function / JSX for logical ones. 

#### Component-Scoped CSS
- This (React way of scoping CSS) introduces a new component-oriented styling paradigm that is different from the normal CSS authoring process.
- The main difference between React and Vue here is that the default method of styling in Vue is through more familiar `style` tags in [single-file components)[https://vuejs.org/v2/guide/single-file-components.html].

# Scale
- > These state management patterns and [even Redux](https://yarnpkg.com/en/packages?q=redux%20vue&p=1) itself can be easily integrated into Vue applications. In fact, Vue has even taken this model a step further with [Vuex](https://github.com/vuejs/vuex), an Elm-inspired state management solution that integrates deeply into Vue that we think offers a superior development experience.


# Other
## Elm Architecture
- projects like Redux have been inspired by The Elm Architecture [see](https://guide.elm-lang.org/architecture/)

### Basic Pattern
#### The logic of every Elm program will break up into three cleanly separated parts:
- **Model** — the state of your application
- **Update** — a way to update your state
- **View** — a way to view your state as HTML

## Elm 
- Source Redux.js.org [see](https://redux.js.org/introduction/priorart) or maybe [see](https://dennisreimann.de/articles/elm-architecture-overview.html)

> [Elm](http://elm-lang.org/) is a functional programming language inspired by **Haskell** and created by [Evan Czaplicki](https://twitter.com/czaplic). It enforces a [**model view update” architecture**](https://github.com/evancz/elm-architecture-tutorial/), where the update has the following signature: `(action, state) => state`. Elm _updaters_ serve the same purpose as **reducers** in **Redux**.

> Unlike Redux, Elm is a language, so it is able to benefit from many things like enforced purity, static typing, out of the box immutability, and pattern matching (using the `case` expression). Even if you don't plan to use Elm, you should read about the Elm architecture, and play with it. There is an interesting [JavaScript library playground implementing similar ideas](https://github.com/paldepind/noname-functional-frontend-framework). We should look there for inspiration on Redux! One way that we can get closer to the static typing of Elm is by [using a gradual typing solution like Flow](https://github.com/reduxjs/redux/issues/290).


# Questions for Wells Fargo Job
- what are using Vue with, ASP.Net MVC? SPA?
- what tools are you using
- Bootstrap, TypeScript, Libman, 
- how about unit tests
- what IDE to you use, VS Code?  see [Vue tooling for VS Code](https://marketplace.visualstudio.com/items?itemName=octref.vetur) 5.7 + million downloads
- cross cutting concerns: state management, routing

