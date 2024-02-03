# machine_learning_project

Creating conda environment 
```
conda create -p venv python==3.7 -y

```

```
conda activate venv/

```
or
```
conda activate venv

```
```
pip install -r requirements.txt

```
To setup CI/CD pipeline in heroku we need 3 information:

1. Heroku Email Id: anishyadav7045075175@gmail.com
2. Heroku API Key: e9171a6d-ccd3-44ea-a07b-45f85bf3d096
3. Heroku App Name = ml-regression-app

Bild Docker Image

```
docker build -t <image_name>:<tagname> .
```

Run Docker Image

```
docker run -p 5000:5000 -e PORT=5000 1fd75c038869
```