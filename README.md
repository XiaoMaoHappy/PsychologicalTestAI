# 智信知心 —— 基于Qwen2大模型的个性化智能心理测评系统
这是一名来自上海的高中生的研究性课题成果，开发不易，感谢支持！

本程序使用了阿里巴巴通义千问Qwen2-0.5B-Instruct大语言模型。

## 软件功能
* 利用AI在特定的聊天语境下获取用户的真实回答
* 分析用户的回答，通过AI推理给出测评报告

## 使用指南
运行GUI.py，稍等一会儿等待窗口出现，按指示操作即可


程序启动和进入测评界面需要一些时间，这取决于你的电脑硬件配置<br>
~~（肯定不是因为有人开发完第一版之后懒得改代码加上threading多线程把窗口运行分开）~~

## Python 环境配置
本程序使用Python 3.9.10在64位win11系统上开发，<br>
开发环境中有以下依赖库：<br>
~~（绝对不是因为没有用虚拟环境，才在根路径下安装了太多库，导致自己都搞不清这个项目和哪些库有关了）~~

> about-time                    4.2.1<br>
absl-py                       2.1.0<br>
accelerate                    0.33.0<br>
aiofiles                      23.2.1<br>
aiohappyeyeballs              2.3.2<br>
aiohttp                       3.10.0<br>
aiosignal                     1.3.1<br>
alive-progress                3.1.5<br>
altair                        5.3.0<br>
altgraph                      0.17.4<br>
annotated-types               0.7.0<br>
anyio                         4.4.0<br>
asttokens                     2.4.1<br>
astunparse                    1.6.3<br>
async-timeout                 4.0.3<br>
attrs                         23.2.0<br>
autograd                      1.6.2<br>
baidutrans                    0.1<br>
cachetools                    5.4.0<br>
certifi                       2024.7.4<br>
cffi                          1.16.0<br>
chardet                       3.0.4<br>
charset-normalizer            3.3.2<br>
click                         8.1.7<br>
cma                           3.2.2<br>
colorama                      0.4.6<br>
coloredlogs                   15.0.1<br>
comm                          0.2.2<br>
comtypes                      1.4.5<br>
contourpy                     1.2.1<br>
cycler                        0.12.1<br>
datasets                      2.14.6<br>
debugpy                       1.8.2<br>
decorator                     5.1.1<br>
Deprecated                    1.2.14<br>
diffusers                     0.23.1<br>
dill                          0.3.7<br>
dnspython                     2.6.1<br>
docstring_parser              0.16<br>
einops                        0.8.0<br>
email_validator               2.2.0<br>
eval_type_backport            0.2.0<br>
exceptiongroup                1.2.2<br>
executing                     2.0.1<br>
fastapi                       0.111.1<br>
fastapi-cli                   0.0.4<br>
ffmpy                         0.4.0<br>
filelock                      3.15.4<br>
flatbuffers                   24.3.25<br>
fonttools                     4.53.1<br>
frozenlist                    1.4.1<br>
fsspec                        2023.10.0<br>
future                        1.0.0<br>
gast                          0.4.0<br>
gevent                        24.2.1<br>
google-auth                   2.32.0<br>
google-auth-oauthlib          1.0.0<br>
google-pasta                  0.2.0<br>
googletrans                   4.0.0rc1<br>
gradio                        4.19.0<br>
gradio_client                 0.10.0<br>
grapheme                      0.6.0<br>
greenlet                      3.0.3<br>
grpcio                        1.65.1<br>
gTTS                          2.5.2<br>
h11                           0.14.0<br>
h2                            3.2.0<br>
h5py                          3.11.0<br>
hpack                         3.0.0<br>
hstspreload                   2024.8.1<br>
httpcore                      1.0.5<br>
httptools                     0.6.1<br>
httpx                         0.27.0<br>
huggingface-hub               0.24.3<br>
humanfriendly                 10.0<br>
hyperframe                    5.2.0<br>
idna                          2.10<br>
importlib_metadata            8.2.0<br>
importlib_resources           6.4.0<br>
ipykernel                     6.29.5<br>
ipython                       8.18.<br>
ipywidgets                    8.1.3<br>
jax                           0.4.30<br>
jaxlib                        0.4.30<br>
jedi                          0.19.1<br>
jieba                         0.42.1<br>
Jinja2                        3.1.4<br>
joblib                        1.4.2<br>
jsonschema                    4.23.0<br>
jsonschema-specifications     2023.12.1<br>
jstyleson                     0.0.2<br>
jupyter_client                8.6.2<br>
jupyter_core                  5.7.2<br>
jupyterlab_widgets            3.0.11<br>
keras                         2.12.0<br>
kiwisolver                    1.4.5<br>
libclang                      18.1.1<br>
Markdown                      3.6<br>
markdown-it-py                3.0.0<br>
MarkupSafe                    2.1.5<br>
matplotlib                    3.9.1<br>
matplotlib-inline             0.1.7<br>
mdurl                         0.1.2<br>
ml-dtypes                     0.4.0<br>
modelscope                    1.17.0<br>
mpmath                        1.3.0<br>
multidict                     6.0.5<br>
multiprocess                  0.70.15<br>
natsort                       8.4.0<br>
nest-asyncio                  1.6.0<br>
networkx                      3.1<br>
ninja                         1.10.2.4<br>
nncf                          2.9.0<br>
numpy                         1.24.3<br>
oauthlib                      3.2.2<br>
ollama                        0.3.1<br>
opencv-python                 4.10.0.84<br>
openvino                      2024.0.0<br>
openvino-telemetry            2024.1.0<br>
opt-einsum                    3.3.0<br>
optimum                       1.21.2<br>
orjson                        3.10.6<br>
packaging                     24.1<br>
pandas                        2.1.4<br>
parso                         0.8.4<br>
pefile                        2023.2.7<br>
peft                          0.12.0<br>
pillow                        10.4.0<br>
pip                           21.2.4<br>
platformdirs                  4.2.2<br>
prompt_toolkit                3.0.47<br>
protobuf                      4.25.4<br>
psutil                        6.0.0<br>
pure_eval                     0.2.3<br>
py-cpuinfo                    9.0.0<br>
pyarrow                       17.0.0<br>
pyarrow-hotfix                0.6<br>
pyasn1                        0.6.0<br>
pyasn1_modules                0.4.0<br>
pycparser                     2.22<br>
pydantic                      2.8.2<br>
pydantic_core                 2.20.1<br>
pydot                         3.0.1<br>
pydub                         0.25.1<br>
pygame                        2.6.0<br>
Pygments                      2.18.0<br>
pyinstaller                   6.11.1<br>
pyinstaller-hooks-contrib     2024.10<br>
pymoo                         0.6.1.3<br>
pyparsing                     3.1.2<br>
pypiwin32                     223<br>
pyreadline3                   3.4.1<br>
python-dateutil               2.9.0.post0<br>
python-dotenv                 1.0.1<br>
python-multipart              0.0.9<br>
pyttsx                        1.1<br>
pyttsx3                       2.90<br>
pytz                          2024.1<br>
pywin32                       306<br>
pywin32-ctypes                0.2.3<br>
PyYAML                        6.0.1<br>
pyzmq                         26.0.3<br>
referencing                   0.35.1<br>
regex                         2024.7.24<br>
requests                      2.32.3<br>
requests-oauthlib             2.0.0<br>
rfc3986                       1.5.0<br>
rich                          13.7.1<br>
rpds-py                       0.19.1<br>
rsa                           4.9<br>
ruff                          0.5.5<br>
safetensors                   0.4.3<br>
scikit-learn                  1.5.1<br>
scipy                         1.13.1<br>
seaborn                       0.13.2<br>
semantic-version              2.10.0<br>
sentencepiece                 0.2.0<br>
setuptools                    58.1.0<br>
shellingham                   1.5.4<br>
shtab                         1.7.1<br>
six                           1.16.0<br>
sniffio                       1.3.1<br>
soundfile                     0.12.1<br>
stack-data                    0.6.3<br>
starlette                     0.37.2<br>
sympy                         1.13.1<br>
tensorboard                   2.12.3<br>
tensorboard-data-server       0.7.2<br>
tensorflow-cpu                2.12.1<br>
tensorflow-estimator          2.12.0<br>
tensorflow-intel              2.12.1<br>
tensorflow-io-gcs-filesystem  0.31.0<br>
termcolor                     2.4.0<br>
texttable                     1.7.0<br>
thop                          0.1.1.post2209072238<br>
threadpoolctl                 3.5.0<br>
tiktoken                      0.7.0<br>
tokenizers                    0.19.1<br>
tomlkit                       0.12.0<br>
toolz                         0.12.1<br>
torch                         2.1.1<br>
torchvision                   0.16.1<br>
tornado                       6.4.1<br>
tqdm                          4.66.4<br>
traitlets                     5.14.3<br>
transformers                  4.42.4<br>
transformers-stream-generator 0.0.5<br>
trl                           0.9.6<br>
typer                         0.12.3<br>
typing_extensions             4.12.2<br>
tyro                          0.8.6<br>
tzdata                        2024.1<br>
ultralytics                   8.2.24<br>
unsloth                       2024.8<br>
urllib3                       2.2.2<br>
uvicorn                       0.30.3<br>
watchfiles                    0.22.0<br>
wcwidth                       0.2.13<br>
websocket                     0.2.1<br>
websocket-client              1.8.0<br>
websockets                    11.0.3<br>
Werkzeug                      3.0.3<br>
wheel                         0.43.0<br>
widgetsnbextension            4.0.11<br>
wordcloud                     1.9.3<br>
wrapt                         1.14.1<br>
xxhash                        3.4.1<br>
yarl                          1.9.4<br>
zipp                          3.19.2<br>
zope.event                    5.0<br>
zope.interface                7.0.1<br>

