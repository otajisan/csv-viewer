# csv-viewer
csv viewer

# Development Environment

developed python version

```
$ python -V
Python 3.6.6
```

generate/update requirements.txt

```
$ pip install pip-tools
$ LC_CTYPE="ja_JP.UTF-8";pip-compile --output-file requirements.txt requirements.in
```

install required packages for development

```
$ pip install -r requirements.txt`
````

install develop package

```
$ pip install -e .
```

# References

install pyenv-virtualenv on anyenv x pyenv environment

```
$ git clone https://github.com/pyenv/pyenv-virtualenv.git  ~/.anyenv/envs/pyenv/plugins/pyenv-virtualenv
```

```
$ echo 'eval "$(pyenv virtualenv-init -)"' >> ~/.zshrc
```

make new virtualenv

```
$ pyenv virtualenv 3.6.6 csv-viewer
```

use created virtual env

```
$ pyenv global 3.6.6/envs/csv-viewer
```
