# Hackust
Recipt Tracker

# Setting up the environment (Linux)
1. Create virtual environment
```bash
python3 -m venv env
``` 
2. Start the virtualenv
```bash
source env/bin/activate
```
3. Install required modules 
```bash
chmod +x bin/setup
./bin/setup
```

# Compile front-end source Code
1. Run webpack to compile React into Javascript code. This should create a bundle.js file.
```bash
./node_modules/.bin/webpack
```


# Running the Application
Although you can run the application right now, not all functionality will work unless you 
complete the steps in the section below.

1. Run the script to start the server
```bash
./bin/run_flask
```
