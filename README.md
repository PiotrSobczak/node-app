# Dependencies
 - scala 2.12.3
 - sbt 1.2.8
 - python 3.6
 - pip 9.0.1

# How to run

### Install flask server requirements
```
pip3 install -r requirements.txt
```

### Build application jar
```
sbt assembly
```

### Set paths to jar and excel sheet in config.py 
```
{
  "jar_path": "/path/to/assembly/jar",
  "sheet_path": "/path/to/xlsx/sheet"
}
```

### Start the server
```
python3 server.py -c config.py
```

 
# View node structure
After running flask server successfully, simply go to go to http://127.0.0.1:5000/. A sample view is presented below.</br></br>
<img src="https://github.com/PiotrSobczak/NodeApp/blob/master/images/node_view.png" width="600"></img>



