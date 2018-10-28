# kaggle-competitions

### Lesson Learned
#### Setup
- The command `jupyter notebook` will always execute from base conda (by default), even when you activate virtual environment. Hence, in order to be able to use kernel of your virtual environment. Use the following command to add your kernel of your virtual environment
```
$ source activate myvirtualenv
(myvirtualenv) $ pip install ipykernel
(myvirtualenv) $ python -m ipykernel install --user --name myvirtualenv --display-name "Python (myvirtualenv)"
```