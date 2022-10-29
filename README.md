# **scada**


## **Installation**

### **Prerequisites**


#### **Mongodb**


- Download and install mongodb here:
[https://www.mongodb.com/try/download/community](https://www.mongodb.com/try/download/community)


#### **Node.js**


- Download and install node here:
[https://nodejs.org/en/download/](https://nodejs.org/en/download/)

#### **Python**

- This project uses python 3.8
Download and install python here:
[https://www.python.org/downloads/](https://www.python.org/downloads/)

    -- Alternatively, you can install pyenv to manage different version of python. Installation instructions can be found here: 
    [https://github.com/pyenv/pyenv#installation](https://github.com/pyenv/pyenv#installation)


- pip: installation instructions for pip can be found here:
  [https://pip.pypa.io/en/stable/installation/](https://pip.pypa.io/en/stable/installation/)
    

- pipenv: installation instructions for pipenv can be found here:
    [https://pipenv.pypa.io/en/latest/install/](https://pipenv.pypa.io/en/latest/install/)

#### **Angular CLI**

- Install angular CLI tools:
[https://angular.io/guide/setup-local](https://angular.io/guide/setup-local)


### **Flask Back-end setup**

1. In a terminal window, navigate to the Lumen-Server directory.

2. To setup the virtual environment, run the command:
    ```sh
    pipenv install
    ```
3. Activate the virtual environment: 
    ```sh
    pipenv shell
    ```

4. Start the app running on port 5000:
```sh
python3 app.py 5000 test
```
- The console should indicate that the development server is running on the local host on port 5000.

### **Angular Front-end setup**
1. In the terminal window, navigate to the Lumen-Client directory.
2. Install the required node modules with npm:
    ```sh
    npm install
    ```
3. Run the angular development server:
   ```sh
   ng serve --open
   ```
- A new browser window should open up with the address {localhost}:4200
