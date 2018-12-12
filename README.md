# Applying Machine Learning Concepts to Results from Distillation Column Simulation

### Setting Up

Install virtualenv and virtualenvwrapper packages by running the following terminal commands.
For more information, please refer to the [official documentation](https://virtualenvwrapper.readthedocs.io/en/latest/install.html).

```
$ pip install --user virtualenv
```

```
$ pip install --user virtualenvwrapper
```

Set up a virtual environment within the project folder of your choice. In this example, my project folder is named project with virtual environment name myenv.

Note: The virtual environment needs to be installed in the project directory, otherwise the Python interpreter running within the notebook will not be able to detect the installed packages.
```
$ mkvirtualenv myenv
```

Activate the virtual environment by changing directory and running 'activate.bat'

```
$ cd project/myenv/Scripts
$ activate
```

Install the required dependencies by running the following command and confirm if
packages are installed. Note that package versions are static - packages may be updated.

```
$ pip install -r requirements.txt
$ pip freeze

cycler==0.10.0
kiwisolver==1.0.1
matplotlib==3.0.2
numpy==1.15.4
pandas==0.23.4
pyparsing==2.3.0
python-dateutil==2.7.5
pytz==2018.7
scikit-learn==0.20.1
scipy==1.1.0
seaborn==0.9.0
six==1.12.0
```

Start local server for Jupyter in the project directory. Your default browser (usually IE) will load the required URL.

```
$ jupyter notebook
```

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/your/project/tags). 

## Authors

* **Jonathan Quah** - [Quattad](https://github.com/quattad)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Authors of all packages that were used (see Setting Up).
* [Chuk](https://www.iss.nus.edu.sg/about-us/staff/detail/532/LEE%20Chuk%20Munn) and [Lisa](https://www.iss.nus.edu.sg/about-us/staff/detail/203/Lisa%20ONG) of NUS ISS for the 4-day course Kickstarting Your Machine Learning Journey, organized by [NUS-ISS](https://www.iss.nus.edu.sg/) and [SGInnovate](https://www.sginnovate.com/).
