<div id="top"></div>

[![LinkedIn][linkedin-shield]][linkedin-url]
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![GNU v3 License][license-shield]][license-url]



<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/estebanvz/crypto_price/">
    <img src="https://avatars.githubusercontent.com/u/65377832?s=400&u=12c57a2350bcd69068ced71f630ca0d5559e6621&v=4)}" alt="Logo" width="80" height="80" style="border-radius:100%">
  </a>

  <h3 align="center"> Crypto Coin Price Extractor - Python Package
</h3>

  <p align="center">
    Python Package focused on download crypto prices from binance.
    <br />
    <!-- <a href="https://github.com/estebanvz/crypto_price"><strong>Explore the docs »</strong></a>
    <br /> -->
    <br />
    <a href="https://github.com/estebanvz/crypto_price/">View Test</a>
    ·
    <a href="https://github.com/estebanvz/crypto_price/issues">Report Bug</a>
    ·
    <a href="https://github.com/estebanvz/crypto_price/issues">Request Feature</a>
  </p>
</div>



<!-- TABLE OF CONTENTS
<details>
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
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details> -->



<!-- ABOUT THE PROJECT -->
## About The Package

This is a small package to download the prices of cryptos using Binance API.

<p align="right">(<a href="#top">back to top</a>)</p>



### Built With

This project was builded with the next technologies.

* [Python](https://python.org/)

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Getting Started


<!-- ### Prerequisites

You need the next components to run this project.
* Docker. To install it follow these steps [Click](https://docs.docker.com/get-docker/). 
  On Ubuntu, you can run:
```sh
sudo apt-get install docker-ce docker-ce-cli containerd.io
```
* Visual Studio Code. To install it follow these steps [Click](https://code.visualstudio.com/download). On Ubuntu, you can run:
```sh
sudo snap install code --classic
```
* Install the visual studio code extension "Remote - Containers" -->
### Installation

Follow the next steps:

1. Setup the project:
   ```python
   python setup.py sdist
   ```
2. Build the package:
   ```python
   python setup.py build
   ```
3. Install the package
   ```python
   python setup.py install
   ```
4. Install the package using pip.
    ```bash
    pip install crypto_price
    ```
<p align="right">(<a href="#top">back to top</a>)</p>

### Usage
Get the keys from API Binance:

[GET BINANCE API KEYS](https://www.binance.com/en/support/faq/360002502072)

You can use the package using the **api_key** and **api_secret** from binance API.
```python
from decouple import config
from crypto_price import CryptoDataExtractor
API_KEY = config("API_KEY")
API_SECRET = config("API_SECRET")
extractor = CryptoDataExtractor()
extractor.from_binance(api_key=API_KEY,api_secret=API_SECRET)
```

<!-- USAGE EXAMPLES
## Usage

Use this space to show useful examples of how a project can be used. Additional screenshots, code examples and demos work well in this space. You may also link to more resources.

_For more examples, please refer to the [Documentation](https://example.com)_

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- ROADMAP -->
<!-- ## Roadmap

- [x] Add Changelog
- [x] Add back to top links
- [ ] Add Additional Templates w/ Examples
- [ ] Add "components" document to easily copy & paste sections of the readme
- [ ] Multi-language Support
    - [ ] Chinese
    - [ ] Spanish

See the [open issues](https://github.com/estebanvz/crypto_price/issues) for a full list of proposed features (and known issues).

<p align="right">(<a href="#top">back to top</a>)</p> -->

<!-- LICENSE -->
## License

Distributed under the GNU v3 License. See `LICENSE` for more information.

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

Esteban Vilca - [@ds_estebanvz](https://twitter.com/ds_estebanvz) - [esteban.wilfredo.g@gmail.com](mailto:esteban.wilfredo.g@gmail.com)

Project Link: [https://github.com/estebanvz/crypto_price](https://github.com/estebanvz/crypto_price)

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/estebanvz/crypto_price.svg
[contributors-url]: https://github.com/estebanvz/crypto_price/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/estebanvz/crypto_price.svg
[forks-url]: https://github.com/estebanvz/crypto_price/network/members
[stars-shield]: https://img.shields.io/github/stars/estebanvz/crypto_price.svg
[stars-url]: https://github.com/estebanvz/crypto_price/stargazers
[issues-shield]: https://img.shields.io/github/issues/estebanvz/crypto_price.svg
[issues-url]: https://github.com/estebanvz/crypto_price/issues
[license-shield]: https://img.shields.io/github/license/estebanvz/crypto_price.svg
[license-url]: https://github.com/estebanvz/crypto_price/blob/main/LICENSE
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?=linkedin&colorB=888
[linkedin-url]: https://linkedin.com/in/estebanvz
[product-screenshot]: images/screenshot.png