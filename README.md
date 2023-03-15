# CamFind 📸
## Link to the app
(https://pratyksha-22-camfind-app-qx0n3o.streamlit.app/)

## About
This app can upload, store, and automatically tag images & videos using the Cloudinary API. It has been deployed using streamlit 


The app is built with Streamlit where it displays an image gallery that can be filtered by tag, and also shows a Dashboard that analyzes all tags.

## Software and Tool Requirements
1. [GithubAccount](https://github.com/)
2. [VScodeIDE](https://code.visualstudio.com/)
3. [GitCli](https://cli.github.com/)
4. [Cloudinary](https://cloudinary.com/)
5. [streamlit](https://share.streamlit.io/)

## Installation 
1.create a virtual environment in your anaconda prompt
```
conda create -n envname 
conda activate envname 
```
2.Install the dependencies in your VScode 
```
pip install -r requirement.txt
```
## Configuration
Follow the quick start guide to create a .env file with the CLOUDINARY_URL

https://cloudinary.com/documentation/python_quickstart

```
CLOUDINARY_URL=cloudinary://<api_key>:<api_secret>@<cloud_name>
```
## Implement the Cloudinary Service
The file cloudinary_service.py contains helper functions to upload, tag, and search images.

Prepare a folder with all the photos you want to upload, and then call the upload_folder()function inside the cloudinary_service.py to upload and tag all images.

## Screenshots 
![ss1](https://user-images.githubusercontent.com/92226372/224777882-62fe31f2-8b48-4cb1-b1ad-6f85d19c254e.png)

![ss2](https://user-images.githubusercontent.com/92226372/224778065-670fc6c0-9b7f-43fc-8f3e-8d363b94c8a8.png)
![ss3](https://user-images.githubusercontent.com/92226372/224778343-1720f70b-85e2-4999-9224-661459635ef6.png)

## Run the App
Run the following code in your VScode to run it locally
```
streamlit run app.py
```

