1. Setup virutal environment:

    `mkvirtualenv ml`
    `pip install -r requirements.txt`

2. Run the notebook (from within the virtualenv)

    `ipython notebook`


If you have any problems, you may need to:
* Upgrade pip & wheel (e.g. `pip install --upgrade pip`)
* Install ipython from within the virtualenv. If you do this, `deactivate` and then `workon ml` before trying to run the notebook again.
