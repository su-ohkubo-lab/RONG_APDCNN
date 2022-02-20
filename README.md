# attention pooling-based dilated convolution neural network (APDCNN)

This library has to be run on Anaconda.

Refer to this page to download it.
https://www.anaconda.com/products/individual

I have been using Ubuntu 20.04.2 LTS OS and Python3.6.

These codes were successfully operated on a GPU machine.

They are the libraries in my anaconda environment.

```
(py3.6) rongyunpeng@rongyunpeng-DAIV-DGZ530:~/tensorflow_learn$ pip3 list
Package                  Version
------------------------ -------------------
absl-py                  0.13.0
aiohttp                  3.7.4
anyio                    2.2.0
argon2-cffi              20.1.0
astor                    0.8.1
async-generator          1.10
async-timeout            3.0.1
attrs                    21.2.0
Babel                    2.9.1
backcall                 0.2.0
bleach                   4.0.0
boto3                    1.18.16
botocore                 1.21.16
brotlipy                 0.7.0
cachetools               4.2.2
certifi                  2021.5.30
cffi                     1.14.6
chardet                  3.0.4
click                    8.0.1
contextvars              2.4
coverage                 5.5
cryptography             3.4.7
cycler                   0.10.0
Cython                   0.29.24
dataclasses              0.8
decorator                5.0.9
defusedxml               0.7.1
entrypoints              0.3
gast                     0.5.1
gensim                   3.8.3
google-api-core          1.25.1
google-auth              1.33.0
google-cloud-core        1.7.1
google-cloud-storage     1.41.0
google-crc32c            1.1.2
google-resumable-media   1.3.1
googleapis-common-protos 1.53.0
grpcio                   1.36.1
h5py                     2.10.0
idna                     2.10
idna-ssl                 1.1.0
immutables               0.15
importlib-metadata       3.10.0
ipykernel                5.3.4
ipython                  7.16.1
ipython-genutils         0.2.0
jedi                     0.17.0
jieba                    0.42.1
Jinja2                   3.0.1
jmespath                 0.10.0
joblib                   0.16.0
json5                    0.9.6
jsonschema               3.2.0
jupyter-client           6.1.12
jupyter-core             4.7.1
jupyter-server           1.4.1
jupyterlab               3.1.4
jupyterlab-pygments      0.1.2
jupyterlab-server        2.6.2
Keras                    2.2.4
Keras-Applications       1.0.8
Keras-Preprocessing      1.1.2
kiwisolver               1.3.1
Markdown                 3.3.4
MarkupSafe               2.0.1
matplotlib               3.3.4
mistune                  0.8.4
mkl-fft                  1.3.0
mkl-random               1.1.0
mkl-service              2.3.0
mock                     4.0.3
multidict                5.1.0
nbclassic                0.2.6
nbclient                 0.5.3
nbconvert                6.0.7
nbformat                 5.1.3
nest-asyncio             1.5.1
nltk                     3.6.2
notebook                 6.4.2
numpy                    1.17.0
olefile                  0.46
packaging                21.0
pandas                   1.1.5
pandocfilters            1.4.3
parso                    0.8.2
pexpect                  4.8.0
pickleshare              0.7.5
Pillow                   8.3.1
pip                      21.2.2
prometheus-client        0.11.0
prompt-toolkit           3.0.17
protobuf                 3.17.2
ptyprocess               0.7.0
pyasn1                   0.4.8
pyasn1-modules           0.2.8
pycparser                2.20
Pygments                 2.9.0
pyOpenSSL                20.0.1
pyparsing                2.4.7
pyrsistent               0.17.3
PySocks                  1.7.1
python-dateutil          2.8.2
pytz                     2021.1
PyYAML                   5.4.1
pyzmq                    22.2.1
regex                    2021.7.6
requests                 2.25.1
rsa                      4.7.2
s3transfer               0.5.0
scikit-learn             0.24.2
scipy                    1.4.1
seaborn                  0.11.1
Send2Trash               1.5.0
setuptools               52.0.0.post20210125
six                      1.16.0
smart-open               5.1.0
sniffio                  1.2.0
tensorboard              1.13.1
tensorflow               1.13.1
tensorflow-estimator     1.13.0
termcolor                1.1.0
terminado                0.9.4
testpath                 0.5.0
threadpoolctl            2.2.0
tornado                  6.1
tqdm                     4.62.0
traitlets                4.3.3
typing-extensions        3.10.0.0
urllib3                  1.26.6
wcwidth                  0.2.5
webencodings             0.5.1
Werkzeug                 1.0.1
wheel                    0.37.0
yarl                     1.5.1
zipp                     3.5.0
```


