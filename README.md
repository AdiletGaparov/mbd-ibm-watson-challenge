## Configuring the application

1. Import IBM Watson skill to your IBM Watson assistant instance. JSON file is located here:

    `<project_root>/skill-json-file/skill-teamD.json`

2. In the application folder, copy the *.env.example* file and create a file called *.env*

    ```
    cp .env.example .env
    ```

3. Open the *.env* file and update the credentials that you can take from IBM Watson (cloud.ibm.com). 

## Running locally

1. Install the dependencies

    ```
    npm install
    ```

1. Run the application

    ```
    npm start
    ```

1. View the application in a browser at `localhost:3000`
