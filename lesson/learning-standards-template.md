### Learning Standards

Check out the [content standards](https://curriculum-documentation.codecademy.com/codecademy-basics/outcomes-standards-objectives/#learning-standards) for guidance on writing learning standards.

Important points from the content standards:
* Learning Standards focus on the goals for understanding, or the what of learning. 
* They are un-opinionated about the how of learning.
* Learning Standards include objective statements about desired understanding, knowledge, and/or skills.

Learning standards can be written before completing lesson outline for individual exercises. It can also be derived from exercise outlines after they have been written out. Learning standards state facts that are covered in this lesson. They are also used for quiz assessments. Each quiz assessment is related to a particular learning standard (in Author, you will have to directly link a quiz assessment to a learning standard).

Examples of Learning Standards:
* Browsers parse HTML tags inside the <body> and render them to a webpage as DOM Elements.
* The CSS display: flex property/value pairing sets an HTML element as a flex container. Any child elements within this flex container are known as flex items and will change size and location in response to the size and position of this parent container. The flex container will be a block level element.
* Inside an **.html** file, include A-Frame in the `<head>` element:
```html
<script src="https://aframe.io/releases/0.9.2/aframe.min.js"></script>
```

## Template: Learning Standard X

### Learning Standard Text

...

### Tags

...

### Additional Notes / Resources Used

...

<hr>

## Example: Installing Redux

### Learning Standard Text

The `redux` package is added to a project by first installing it with `npm`...
```
npm install redux
```

...and then importing it into the desired file:
```js
import { createStore } from 'redux'; 
```

### Tags

JavaScript, Redux

### Additional Notes / Examples / Resources Used

The Redux API surface is tiny. Redux defines a set of contracts for you to implement (such as reducers) and provides a few helper functions to tie these contracts together. The following top-level exports are available:
- createStore(reducer, [preloadedState], [enhancer])
- combineReducers(reducers)
- applyMiddleware(...middlewares)
- bindActionCreators(actionCreators, dispatch)
- compose(...functions)

This learning standard:
* does not cover reducer functions or store methods
* does not explain how to use `createStore`

Sources:
* https://redux.js.org/api/api-reference