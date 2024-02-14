<div align="center">

# Let's Git

[![license][license]][license-url]
[![python][python]][python-url]
[![jupyter][jupyter]][jupyter-url]

</div>

## Description
-   Climate vs. Crime Index
-   US North & US South vs. Crime Index
-   Climate vs. Suicide Rate

## Table of Contents

-   [Installation](#installation)
-   [Usage](#usage)
-   [Tests](#tests)
-   [Contributing](#contributing)
-   [License](#license)
-   [Contact](#contact)
-   [Credits](#credits)

## Installation

1.  Clone the repo

    ```sh
    git clone https://github.com/manc1n1/lets-git.git
    ```

2.  Change directories to `lets-git`

    ```sh
    cd lets-git
    ```

3.  Install dependencies

    ```sh
    pip install -r requirements.txt
    ```
    
4.  Open and Run `Jupyter Notebook` file `city_data.ipynb`
5.  Open and Run `Jupyter Notebook` file `weather_data.ipynb`
6.  Open and Run `Jupyter Notebook` file `suicide_data.ipynb`

## Usage

<div align="center">
    
**Crime Index Map Plot**

![cimp](https://github.com/manc1n1/lets-git/assets/18316547/b477d2b9-bb9f-4711-afa5-10cc154a82ad)

<img width="698" alt="Average Temp Hist" src="https://github.com/manc1n1/lets-git/assets/18316547/e90c3128-822b-44a8-9b7a-325f6f3e192e">

<img width="698" alt="Crime Index Hist" src="https://github.com/manc1n1/lets-git/assets/18316547/eed5f027-8ea8-4420-98e4-52a53acb662b">

**Average Temperature vs. Crime Index**

The r-squared is: 0.02647214945425883

![tvc](https://github.com/manc1n1/lets-git/assets/18316547/1c2afe07-d215-4635-9d54-29da8504ae2e)

**Average Temperature vs. Suicide Rate (per 100k population)**

The r-squared is: 0.0946009854236267

![tvs](https://github.com/manc1n1/lets-git/assets/18316547/22d79225-59c8-44b8-97bf-e69865d51cff)

**US Crime Index Map Plot**

<img width="847" alt="US Crime Map" src="https://github.com/manc1n1/lets-git/assets/18316547/44a797c2-6450-4a79-909a-84f586173df2">

**US Temperature Map Plot**

<img width="845" alt="US Temp Map" src="https://github.com/manc1n1/lets-git/assets/18316547/570191d5-0b05-432b-9c0f-b6bdebcadf71">

**Average Temperature (US) vs. Crime Index (US)**

![image](https://github.com/manc1n1/lets-git/assets/18316547/aa712bd0-7df6-4da5-be4e-ddbe37b9fc6a)

**Average Temperature (Northern US) vs. Crime Index (Northern US)**

The r-squared is: 0.12882830500813564

![nus](https://github.com/manc1n1/lets-git/assets/18316547/0a33ae6d-cb3a-4fd3-813b-067cb3599696)

**Average Temperature (Southern US) vs. Crime Index (Southern US)**

The r-squared is: 0.008932637280915468

![sus](https://github.com/manc1n1/lets-git/assets/18316547/9f3e097a-b768-45c1-8a33-0c00aeaf82f4)

**Boxplot grouped by US Region**

TtestResult(statistic=-0.3693358190026192, pvalue=0.7142702467645812, df=32.53740112916721)

![image](https://github.com/manc1n1/lets-git/assets/18316547/a7a9b883-7ad9-4112-8803-e1a0efb5c725)

</div>

## Tests

## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

[MIT License](https://opensource.org/licenses/MIT)

## Contact

-   Email mancinij1111@gmail.com
-   GitHub [manc1n1](https://github.com/manc1n1)

## Credits

[license]: https://img.shields.io/github/license/manc1n1/lets-git.svg?style=for-the-badge
[license-url]: https://github.com/manc1n1/lets-git/blob/master/LICENSE
[python]: https://img.shields.io/badge/python-3776AB?style=for-the-badge&logo=python&logoColor=ffdd54
[python-url]: https://www.python.org/
[jupyter]: https://img.shields.io/badge/jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white
[jupyter-url]: https://jupyter.org/
