# node-hello-world

1. Make a directory to keep your application your working directory.

2. Create a package.json file for your application using the npm init 

3. Install Express in the myapp directory and add it to the list of dependencies.

4. In your index.js copy and paste the following code: 

const express = require('express')
const app = express()
const port = 3000

app.get('/', (req, res) => {
  res.send('Hello World!')
})

app.listen(port, () => {
  console.log(`Example app listening on port ${port}`)
})

5. Run the app using **node app.js**

Loaded browser output = **http://localhost:3000/**