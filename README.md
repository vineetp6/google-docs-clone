<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgements">Acknowledgements</a></li>
  </ol>
</details>

## About The Project



### Built With

- [React](https://reactjs.org/docs/getting-started.html)
- [Material UI](https://material-ui.com/getting-started/installation/)
- [yjs](https://yjs.dev/)

Written in TypeScript ♥

## Getting Started

Follow the instructions to set up the project on your local machine.

### Prerequisites

This is an example of how to list things you need to use the software and how to install them.

- npm

  ```sh
  npm install npm@latest -g
  ```

### Installation

1. Fork the repo(required), a star is also appretiated but optional :P

2. Clone the forked repo

   ```sh
   git clone https://github.com/{your-github-username}/caucus.git
   ```

   example : `git clone https://github.com/Rishabh-malhotraa/caucus.git`

3. Install NPM packages

   ```sh
   npm run install-modules
   ```

4. Start the react and nodejs server concucrrently

   ```sh
   npm run dev
   ```

### Setting up DATABASE

To setup the database with mockdata, follow this [guide](/Setting%20up%20Database.md)

### Execute Code

To allow cuacus to execute code, you need to get your api keys from [JDoodle](https://www.jdoodle.com/) and add them to the `.env` file
Update: I have included API keys from a dummy account, you can get your own also from JDoodle, the keys are restricited to 200 executions per day, and is visible to everyone, you can get your own private key at JDOODLE

``` text
JDOODLE_CLIENTID=get_your_key
JDOOLDE_CLIENTSECRET=get_your_key
```

## Roadmap

See the [open issues](https://github.com/Rishabh-malhotraa/caucus/issues) for a list of proposed features (and known issues).

### Things To do

- [x] Inital Login Page
- [x] Database hookup with login from oAuth
- [x] Chat Application
- [x] Video Chat Application (the main chunk of work)
- [x] Collaborative Editing (the main chunk of work)
- [x] Resizable Panes
- [x] Code Running (Easy need to just hookup with an api)
- [x] Database with all the leetcode question and sorted based on tags.
- [x] IMP: Sync code using localstorage or sockets when a new person joins in the room, with defaultvalue prop on the monaco editor instance.
- [x] Add SSL certificate to the docker container, andd get rid of the current bootleg shenanigans D: (LetsEncrypt or Cloudflare)
- [x] Add codeforce problem using webscraping thingy
- [x] Add Vim Keybinds
- [x] Add intellisense using Language Server Protocal for atleast C++ and JAVA
- [x] Make a public api to fetch questions, based on scraped data
- [ ] Add a full-screen Zen Mode
- [ ] Change Hosting from Heroku to GCP or Digital Ocean
- [ ] Change Heroku PSQL DB to either ~~MongoDB or Firebase~~ SQLITE.
- [ ] Add Autoformating keybind.
- [ ] ~~Fix the number of users in the room.~~
- [ ] ~~REACH: Add video call functionality (using WEBRTC or something propieteary like Twilo proprietary)~~
- [ ] ~~Add ability to add different tabs on the editor instance just like that on VSCODE~~
- [ ] ~~Integrate the random quote thingy on loading screen from forticodes API~~
- [ ] ~~Fix why the loader gets frozen on intial render -\_-~~

## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

Refer to this [article](https://medium.com/swlh/guide-to-git-a-practical-approach-27926a1ff564?sk=b54ca413a142c275f5d2901d0384a0db) if you have any difficulty in making a pull request

## License

Distributed under the MIT License. See [`LICENSE`][license-url] for more information.
---

## Stargazers over time

[![Stargazers over time](https://starchart.cc/rishabh-malhotraa/caucus.svg)](https://starchart.cc/rishabh-malhotraa/caucus)

---

## Acknowledgements

- [Heroku](https://www.heroku.com/)
- [Azure](https://azure.microsoft.com/en-us/)
- [notistack](https://www.npmjs.com/package/notistack/)
- [axios](https://www.npmjs.com/package/axios)
- [dog-names](https://www.npmjs.com/package/dog-names)
- [Best-README-Template](https://github.com/othneildrew/Best-README-Template)
- [MIT License](https://opensource.org/licenses/MIT)
- [SVG Backgrounds](https://www.svgbackgrounds.com/)

<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->

[all-contributors-shield]: https://img.shields.io/badge/all_contributors-8-orange.svg?style=for-the-badge
[contributors-shield]: https://img.shields.io/github/contributors/Rishabh-malhotraa/caucus.svg?style=for-the-badge
[contributors-url]: https://github.com/Rishabh-malhotraa/caucus/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/Rishabh-malhotraa/caucus.svg?style=for-the-badge
[forks-url]: https://github.com/Rishabh-malhotraa/caucus/network/members
[stars-shield]: https://img.shields.io/github/stars/Rishabh-malhotraa/caucus.svg?style=for-the-badge
[stars-url]: https://github.com/Rishabh-malhotraa/caucus/stargazers
[issues-shield]: https://img.shields.io/github/issues/Rishabh-malhotraa/caucus.svg?style=for-the-badge
[issues-url]: https://github.com/Rishabh-malhotraa/caucus/issues
[license-shield]: https://img.shields.io/github/license/Rishabh-malhotraa/caucus.svg?style=for-the-badge
[license-url]: https://github.com/Rishabh-malhotraa/caucus/blob/main/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/rishabh-malhotra-4536a418b
[product-demo]: images/caucus-demonstation.gif
[product-screenshoti]: images/code-editor.png
[product-screenshotii]: images/login-page.png
[product-screenshotiii]: images/navigation-page.png



