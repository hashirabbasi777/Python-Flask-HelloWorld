Readme For Python Flask Hello World


Windows (PowerShell):

mkdir flask-hello
cd flask-hello
python -m venv venv
.\venv\Scripts\Activate.ps1


Install Flask
pip install --upgrade pip
pip install flask


Create the Flask app file

Create a file named app.py with this content:

from flask import Flask

app = Flask(__name__)

@app.route("/")
def hello():
    return "Hello, Flask!"

if __name__ == "__main__":
    app.run(debug=True)


Run the Flask server
python app.py



    
