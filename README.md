# ML with Flask Project

This project demonstrates the implementation of a machine learning (ML) model using Flask.

## HOW TO USE IT
- we need the `main.py` to modify the directory of model.h5 file
- run the app

## Application Flow
- The user visits the homepage (http://localhost:5000/) and it will shows "OK".
- The user submits the form, triggering a POST request to the Flask server.
- The server receives the data and processes it using the trained ML model.
- The server returns the ML model's prediction as a response to the user's request.
- The prediction is displayed on the result page.

# API DOCUMENTATION
## ADD IMAGE 
    URL             : /
    Method          : POST
    Body	          : file| key = image, value = select files 
    Response        : 
                        {
                            "predict": "THE_PREDICTION_OF_SKIN"
                        }



