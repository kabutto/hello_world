# hello_world
# just another repository

from flask import Flask

app = Flask(__name__)

@app.route("/")
def index():
    return "index2"
    
    
@app.route("/index")
def index2():
    return "index_index"
    

if __name__ == "__main__":
    app.run(debug=True)
  
