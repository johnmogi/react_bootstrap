ES7 React/Redux/GraphQL/React-Native snippets

1. root folder (cra will handle the inner folder)
2. npx create-react-app client --template typescript
3. fix folders
4. components layout - rfc<br>
  (index.tsx)<br>
  import React from "react";<br>
  import ReactDOM from "react-dom";<br>
  import "./index.css";<br>
  import Layout from "./components/layout/layout";<br>
  ReactDOM.render(

  <layout>, document.getElementById("root"));<br>
  (components/layout.tsx)<br>
  import React from "react";<br>
  class Layout extends React.Component<props, state=""> {<br>
  constructor(props: Props) {<br>
  super(props);<br>
  this.state = { arr: [] };<br>
  }<br>
  render() {<br>
  return &lt;&gt;hi&lt;/&gt;;<br>
  }<br>
  }<br>
  export default Layout;<br></props,></layout>

npm install react-bootstrap bootstrap<br>
(index.tsx)<br>
import "bootstrap/dist/css/bootstrap.min.css";<br>
the individual imports such as:<br>
import Container from "react-bootstrap/Container";<br>

npm i react-router-dom @types/react-router-dom
