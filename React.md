# React Introductory

[React Official](https://reactjs.org/) | [React Github](https://github.com/facebook/react/)

## Why React

React is one of the modern frontend library that has grown popularity recently. Many developers has picked up this library for a multitude of reasons

1. Reusable components throughout your application

    React components is a powerful capability to take advantage of. 
    Each component are like independent pieces of code that has its own rendering logic.  
    This allows you to take advantage of abstraction, also simplifying development cycles.

2. High Performance through Virtual DOM

    A virtual representation of the UI is kept in memory through ReactDOM. By comparing previou states, it updates only the neccessary parts of the real DOM to minimise reads/writes, boosting performance compared to traditional web applications.
    [Official React Doc](https://reactjs.org/docs/faq-internals.html)  

3. Many supporting libraries available

    Due to the popularity of React, many 3rd party libraries exists to achieves certain use cases easily.  
    While some may like this flexiblity, some may prefer frameworks that provides such capabilities out of the box.

    Here are just some examples,

    |Use Cases|Available Libraries |
    |-:|:-|
    |State Management | **Redux**, Recoil, Mobx |
    |Mobile Development | React Native |
    |Components / UI | Tailwind UI, React Bootstrap, **Blueprint** |
    |Forms | React Hook Form, Formik, React Final Form,

    _Bolded libraries are used in Source Academy_

4. Growing community as React gains popularity


## What is React

As mentioned, React is a frontend JavaScript library developed **building user interfaces** .

It is `declarative-based`, where you describe the final state of the UI you desire and React is responsible for determining the necessary changes to achieve that goal. [Read More](https://ui.dev/imperative-vs-declarative-programming)

It is `unopiniated` or flexible in a sense, it leaves the build and structure of the application to you. Every react project can look different in file structure or organisation, there is **no one right way**. 
Hence, we will be discussing what Source Academy's organisation is later onwards.

## React's Project Organisation

<img src="./assets/react_app_structure.jpg" width="200px" /><br />
> _The project in this picture was freshly created for demonstration purpose with the folders in _src/_ created by me._

React does not impose on a specific folder structure, hence any projects can look different but this image shows one typical style of managing your codebase.

#### Overall
| File / Folder | Description |
| -:|:- |
| node_modules | installed packages |
| public/ | |
| src/ | Actual codebase that renders your UI |
| .gitignore | Used for Git |
| package-lock.json | Used by NPM |
| package.json | Used by NPM / Yarn |
| README.md | Guide to your codebase / application |

#### src/
| File / Folder | Description |
| -:|:- |
| assets/ | media files (etc. images, icons)|
| components/ | react components|
| pages/ | pages which users navigate between |
| styles/ | stylesheets (CSS, SCSS, ...) |
| _..others_ | |

With other use cases and libraries, more folders may/should be created for better organisation. Once again, the organisation is up to you to decide best for your development purposes.

## React Components

## React Router

## Redux