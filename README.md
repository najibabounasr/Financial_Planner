# Financial_Planner

![alt text](5-4-challenge-image.png?raw=True "Financial Planning")

Financial Manager. The application is split into: 'Financial Planner for Emergencies', and 'Financial Planner for Retirement'.
### Background

You’ve decided to start a fintech consulting firm that focuses on projects to benefit local communities. You just won your first contract with a large credit union. The project entails building a tool to help credit union members evaluate their financial health. Specifically, the credit union board wants the members to be able to do two things. First, they should be able to assess their monthly budgets. Second, they should be able to forecast a reasonably effective retirement plan based on their current holdings of cryptocurrencies, stocks, and bonds. The chief technology officer (CTO) of the credit union wants you to develop a prototype application to present at its next assembly.
#### What You're Creating
You’ll create two financial analysis tools by using a single Jupyter notebook:

    1. A financial planner for emergencies. The members will be able to use this tool to visualize their current savings. The members can then determine if they have enough reserves for an emergency fund.

    2. A financial planner for retirement. This tool will forecast the performance of their retirement portfolio in 30 years. To do this, the tool will make an Alpaca API call via the Alpaca SDK to get historical price data for use in Monte Carlo simulations.

You’ll use the information from the Monte Carlo simulation to answer questions about the portfolio in your Jupyter notebook.


## Technologies

> This project uses the software jupyter lab with the following  softwares, and their installed versions :


Package                       Version
----------------------------- --------------------
aiohttp                       3.8.1
aiosignal                     1.3.1
alabaster                     0.7.12
alpaca-trade-api              2.3.0
anaconda-client               1.11.0
anaconda-project              0.11.1
anyio                         3.5.0
appdirs                       1.4.4
applaunchservices             0.3.0
appnope                       0.1.2
appscript                     1.1.2
argon2-cffi                   21.3.0
argon2-cffi-bindings          21.2.0
arrow                         1.2.2
astroid                       2.11.7
astropy                       4.3.1
async-timeout                 4.0.2
asynctest                     0.13.0
atomicwrites                  1.4.0
attrs                         21.4.0
Automat                       20.2.0
autopep8                      1.6.0
Babel                         2.9.1
backcall                      0.2.0
backports.functools-lru-cache 1.6.4
backports.tempfile            1.0
backports.weakref             1.0.post1
bcrypt                        3.2.0
beautifulsoup4                4.11.1
binaryornot                   0.4.4
bitarray                      2.5.1
bkcharts                      0.2
black                         22.6.0
bleach                        4.1.0
bokeh                         2.4.3
boto3                         1.24.28
botocore                      1.27.28
Bottleneck                    1.3.5
brotlipy                      0.7.0
certifi                       2022.9.24
cffi                          1.15.1
chardet                       4.0.0
charset-normalizer            2.0.4
click                         8.0.4
cloudpickle                   2.0.0
clyent                        1.2.2
colorama                      0.4.5
colorcet                      3.0.0
conda                         22.11.1
conda-content-trust           0.1.3
conda-pack                    0.6.0
conda-package-handling        1.9.0
conda-token                   0.4.0
constantly                    15.1.0
cookiecutter                  1.7.3
cryptography                  37.0.1
cssselect                     1.1.0
cycler                        0.11.0
Cython                        0.29.32
cytoolz                       0.11.0
daal4py                       2021.6.0
dask                          2021.10.0
datashader                    0.14.1
datashape                     0.5.4
debugpy                       1.5.1
decorator                     5.1.1
defusedxml                    0.7.1
deprecation                   2.1.0
diff-match-patch              20200713
dill                          0.3.4
distributed                   2021.10.0
docutils                      0.17.1
entrypoints                   0.4
et-xmlfile                    1.1.0
fastjsonschema                2.16.2
filelock                      3.6.0
flake8                        4.0.1
Flask                         1.1.2
fonttools                     4.25.0
frozenlist                    1.3.3
fsspec                        2022.7.1
future                        0.18.2
gensim                        4.1.2
glob2                         0.7
gmpy2                         2.1.2
greenlet                      1.1.1
h5py                          2.10.0
HeapDict                      1.0.1
holoviews                     1.15.0
hvplot                        0.8.0
hyperlink                     21.0.0
idna                          3.3
imagecodecs                   2021.8.26
imageio                       2.19.3
imagesize                     1.4.1
importlib-metadata            3.10.0
importlib-resources           5.2.0
incremental                   21.3.0
inflection                    0.5.1
iniconfig                     1.1.1
intake                        0.6.5
intervaltree                  3.1.0
ipykernel                     6.15.2
ipython                       7.31.1
ipython-genutils              0.2.0
ipywidgets                    7.6.5
isort                         5.9.3
itemadapter                   0.3.0
itemloaders                   1.0.4
itsdangerous                  2.0.1
jdcal                         1.4.1
jedi                          0.18.1
jellyfish                     0.9.0
Jinja2                        2.11.3
jinja2-time                   0.2.0
jmespath                      0.10.0
joblib                        1.1.0
json5                         0.9.6
jsonschema                    4.16.0
jupyter                       1.0.0
jupyter_client                7.3.5
jupyter-console               6.4.3
jupyter_core                  4.11.1
jupyter-server                1.18.1
jupyterlab                    3.4.4
jupyterlab-pygments           0.1.2
jupyterlab-server             2.10.3
jupyterlab-widgets            1.0.0
keyring                       23.4.0
kiwisolver                    1.4.2
lazy-object-proxy             1.6.0
libarchive-c                  2.9
llvmlite                      0.38.0
locket                        1.0.0
lxml                          4.9.1
Markdown                      3.3.4
MarkupSafe                    2.0.1
matplotlib                    3.5.2
matplotlib-inline             0.1.6
mccabe                        0.7.0
mistune                       0.8.4
mkl-fft                       1.3.1
mkl-random                    1.2.2
mkl-service                   2.4.0
mock                          4.0.3
mpmath                        1.2.1
msgpack                       1.0.3
multidict                     6.0.4
multipledispatch              0.6.0
munkres                       1.1.4
mypy-extensions               0.4.3
nbclassic                     0.3.5
nbclient                      0.5.13
nbconvert                     6.4.4
nbformat                      5.5.0
nest-asyncio                  1.5.5
networkx                      2.6.3
nltk                          3.7
nose                          1.3.7
notebook                      6.4.12
numba                         0.55.1
numexpr                       2.8.3
numpy                         1.21.5
numpydoc                      1.4.0
olefile                       0.46
openpyxl                      3.0.10
packaging                     21.3
pandas                        1.3.5
pandocfilters                 1.5.0
panel                         0.13.1
param                         1.12.0
parsel                        1.6.0
parso                         0.8.3
partd                         1.2.0
pathspec                      0.9.0
patsy                         0.5.2
pep8                          1.7.1
pexpect                       4.8.0
pickleshare                   0.7.5
Pillow                        9.2.0
pip                           22.2.2
pkginfo                       1.8.2
pkgutil_resolve_name          1.3.10
platformdirs                  2.5.2
plotly                        5.9.0
pluggy                        1.0.0
ply                           3.11
poyo                          0.5.0
prometheus-client             0.14.1
prompt-toolkit                3.0.20
Protego                       0.1.16
psutil                        5.9.0
ptyprocess                    0.7.0
py                            1.11.0
pyasn1                        0.4.8
pyasn1-modules                0.2.8
pycodestyle                   2.8.0
pycosat                       0.6.3
pycparser                     2.21
pycrypto                      2.6.1
pyct                          0.4.8
pycurl                        7.45.1
PyDispatcher                  2.0.5
pydocstyle                    6.1.1
pyerfa                        2.0.0
pyflakes                      2.4.0
Pygments                      2.11.2
PyHamcrest                    2.0.2
pylint                        2.14.5
pyls-spyder                   0.4.0
pyobjc-core                   8.5
pyobjc-framework-Cocoa        8.5
pyobjc-framework-CoreServices 8.5
pyobjc-framework-FSEvents     8.5
pyodbc                        4.0.34
pyOpenSSL                     22.0.0
pyparsing                     3.0.9
PyQt5-sip                     12.11.0
pyrsistent                    0.18.0
PySocks                       1.7.1
pytest                        7.1.2
python-dateutil               2.8.2
python-dotenv                 0.21.1
python-lsp-black              1.2.1
python-lsp-jsonrpc            1.0.0
python-lsp-server             1.5.0
python-slugify                5.0.2
python-snappy                 0.6.0
pytz                          2022.1
pyviz-comms                   2.0.2
PyWavelets                    1.3.0
PyYAML                        6.0
pyzmq                         23.2.0
QDarkStyle                    3.0.2
qstylizer                     0.1.10
QtAwesome                     1.0.3
qtconsole                     5.3.2
QtPy                          2.2.0
queuelib                      1.5.0
regex                         2022.7.9
requests                      2.28.1
requests-file                 1.5.1
rope                          0.22.0
Rtree                         0.9.7
ruamel.yaml                   0.17.21
ruamel.yaml.clib              0.2.6
ruamel-yaml-conda             0.15.100
s3transfer                    0.6.0
scikit-image                  0.19.2
scikit-learn                  1.0.2
scikit-learn-intelex          2021.20221004.121742
scipy                         1.7.3
Scrapy                        2.6.2
seaborn                       0.11.2
Send2Trash                    1.8.0
service-identity              18.1.0
setuptools                    63.4.1
sip                           6.6.2
six                           1.16.0
smart-open                    5.2.1
sniffio                       1.2.0
snowballstemmer               2.2.0
sortedcollections             2.1.0
sortedcontainers              2.4.0
soupsieve                     2.3.1
Sphinx                        4.2.0
sphinxcontrib-applehelp       1.0.2
sphinxcontrib-devhelp         1.0.2
sphinxcontrib-htmlhelp        2.0.0
sphinxcontrib-jsmath          1.0.1
sphinxcontrib-qthelp          1.0.3
sphinxcontrib-serializinghtml 1.1.5
spyder                        5.3.3
spyder-kernels                2.3.3
SQLAlchemy                    1.4.39
statsmodels                   0.13.2
sympy                         1.10.1
tables                        3.6.1
tabulate                      0.8.10
TBB                           0.2
tblib                         1.7.0
tenacity                      8.0.1
terminado                     0.13.1
testpath                      0.6.0
text-unidecode                1.3
textdistance                  4.2.1
threadpoolctl                 2.2.0
three-merge                   0.1.1
tifffile                      2021.7.2
tinycss                       0.4
tldextract                    3.2.0
toml                          0.10.2
tomli                         2.0.1
tomlkit                       0.11.1
toolz                         0.11.2
tornado                       6.2
tqdm                          4.64.1
traitlets                     5.1.1
Twisted                       22.2.0
typed-ast                     1.4.3
typing_extensions             4.3.0
ujson                         5.4.0
Unidecode                     1.2.0
urllib3                       1.26.11
w3lib                         1.21.0
watchdog                      2.1.6
wcwidth                       0.2.5
webencodings                  0.5.1
websocket-client              0.58.0
websockets                    10.4
Werkzeug                      2.0.3
whatthepatch                  1.0.2
wheel                         0.37.1
widgetsnbextension            3.5.2
wrapt                         1.14.1
wurlitzer                     3.0.2
xarray                        0.20.1
xlrd                          2.0.1
XlsxWriter                    3.0.3
xlwings                       0.27.15
yapf                          0.31.0
yarl                          1.8.2
zict                          2.1.0
zipp                          3.8.0
zope.interface                5.4.0


The following python modules are also used in the application. Remember to install these packages via Terminal for MacOS/Linux or GitBash for windows clients. 
* [pandas](https://github.com/pandas-dev/pandas) - pandas is used to interact with data packages, plot data frames, create new dataframes, describe abailable data, and helps traders and fintech proffesionals organize financial data to perform advanced decisionmaking. 

* [pathlib](https://github.com/python/cpython/blob/main/Lib/pathlib.py) - Allows the user to specify the path to a data frame / any data in a csv file. 

* [numpy]
(https://github.com/numpy/numpy)
- NumPy is the fundamental package for scientific computing with Python. It provides: a powerful N-dimensional array object, sophisticated (broadcasting) functions tools for integrating C/C++ and Fortran code, useful linear algebra, Fourier transform, and random number capabilities. 

* [json]
(https://github.com/nlohmann/json)
- JSON (JavaScript Object Notation), specified by RFC 7159 (which obsoletes RFC 4627) and by ECMA-404, is a lightweight data interchange format inspired by JavaScript object literal syntax (although it is not a strict subset of JavaScript. 

* [os]
(https://docs.python.org/3/library/os.html)
- This module provides a portable way of using operating system dependent functionality. If you just want to read or write a file see open(), if you want to manipulate paths, see the os.path module, and if you want to read all the lines in all the files on the command line see the fileinput module. For creating temporary files and directories see the tempfile module, and for high-level file and directory handling see the shutil module..

* [dotenv]
(https://pypi.org/project/python-dotenv/)
- Python-dotenv reads key-value pairs from a .env file and can set them as environment variables. It helps in the development of applications following the 12-factor principles.

* [alpaca_trade_api]
(https://github.com/alpacahq/alpaca-trade-api-python)
- alpaca-trade-api-python is a python library for the Alpaca Commission Free Trading API. It allows rapid trading algo development easily, with support for both REST and streaming data interfaces. For details of each API behavior, please see the online API document.

* [requests]
(https://pypi.org/project/requests/)
- Requests is a simple, yet elegant, HTTP library..

* [MCForecastTools]
- 'Monte Carlo Forecast Tools' provided by the Berkley Fintech Bootcamp; provides functionality to help interact with data, and simulate market results with varying weight, stock, and time paramaters.


## Installation Guide

There are three installations neccesary for the program to run. Make sure these are installed via terminal (for MacOS) or GitBash (Windows/Linux)

'''python
    pip3 install pandas
    pip3 install numpy
    pip3 install pathlib
    pip install python-dotenv
    pip install alpaca-trade-api
    conda install -c anaconda requests
    conda install -c jmcmurray json
'''


## Usage

In order to interact with the application, please first clone the repository, and then in the command line run type in:

'''python
python financial_planning_tools.ipynb
'''
NOTE : remember to be in the application folder (clone) when imputing the command.
---

## Contributors

The sole contributor for this project is:

**NAJIB ABOU NASR**
 no instagram or linkedin yet!

--

## License

Using the 'MIT' license!

--
## History

### 
    Here, I documented my command line inputs, to show the changes I had made, and document the debugging and programing process:  


