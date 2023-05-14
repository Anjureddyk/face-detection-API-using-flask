# face-detection-API-using-flask
Face detection is the process of locating human faces in images or videos. It is a fundamental technology in computer vision and has numerous applications, such as in security systems, image search, and social media.

This API has been created flask, where this API contains two files one for the flask API and another one is for detecting faces, this detect_faces file contains an .xml file, it has been downloaded form github opencv repository for frontal face detection.

In this code, we create an /upload endpoint that accepts a POST request with a file attached. The file is saved to a local directory specified by UPLOAD_FOLDER, and then the detect_faces function is called to process the image and return a path to the resulting image file. Finally, the API returns a JSON response with a message indicating success and the path to the resulting image file.

When you make a POST request to the /upload endpoint with an image URL in the file_url parameter, the upload() function will download the image from the URL and save it as image.jpg. It will then call the detect_faces() function in the detect_faces.py module to detect faces in the image and return the path to the resulting image file as a response.
