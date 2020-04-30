import React from 'react'
import ReactDOM from 'react-dom'

import "./index.css"

class Parent extends React.Component {
  constructor(props){
  super(props)
  this.state={
    name:this.props.name,
    count:this.props.count
  }
  // this.clickMe=this.clickMe.bind(this)
}
 clickMe =()=> {
   console.log('clicked');
  // let count=this.state.count
  this.setState({count:this.state.count+1})
}
  render(){
  return(
    <div>
      <h1 className="title">Name: {this.state.name}</h1>
      <h1>Count: {this.state.count}</h1>
      <button onClick= {this.clickMe} >button</button>
    </div>
    )
}
}
Parent.defaultProps={
  name:"Mollay"
}

ReactDOM.render(
<div>
  <Parent name="Ashish" count={0}/>
  </div>,
  document.getElementById('root')
);



// import React from 'react';
// import ReactDOM from 'react-dom';
// import './index.css';
// import App from './App';
// import * as serviceWorker from './serviceWorker';

// ReactDOM.render(
//   <React.StrictMode>
//     <App />
//   </React.StrictMode>,
//   document.getElementById('root')
// );

// // If you want your app to work offline and load faster, you can change
// // unregister() to register() below. Note this comes with some pitfalls.
// // Learn more about service workers: https://bit.ly/CRA-PWA
// serviceWorker.unregister();
