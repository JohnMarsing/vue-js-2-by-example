
# Lesson 1
## Installing Vue with the Vue CLI
- [source](https://coursetro.com/posts/code/133/How-to-Install-Vue-2---Through-CDN,-NPM-and-the-Vue-CLI) Used by the tutorial.
- `npm -v` find what version your using
- Update NPM on Windows [github](https://stackoverflow.com/questions/18412129/how-can-i-update-npm-on-windows)
- `npm install -g @vue/cli`
- ` vue create vue-skills`
`PS D:\Github\vue-js-2-by-example> vue create vue-skills
> You are using Node v4.6.0, but this version of vue-cli > requires Node >=8.9.
> Please upgrade your Node version.

## Launch and run the server with NPM
- `npm run serve`

### App running at:
- Local: `http://localhost:8080/`
- network: unavailable

## Vue CLI
- [install Vue through NPM](https://coursetro.com/posts/code/133/How-to-Install-Vue-2---Through-CDN,-NPM-and-the-Vue-CLI) 
- NPM=Node Package Manager; Not used in the tutorial

# Lesson 2 Startup and Over vier

## App.vue
<img src="01-App-dot-Vue.png" />

## App.vue Hello World
<img src="02-App-dot-Vue-HelloWorld_Vue-Component.png" />

### Change HelloWorld to Skills
<img src="change-HelloWorld-to-Skills.png" />

### App-vue-modifications
<img src="App-vue-modifications.png" />


### npm-run-serve_debugging-example
NOT SHOWN



# Lesson3 Templating - Interpolation and Directives
- [notes](https://coursetro.com/courses/23/Vue-Tutorial-in-2018---Learn-Vue.js-by-Example/lessons/3)
- Interprelation aka mustaches
- Text Interprelation
- JavaScript Interprelation

## Template and Script example
<img src="template-script-example.png" />

## v-for directive and som Json-data
<img src="v-for_and-Json-data.png" />

## App-vue with scoped and without scope
<img src="App-Vue-with-scoped-and-without.png" />

## Add Skills.css file reference vai style src
<img src="Adding-css-file-to-style-src.png" />

# v-bind directive
## v-bind-class
<img src="v-bind_directive.png" />

## v-bind-class multiple directives
<img src="v-bind_multiple-directives.png" />

## v-bind-class to a JSON object
<img src="v-bind_directive-to-a-JSON-object.png" />

## v-bind to a style
<img src="v-bind_directive-to-a-style.png" />

## updated styles in App.vue and Skills.vue
**ToDo**: what's special about this?
<img src="updated-styles-in-App-vue-and-Skills-Vue.png" />

## form v-model directive methods
- [see](https://vuejs.org/v2/guide/events.html)

<img src="form_v-model_methods.png" />

## form with two input fields
<img src="form_with-two-input-fields.png" />

## Appendix Vue Directives (most common)
  v-text
  v-html
  v-show
  v-if
  v-else
  v-else-if
  v-for
  v-on
  v-bind
  v-model
  v-pre
  v-cloak
  v-once

- [Class and Style Binding](https://coursetro.com/posts/code/136/Vue-CSS-Tutorial---Class-and-Style-Binding)

## Vue Class binding
uses a bind directive

## style binding

## vee-validate
- **vee-validate** Input validation for Vue.js, [see](https://baianat.github.io/vee-validate/)
- `npm install vee-validate --save`
-

### Vue Devtools extension 
-  [github](https://github.com/vuejs/vue-devtools) extension has install for **Chrome** Extension (beta), **Firefox** Addon (beta) and stadalone **Electron** app (works with any environment!)

# Validation

## install vee-validate
<img src="install-vee-validate.png" />


## vue-validate example
<img src="vee-validate-example.png" />


# Animations
- e.g. enter and leave
- Custom component wrapper `transition`
- The name of the transition e.g. alert-in will server as a prefix to some css animation classes
- transition can deal with certain type of directives e.g. `v-if`, `v-show`, _dynamic components_ and _component group nodes_
- Available transition class for Vue [see](https://vuejs.org/v2/guide/transitions.html)
   `v-enter, v-enter-active, v-enter-to, v-leave, v-leave-active, v-leave-to`
    
## 3rd Party Animation Library 
- **Animate.css** [demo](https://daneden.github.io/animate.css/)


## animations using transition-class
<img src="animations-using-transition-class.png" />

## animations using _Annimation.css_ 3rd party library
<img src="animations-using-Annimation-CSS-3rd-party-library.png" />


### Animating List
via transition group


# Routing [see](https://router.vuejs.org/installation.html)
- `npm install vue-router`
- this could have been created for me when I did the initial `vue create` command


## npm install vue-router
<img src="npm-install-vue-router.png" />

## routing changes
<img src="routing.png" />



Left off [here](https://youtu.be/78tNYZUS-ps?t=3609) in the Video


# More Samples
- [StupidTodo](https://github.com/DaneVinson/StupidTodo) by DaneVinson, example uses no NPM, [blog](https://developingdane.com/vue-js/)
- [Vue and TypeScript](https://johnpapa.net/vue-typescript/) by John Papa

### ToDo - move to another md file
- cheat-sheet.png
- 11-8-2018 9-57-57 AM