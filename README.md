
[![GitHub license](https://img.shields.io/github/license/swapnanildutta/CoronavirusDatabase)](https://github.com/swapnanildutta/CoronavirusDatabase)

<!-- PROJECT LOGO -->
<br />
<p align="center">
  <a href="https://github.com/swapnanildutta/CoronavirusDatabase">
    <img src="assets/logo-readme.png" alt="Logo" width="80" height="80">
  </a>
  <h3 align="center">Corona-Virus-Database</h3>
</p>

<!-- TABLE OF CONTENTS -->

## Table of Contents

- [Corona Virus Database](#corona-virus-database)
    - [Built With](#built-with)
  - [Getting Started](#getting-started)
    - [Installation](#installation)
  - [Usage](#usage)
  - [Roadmap](#roadmap)
  - [Contributing](#contributing)
  - [License](#license)
  - [Contact](#contact)
  - [Acknowledgements](#acknowledgements)

<!-- ABOUT THE PROJECT -->

## About The Project

### Corona Virus Database

I have used web scraping to collect the data and stored it into a .json file and further using the .json file to add to SQLite Database and also trying to make an API using Flask.

### Built With

This section should list any major frameworks that you built your project using. Leave any add-ons/plugins for the acknowledgements section. Here are a few examples.

- [Python 3](https://www.python.org/)

<!-- GETTING STARTED -->

## Getting Started

This is an example of how you may give instructions on setting up your project locally.
To get a local copy up and running follow these simple example steps.

### Installation
*NOTE: If running `python` does not work for you, use what you normally use to envoke python. Some things to try are `py` (for windows) and `python3` (for bash).*
1. Clone the repo

```sh
 git clone https://github.com/swapnanildutta/CoronavirusDatabase.git
```

2. Move into the cloned directory

```sh
cd CoronavirusDatabse
```

3. Create a [virtual environment](https://docs.python.org/3/tutorial/venv.html) and set it up (Optional)
```sh
python -m venv coronavirus_venv
```
##### On Windows:
```sh
coronavirus_venv\Scripts\activate
```
##### On Bash (Mac or Linux):
```sh
source coronavirus_venv/bin/activate
```
Your terminal should now be something like `(coronavirus_venv) Some\path $`

4. Install the requirements
```sh
python -m pip install -r requirements.txt`
```
5. Run CoronavirusDatabse
```sh
python coronavirusweb.py
```

## Usage

I have used web scraping to collect the data and stored it into a .json file and further using the .json file to add to SQLite Database and also trying to make an API using Flask.

- add some more features.
- use pictures for demo if you can
- or use gif images here if you want

<!-- Here you can add documentation link for the more user-understanble -->

_For more examples, please refer to the [Documentation]()_

<!-- ROADMAP -->

## Roadmap

See the [open issues](https://github.com/swapnanildutta/CoronavirusDatabase) for a list of proposed features (and known issues).

<!-- CONTRIBUTING -->

## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<!-- LICENSE -->

## License

<!-- Here you can add license link  -->

Distributed under the License. See [`LICENSE`](https://choosealicense.com/licenses/mit/) for more information.
