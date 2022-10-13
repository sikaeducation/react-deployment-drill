# React Deployment Drill

1. Build an app with Create React App.
2. Run the app and see its defaults render in the browser.
3. Download a picture of a dog and put it in the `public` folder
4. Replace the contents of `App.js` with the following:

```jsx
import "./App.css"

const App = () => {
  return (
    <div className="App">
      <h1>React Rocks!</h1>
      <img src="name-of-dog-file-goes-here.jpg" />
    </div>
  )
}

export default App
```

5. See the app update in the browser
6. Build the app.
7. Deploy the app to a static hosting provider like Surge.
8. Change the content of the `<h1>`.
9. Rebuild the app.
10. Redeploy the app.
