# GCP-Python-WebAPP
Deploying Hello world Python App on Google Cloud Platform's App Engine

## Creating Project
1.Go to GCP Console Home,Click on cloud shell icon. it will open shell cmd prompt on bottom screen

<img align="center" src="https://github.com/Salmandabbakuti/GCP-Python-WebApp/blob/master/chrome_2019-04-24_22-33-46.png">

2. Click on Little pen icon on top right of shell. it will take you to cloudshell UI site.

<img align="center" src="https://github.com/Salmandabbakuti/GCP-Python-WebApp/blob/master/chrome_2019-04-24_22-34-40.png">


3. Create a new folder by  rigth clicking on  your root directory.

<img align="center" src="https://github.com/Salmandabbakuti/GCP-Python-WebApp/blob/master/chrome_2019-04-24_22-46-25.png">


4. Create app.yaml, main.py, requirements.txt files in newfolder directory

<img align="center" src="https://github.com/Salmandabbakuti/GCP-Python-WebApp/blob/master/chrome_2019-04-24_22-21-52.png">


## Folder Structure
```
├── pythondemo
│   ├── app.yaml
│   ├── main.py
│   └── requirements.txt
```
## Deploy App

in your folder directory, run following command. it will take sometime to deploy your app.

```
gcloud app deploy
```

<img align="center" src="https://github.com/Salmandabbakuti/GCP-Python-WebApp/blob/master/chrome_2019-04-24_22-56-18.png">
 
## Browse APP

once deployed, run this command and it will show deployed address and paste this address in your browser. it will show deployed python Webapp response.

```

gcloud app  browse
```
