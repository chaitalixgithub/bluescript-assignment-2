# :superhero: React Marvel

<div align="left">

<a href="https://reactjs.org" target="_blank">
<img src="https://img.shields.io/badge/React-17.0.2-61DAFB?style=for-the-badge&logo=React">
</a>

<a href="https://reactrouter.com/" target="_blank">
<img src="https://img.shields.io/badge/React%20Router-6.3.0-CA4245?style=for-the-badge&logo=React%20Router">
</a>

<a href="https://styled-components.com/" target="_blank">
<img src="https://img.shields.io/badge/Styled%20Components-5.3.3-DB7093?style=for-the-badge&logo=styled-components">
</a>

<a href="https://www.npmjs.com/package/react-helmet" target="_blank">
<img src="https://img.shields.io/badge/React%20Helmet-6.1.0-D36E70?style=for-the-badge">
</a>

<a href="https://www.npmjs.com/package/react-palette" target="_blank">
<img src="https://img.shields.io/badge/React%20Palette-1.0.2-77D6A1?style=for-the-badge">
</a>

<a href="https://www.npmjs.com/package/react-scroll" target="_blank">
<img src="https://img.shields.io/badge/React%20Scroll-1.8.7-C2EF8A?style=for-the-badge">
</a>

<a href="https://www.npmjs.com/package/prop-types">
<img src="https://img.shields.io/badge/Prop%20Types-15.8.1-A32DED?style=for-the-badge">
</a>

<a href="https://prettier.io/" target="_blank">
<img src="https://img.shields.io/badge/Prettier-2.6.2-F7B93E?style=for-the-badge&logo=Prettier">
</a>

<a href="https://webpack.js.org/" target="_blank">
<img src="https://img.shields.io/badge/Webpack-5.73.0-8DD6F9?style=for-the-badge&logo=Webpack">
</a>

</div>

<p>

![GitHub repo size](https://img.shields.io/github/repo-size/mudaston/React-Marvel?style=for-the-badge)
![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/mudaston/React-Marvel?style=for-the-badge)

</p>

This app interacts with the [Marvel Developer Portal](https://developer.marvel.com/) API to get characters, comics and information about them.

<br/>

## Demo

[https://mudaston.github.io/React-Marvel](https://mudaston.github.io/React-Marvel/)

<br/>

## Screenshots

</p>

<p align="center">
<img src="https://user-images.githubusercontent.com/64277973/179247956-e9cdb731-3bc0-43e2-bd0c-c52b7388babd.png"
     width="800"
/>
</p>

<p align="center">
<img src="https://user-images.githubusercontent.com/64277973/179245046-0ea6c28a-90ff-4a87-b460-654019c0791c.png"
     width="800"
/>
</p>

<p align="center">
<img src="https://user-images.githubusercontent.com/64277973/179279024-60eb8b3d-eb70-4617-b912-aacd0207f472.png"
     width="800"
/>
</p>

<p align="center">
<img src="https://user-images.githubusercontent.com/64277973/179279037-edc24bed-f283-4c24-b7a8-bd54d576a13f.png"
     width="800"
/>
</p>

## System Requirements

- [git](https://git-scm.com/)
- [NodeJS](https://nodejs.org/en/)

<br/>

## Run Locally

Clone the project

```bash
  git clone https://github.com/mudaston/React-Marvel.git
```

Go to the project directory

```bash
  cd React-Marvel
```

Install dependencies

```bash
  npm install
```

Start the server

```bash
  npm run start
```

Open in a browser

```bash
  http://localhost:3000
```

<br/>

## Lessons Learned

In this project, I learned how to work with an API (in this case is the [Marvel API](https://developer.marvel.com/)), do pagination and change page metadata.

<br/>

## Additional

Sometimes the app can get the same data from the api request on the comics page, i don't know why this happens, but i checked it multiple times and really can't realize the problem. Method is the same as on the characters page and even the context is the same, so i think - it's API's problem.
