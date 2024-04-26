# Starting With Project

## Create the necessary Folder
- app
- components
- models
- publi/assets
- styles (add globals.css file and add the styling in that)

## Create files in app folder
- layout.jsx
- page.jsx

### Import Files
- Importing files: '@folder_in_root_directory/filename'
- example: '@styles/globals.css'
- remove / from path in jsconfig.js


## Connect to DB
- make utils folder in root directory
- create database.js file and setup mongoDB connection

## Create auth api
- Create Userr Model
- go to console.cloud.google.com
- create project
- create credential (OAuth)
- create session, signIn function 

### Go to openssl terminal (online) and run command to generate random secret which will be helpful for encryption/decryption 

## Prompt APIs
- create prompt model

### /prompt
- Method : GET
- To List all the available prompts

### /prompt/new
- Method : POST
- Create a new prompt
- Request Body
```json
{
    userId: "user098239489220",
    prompt: "Create a simple Calculator in React.js",
    tag: "coding"
}
```

### /prompt/[id]
1. GET METHOD
- To get the details of a particular user along with all the prompts by that particular user

2. PATCH METHOD
- Update the Prompt or Tag of the prompt
- Request Body
```json
{
    prompt: "Create a simple Calculator in React.js, use Chakra ui and it should be fully responsive",
    tag: "coding"
}
```

3. DELETE METHOD
- Delete the prompt

