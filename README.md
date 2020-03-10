# React Not Typist

React component for cycling through different strings. A lot of similar
components will cycle through with a typing animation. This component offers a
different style.

## Demo

<img src="demo/demo.gif" alt="The component in action" height=100 />

Also on [codepen](https://codepen.io/chrismilson/pen/gObQJZV).

## Installation

```bash
npm install react-not-typist --save
```

## Usage

```jsx
import NotTypist from 'react-not-typist';

function Reaction (props) {
  return (
    <p>
      That was <NotTypist 
        words={[
          'exciting',
          'interesting',
          'frightening'
        ]}
      />.
    </p>
  )
}
```