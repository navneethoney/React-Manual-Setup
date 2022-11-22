# Getting Started with React (Manual Setup)

1. Create package.json by npm init -y

2. Create node modules and package-lock.json by:
   npm install react react-dom

3. Use Babel:
   npm install @babel/core @babel/preset-env @babel/preset-react babel-loader

4. Create .babelrc file and add this code:
   {
   "presets": ["@babel/preset-react", "@babel/preset-env"]
   }

5. Install webpack:
   npm install webpack webpack-cli webpack-dev-server

6. Install HTML webpack plugin:
   npm install html-webpack-plugin

7. Create webpack.config.js file and write the code (as shown in the file)

8. Write start and build key in package.json

9. npm start
