# keras-brain-tumor-scan

![brain scan image](https://images.pexels.com/photos/4226264/pexels-photo-4226264.jpeg?auto=compress&cs=tinysrgb&dpr=3&h=750&w=1260)

Add description

dataset: https://www.kaggle.com/sartajbhuvaji/brain-tumor-classification-mri

-----


Install dependencies:

Upgrade pip and install [pipenv](https://pipenv.pypa.io/en/latest/)

```
pip install --upgrade --user pip

pip install --upgrade pipenv
```

Create and activate the virtual enviroment.The python version already needs to be installed in your pc

I am using this python version because at the moment this python version is  compatible with tensorflow and keras

```
pipenv install --python 3.7.8
```

Install necessary modules and activate it

```
pipenv install tensorflow==2.4.1 matplotlib==3.3 keras==2.4

pipenv shell
```

Install modules to make sure the code runs on a jupyter notebook

```
pipenv install ipykernel
python -m ipykernel install --user --name ENVNAME --display-name "Python (whatever you want to call it)"
```
After all this, start jupyter notebook

```
jupyter notebook
```

-----

Started on 08/04/2021

Ended

Archived
