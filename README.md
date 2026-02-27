### Boston House Pricing Prediction

### Software And Tools Requirements

1. [Github Account](https://github.com)
2. [HerokuAccount](https://heroku.com)
3. [VSCodeIDE](https://code.visualstudio.com/)
4. [GitCLI](https://git-scm.com/book/en/v2/Getting-Started-The-Command-Line)

Create a new environment

```
conda create -p venv python==3.7 -y


```


conda deactivate
conda create -p venv python==3.10
conda activate venv/
pip install -r requirements.txt


docker pull buzz7/flasktest-app                          # after deploying pull image
docker run -p 5000:5000 buzz7/flasktest-app:latest       # run app


docker build -t welcome_app .            # cmd to buld docker image loclal machine
docker images                                         # check list of images
docker run -p 5000:5000 welcome_app                   # run app
docker stop                                           # stop app
docker login                                           # login docker hub
docker image rm =f welcome_app                         # remove repository
docker build -t buzz7/welcome_app .                # build to push in docker hub
docker tag buzz7/welcome_app buzz7/welcome_app1     # copy and rename it
docker push buzz7/welcome_app:latest               # push to docker hub
docker pull buzz7/welcome_app:latest               # pull image to run
docker run -d -p 5000:5000 buzz7/welcome_app:latest  # run app

