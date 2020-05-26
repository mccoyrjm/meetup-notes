# Byteconf React 2020 - Day 2
* [YouTube](https://www.youtube.com/channel/UC046lFvJZhiwSRWsoH8SFjg)

# Concurrent React from Scratch - Shawn Wang
https://www.github.com/pomber/didact

## JSX Element
* Plain old JS object
* Type [and Key]
* Props

```javascript
const element = {
  type: "h1",
  props: {
    children: "Hello World",
  },
}
```

# Building Scalable Web Applications with React - Saeed Ahmad
## What will we cover?
* Scalibility
* Why?
* Challenges
* Parts of a ReactJS App
* Approaches to Scale
* Best Practices

## What's Scalibility?
* The property of a system to handle a growing amount of work by adding resources to the system

## Scalibility in React
* easy to extend
* easy to collaborate on
* easy to reuse

## Dynamic Requirements
* Are the ones which can change depending on different factors

## UI
* Starter Kits
* UI Libraries
* Styling

## Interface
* React Router
* Reach Router
* React Loadable

## State Management
* React State
* Context API - Global State
* Redux/MOBX

## Business Logic & Middleware
* Action Creators
* Reducers
* Redux
* Redux Saga
* Thunk


# Adding the accessibility in your React Apps - Neha Sharma
## What is?
* 1 2 3 4 5 6 7 8 9 10 11
* A11y

## Why it matters
* Accessibility means web should be accessible for everyone irrespctive of the user's disability. Especially at today's time of #COVID19, when everyone is moving digital to access the content & information.

## WCAG
* Accessibility Levels
  * A
  * AA
  * AAA
* Types of Disability
  * Vision
  * Hear
  * Speak
  * Cognitive

## Myth 1: Accessibility only pertains to disabled people
Is it accessibile:
1. on Mobile?
2. by Speed?
3. w.r.t content?
4. UX?
5. by Keyaboard?
6. by Screen Readers?

## Myth 2: Achieveing Accessibility is hard.
1. Semantic Tags
2. Focus & Keyboard
3. Screen Readers
4. Alt Tags

## Myth 3: Accessibility is not possible with JS Frameworks
* ReactJS supports accessibility: https://reactjs.org/docs/accessibility

* Take advantage of components
  1. UX
  2. UI
  3. Responsive
  4. Accessibility

## Tips

1. Semantic JSX/HTML
    * Correct Semantic code (ex. use `<header>` for Header component)
    * Use native elements over custom elements
    * Validate JSX/HTML

2. Keyboard Support
    1. Tabindex, Outline & .focus, refs(), Order
    2. Think logical
    3. Skip to main content

3. Page Titles
Important for screen readers to inform the users on which page they are on.

4. Accessible Forms

5. Live Regions

## Tools
* [Lighthouse](https://developers.google.com/web/tools/lighthouse)
* [Axe](https://www.deque.comaxe/axe-for-web/)
* [Wave](https://wave.webaim.org)
* [Accessibility Insights](https://accessibilityinsights.io/)
* eslint-plugin-jsx-a11y
* axe-a11y


# Power Up Gatsby with Auth! - Sam Julien
About adding auth to gatsby.

## Gatsby
* Static Site Generator? Really more of a Dynamic Site Framework.
* "Blazing Fast Web & App Framework"
* Can do both static and dynamic

Authentication - Is it the same as in ReactJS?

## Build Time vs. Runtime
* Build Time
  * use server to process site that builds file to deliver to website later
  * No browser APIs available
* Runtime
  * things that happen in the browser when you run & click (ex. `window`, `document`)

### Runtime
1. Start login
2. Log in to identity provider
3. Handle redirect
    * Success - User, Token Redirect
    * Error

### Auth Utility
* Store token and user in memory
* Interact with auth SDK
* Handle all redirect logic



## Using Hooks for Auth

## Special Gatsby Bits

## Misc.
"Is auth().com a good goto place to get started getting my feet wet? Seems like there are so many auth() services/providers/solutions to pick from!"

> "Yeah, there are a few these days. :) My advice is always to sign up for the free tier of a few of them and see which one works best for you. Day job aside, I find Auth0 really really nice for working with JS." - Sam Julien


# Lifting state up is killing your app - Andrey Goncharov


# From create-react-app to create-any-app - Ema Suriano


# React Bandersnatch experiment: getting close to a real framework - Claudia Bressi


# Speeding up your Gatsby app in a day - Henrique Cavalieri
