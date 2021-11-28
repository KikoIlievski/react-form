# Deploying the react-app using GitHub pages

To `package.json`, add the following:

```json
    "homepage":"https://<username>.github.io/<reponame>" 
     "scripts": {
      "predeploy": "npm run build",
      "deploy": "gh-pages -d build"
    }
```
Run the following commands in the directory of your project
1.  `npm install --save-devs gh-pages`  
2.  `npm run build`
3. `npm run deploy`

Now, if you visit the url `https://<username>.github.io/<reponame>`, your site should be up :)
Links I found useful if this doesn't work in the future: 
- https://www.taniarascia.com/getting-started-with-react/
- https://github.com/gitname/react-gh-pages
