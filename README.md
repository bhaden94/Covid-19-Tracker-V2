# Covid-19-Tracker-V2
Documentation For Covid-19-Tracker-V2-FE &amp; Covid-19-Tracker-V2-API

<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->
<!-- [![Contributors][contributors-shield]][contributors-url] -->
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]



<!-- PROJECT LOGO -->
<br />
<p align="center">
  <a href="https://covid-tracker-v2.herokuapp.com/">
    <img src="https://images.newscientist.com/wp-content/uploads/2020/02/11165812/c0481846-wuhan_novel_coronavirus_illustration-spl.jpg" alt="Logo" width="150" height="100">
  </a>

  <h3 align="center">Covid Tracker V2</h3>

  <p align="center">
    Visualization dashboard to see key data related to Covid-19.
    <br />
    <a href="https://covid-tracker-v2.herokuapp.com/">View On Heroku</a>
    ·
    <a href="https://github.com/bhaden94/spacex-app/issues">Report an Issue With This Documentation</a>
  </p>
</p>



<!-- TABLE OF CONTENTS -->
## Table of Contents

* [About the Project](#about-the-project)
  * [Built With](#built-with)
* [Getting Started](#getting-started)
  * [Prerequisites](#prerequisites)
  * [Installation Without Docker](#installation-without-docker)
  * [Installation With Docker](#installation-with-docker)
* [Usage](#usage)
* [Roadmap](#roadmap)
* [Contributing](#contributing)
* [License](#license)
* [Contact](#contact)
* [Acknowledgements](#acknowledgements)



<!-- ABOUT THE PROJECT -->
## About The Project

![Desktop past view](images/screenshot1.JPG)
![Desktop next view](images/screenshot2.JPG)
![Mobile past view](images/mobile-screenshot1.JPG)
![Desktop next view](images/mobile-screenshot2.JPG)



### Built With
* [Create React App](https://create-react-app.dev/)
* [MDBootstrap](https://mdbootstrap.com/docs/react/)
* [Docker](https://www.docker.com/)
* [SpaceX-API](https://github.com/r-spacex/SpaceX-API) :rocket:



<!-- GETTING STARTED -->
## Getting Started

This app was dockerized so if you want to install and use it on your local machine follow these steps.

### Prerequisites

To run this in a Docker container you must have Docker installed on your machine. Go [here](https://www.docker.com/get-started) to get started if you don't.

### Installation Without Docker

1. Clone the repo
```sh
git clone https://github.com/bhaden94/spacex-app
```
2. Install NPM packages
```sh
npm install
```
3. Start the react app
```sh
npm start
```

### Installation With Docker

1. Make sure Docker is installed and running
2. Clone the repo
```sh
git clone https://github.com/bhaden94/spacex-app
```
3. Build Docker image
```sh
docker build -t spacex-app .
```
4. Run the container
```sh
docker run -dp 3000:80 spacex-app
```
5. Navigate to [http://localhost:3000](http://localhost:3000)



<!-- USAGE EXAMPLES -->
## Usage

This app was built to give a brief snapshot of SpaceX and their history along with upcoming and past launches.

<!-- ROADMAP -->
## Roadmap

See the [open issues](https://github.com/bhaden94/spacex-app/issues) for a list of proposed features (and known issues).


<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to be; learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request



<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE` for more information.



<!-- CONTACT -->
## Contact

Brady Haden - [LinkedIn](https://www.linkedin.com/in/brady-s-haden/)




<!-- ACKNOWLEDGEMENTS -->
## Acknowledgements
* [React Vertical Timeline](https://stephane-monnot.github.io/react-vertical-timeline/#/)
* [GitHub Emoji Cheat Sheet](https://www.webpagefx.com/tools/emoji-cheat-sheet)
* [Img Shields](https://shields.io)





<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
<!-- [contributors-shield]: https://img.shields.io/github/contributors/othneildrew/Best-README-Template.svg?style=flat-square
[contributors-url]: https://github.com/othneildrew/Best-README-Template/graphs/contributors -->
[forks-shield]: https://img.shields.io/github/forks/bhaden94/spacex-app.svg
[forks-url]: https://github.com/bhaden94/spacex-app/network/members

[stars-shield]: https://img.shields.io/github/stars/bhaden94/spacex-app.svg
[stars-url]: https://github.com/bhaden94/spacex-app/stargazers

[issues-shield]: https://img.shields.io/github/issues/bhaden94/spacex-app.svg
[issues-url]: https://github.com/bhaden94/spacex-app/issues

[license-shield]: https://img.shields.io/github/license/bhaden94/spacex-app.svg
[license-url]: https://github.com/bhaden94/spacex-app/blob/master/LICENSE.txt

[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/brady-s-haden/
[product-screenshot]: images/screenshot.png
