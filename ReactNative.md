To use env variables install react-native-dotenv using `npm i react-native-dotenv` tutorial https://levelup.gitconnected.com/using-environment-variables-in-a-react-native-app-f2dd005d2457

Folder Structure 

![image](https://user-images.githubusercontent.com/2725300/191238628-836ff36d-0a82-4883-aac7-83b195880053.png)


To get rid of eslint error `delete cr`

Add 
`'endOfLine':'auto'`

To `.prettierrc.js`

So that it looks like this 

![image](https://user-images.githubusercontent.com/2725300/191238197-85cce819-b30f-4df1-a185-51abb5239e07.png)

Set up prettier and ESline https://github.com/vasilestefirta/react-native-eslint-prettier-example

Redux https://redux.js.org/introduction/installation

https://www.digitalocean.com/community/tutorials/react-react-native-redux

For this error when using react-native-reanimated

Export namespace should be first transformed by `@babel/plugin-proposal-export-namespace-from`

SOLUTION 
add to `babel.config.js`
plugins: [
    'react-native-reanimated/plugin', // This line.
  ],
![image](https://user-images.githubusercontent.com/2725300/194061593-c0cc3c5d-5b4f-416b-b15c-ba5467e8a51f.png)

Folder structure https://medium.com/the-andela-way/how-to-structure-a-react-native-app-for-scale-a29194cd33fc

Adding redux to expo app https://negativeepsilon.com/en/posts/expo-react-redux/

Expo app add permissions in app.js https://gist.github.com/warlock/5db76a64d56d4254c280344e40b77337

Good tutorial of import / export / aliases https://medium.com/@akshit5230/imports-exports-react-native-with-typescript-59e6460b0baa
