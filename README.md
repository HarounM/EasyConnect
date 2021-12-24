

[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]



<br />
<div align="center">
  <a href="https://github.com/HarounM/EasyConnect">
        <img src="./images/logo.png"/>                                              
  </a>
</div>

<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>

## About The Project

[![Product Name Screen Shot][product-screenshot]](https://github.com/HarounM/EasyConnect)

EasyConnect is a simple TUI program built in bash. It is intended to simplify basic network services usage to the end-user. Its first release is supposed to support ssh, ftp, http and https. 
Although still unfinished, I decided to publish it as I'm really excited to demonstrate the use of ASCII escape characters.

## Getting Started

### Prerequisites

Well, this is a simple program that only needs bash to work.
For mac users, you could install bash as follows:
  ```sh
  brew install bash
  ```

### Installation

 You only need to clone the repo
   ```sh
   git clone https://github.com/HarounM/EasyConnect.git
   ```

## Usage
The program is not really usable as for now. But you could check the loading page and main menu. Simply run it with bash :
   ```sh
bash ./easyconnect
   ```

## Roadmap

- [x] Create a loading page 
- [x] Create the main menu
- [x] Correctly handle SIGTSTP
- [x] Correctly handle SIGTERM
- [ ] Correctly handle SIGWINCH 
- [ ] Create ssh page 
    - [ ] Support private key usage
- [ ] Create ftp page
- [ ] Create HTTP page
- [ ] Create HTTPS page

## Contributing
If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

Distributed under the Gnu GPLv3 License. See `LICENSE.txt` for more information.


## Contact
Email: maghharoun@gmail.com
Project Link: [https://github.com/HarounM/EasyConnect](https://github.com/HarounM/EasyConnect)

[contributors-shield]: https://img.shields.io/github/contributors/github_username/repo_name.svg?style=for-the-badge
[contributors-url]: https://github.com/HarounM/EasyConnect/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/github_username/repo_name.svg?style=for-the-badge
[forks-url]: https://github.com/HarounM/EasyConnect/network/members
[stars-shield]: https://img.shields.io/github/stars/github_username/repo_name.svg?style=for-the-badge
[stars-url]: https://github.com/HarounM/EasyConnect/stargazers
[issues-shield]: https://img.shields.io/github/issues/github_username/repo_name.svg?style=for-the-badge
[issues-url]: https://github.com/HarounM/EasyConnect/issues
[license-shield]: https://img.shields.io/github/license/github_username/repo_name.svg?style=for-the-badge
[license-url]: https://github.com/HarounM/EasyConnect/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/haroun-maghraoui-08021a1b3/
[product-screenshot]: images/screenshot.png

