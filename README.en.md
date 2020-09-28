<p align="right">
  <a href="README.en.md">🇺🇸</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="README.md">🇧🇷</a>&nbsp;&nbsp;&nbsp;
</p>

<img alt="GoStack" src=./src/assets/header-bootcamp.png />

<h3 align="center">
  Challenge 03: ReactJS Concepts
</h3>

<p align="center">
  <a href="#rocket-about-the-application">About the application</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#cd-installed-packages">Installed packages</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#memo-licence">Licence</a>
</p>

## :rocket: About the application

A simple application in React Native!

This is an application to store repositories in your portfolio, which will allow you to create, list and give a like to projects.

### Application Template

The template is available in the following URL: **[Access Template](https://github.com/Rocketseat/gostack-template-conceitos-react-native)**

**Tip**: In case you don't know how to use Github repositories as templates, we have a guide in **[Rocketseat FAQ](https://github.com/Rocketseat/bootcamp-gostack-desafios/tree/master/faq-desafios).**

Navigate to the created folder and open it in the Visual Studio Code, remember to execute the command `yarn` in your terminal in order to install all the dependencies.

**Attention:** It is not necessary to install any dependencies (like the webpack). The template is already functional, and it is only necessary to run the command `yarn start` and code.

### Application Routes

In the src/App.js file:

- **`List the repositories of your API`**: You should be able to create a list with the **title** field of all repositories that are registered in your API.

- **`Add a repository to your API`**: You should be able to add a new item to your API via a button with the text **Adicionar**<sup>*</sup> and, after creation, you should be able to display its name after registration.

- **`Remove a repository from your API`**: For each item on your list, you must have a button with the text **Remover**<sup>**</sup> that, when clicking, will call a function to remove that item from the list of your frontend and its API.

<sup>*</sup> Adicionar (pt-br) = Add (eng)

<sup>**</sup> Remover (pt-br) = Remove (eng)

### Tests Specification

In each test, you have a brief description of what your application must do in order for the test suits pass.

If you have questions about what the tests are, and how to interpret them, take a look at **[Rocketseat FAQ](https://github.com/Rocketseat/bootcamp-gostack-desafios/tree/master/faq-challenges).**

For this challenge we have the following tests:

- **`should be able to add new repository`**: For this test to pass, your application must allow a repository to be added to your backend and listed on your frontend within a `LI`.

- **`should be able to remove repository`**: In order for this test to pass, your application must allow that by clicking on the remove button that will be inside the `LI` of the added repository, the item will be removed from the list.

## :cd: Installed packages

The following is a list of installed packages:

- [react react-test-renderer](https://reactjs.org/)
- [react-native](https://github.com/facebook/react-native#readme)
- [axios](https://github.com/axios/axios)
- [@babel/core @babel/runtime](https://babeljs.io/)
- [jest babel-jest](https://github.com/facebook/jest#readme)
- [metro-react-native-babel-preset](https://github.com/facebook/metro#readme)

  Optional
- [eslint](https://eslint.org/)
- [@react-native-community/eslint-config](https://github.com/facebook/react-native/tree/master/packages/eslint-config-react-native-community#readme)

## :memo: Licence

This project is under license from MIT. See the archive [LICENSE](LICENSE) to more details.
