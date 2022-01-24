# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)

### Snippets

### Snippet Renders

imr Import React
imrc Import React / Component
imrd Import ReactDOM
imrs Import React / useState
imrse Import React / useState useEffect
impt Import PropTypes
impc Import React / PureComponent
cc Class Component
ccc Class Component With Constructor
cpc Class Pure Component
fc Function Component
cdm componentDidMount
uef useEffect Hook
cwm componentWillMount
cwrp componentWillReceiveProps
gds getDerivedStateFromProps
scu shouldComponentUpdate
cwu componentWillUpdate
cdu componentDidUpdate
cwu componentWillUpdate
cdc componentDidCatch
gsbu getSnapshotBeforeUpdate
ss setState
ssf Functional setState
usf Declare a new state variable using State Hook
ren render
rprop Render Prop
hoc Higher Order Component
Full Expansions
imr - Import React
import \* as React from 'react';

imrc - Import React, Component
import \* as React from 'react';
import { Component } from 'react';

imrd - Import ReactDOM
import ReactDOM from 'react-dom';

imrs - Import React, useState
import \* as React from 'react';
import { useState } from 'react';

imrse - Import React, useState, useEffect
import \* as React from 'react';
import { useState, useEffect } from 'react';

impt - Import PropTypes
import PropTypes from 'prop-types';

impc - Import PureComponent
import \* as React from 'react';
import { PureComponent } from 'react';

cc - Class Component
class | extends React.Component {
render() {
return <div>|</div>
}
}

export default |;

ccc - Class Component With Constructor
class | extends Component {
constructor(props) {
super(props);
this.state = { | };
}
render() {
return ( | );
}
}

export default |;

cpc - Class Pure Component
class | extends PureComponent {
state = { | },
render() {
return ( | );
}
}

export default |;

fc - Function Component
const | = props => {
return ( | );
};

export default |;

cdm - componentDidMount
componentDidMount() {
|
}

uef - useEffect Hook
useEffect(() => {
|
}, []);

cwm - componentWillMount
//WARNING! To be deprecated in React v17. Use componentDidMount instead.
componentWillMount() {
|
}

cwrp - componentWillReceiveProps
//WARNING! To be deprecated in React v17. Use new lifecycle static getDerivedStateFromProps instead.
componentWillReceiveProps(nextProps) {
|
}

gds - getDerivedStateFromProps
static getDerivedStateFromProps(nextProps, prevState) {
|
}

scu - shouldComponentUpdate
shouldComponentUpdate(nextProps, nextState) {
|
}

cwu - componentWillUpdate
//WARNING! To be deprecated in React v17. Use componentDidUpdate instead.
componentWillUpdate(nextProps, nextState) {
|
}

cdu - componentDidUpdate
componentDidUpdate(prevProps, prevState) {
|
}

cwun - componentWillUnmount
componentWillUnmount() {
|
}

cdc - componentDidCatch
componentDidCatch(error, info) {
|
}

gsbu - getSnapshotBeforeUpdate
getSnapshotBeforeUpdate(prevProps, prevState) {
|
}

ss - setState
this.setState({ | : | });

ssf - Functional setState
this.setState(prevState => {
return { | : prevState.| }
});

usf - Declare a new state variable using State Hook
const [|, set|] = useState();

Hit Tab to apply CamelCase to function. e.g. [count, setCount]

ren - render
render() {
return (
|
);
}

rprop - Render Prop
class | extends Component {
state = { | },
render() {
return this.props.render({
|: this.state.|
});
}
}

export default |;

hoc - Higher Order Component
function | (|) {
return class extends Component {
constructor(props) {
super(props);
}

    render() {
      return < | {...this.props} />;
    }

};
}

cpf - Class Property Function
| = (e) => {
|
}
