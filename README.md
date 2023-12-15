## Machine Learning Analytic Site
• Developed a full-stack web solution in HTML to deliver machine learning model predictions using user-uploaded datasets\
• Implemented Django REST APIs for backend dataset uploading and streamlined management within the SQLite database\
• Visualized the prediction results generated by a machine learning model built with TensorFlow

## Test the service on local machine: 
• Verify python installation with Python 3.6 or later.\
            python --version\
• Change your terminal to your project directory\
            cd path/to/YOUR_PROJECT_DIRECTORY\
• OPTIONAL: Activate your virtual environment,\
            source env/bin/activate\
            # On Windows use ‘env\Scripts\activate‘ \
– You can also activate virtual environment by selecting python inter- preter on Vscode. \
– Possible error:\
https://stackoverflow.com/questions/4037939/powershell-says-execution-of-scripts-is-disabled-on-this-system \
• Make sure manage.py is present in your terminal’s current working directory \
ls manage.py \
If it gives you ”no such file or directory” as an error, you may need to change directories again. \
• Run the following command and go to http://127.0.0.1:8000/ on your browser.\
python manage.py runserver
