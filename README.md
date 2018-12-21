# API Project: File Metadata Microservice for freeCodeCamp

###    User stories:
1. I can submit a form that includes a file upload.
2. The from file input field  has the "name" attribute set to "upfile". We rely on this in testing.
3. When I submit something, I will receive the file name and size in bytes within the JSON response

### Usage :
* Go to the main page, and upload a file using the provided form.

### Hint:
* To handle the file uploading you should use the [multer](https://www.npmjs.com/package/multer) npm package.

#### Example output:
* {"name":"OReilly_JavaScript_The_Good_Parts_May_2008.pdf","type":"application/pdf","size":2193582}

### How to run the project :

1. Clone the repository :                  
     https://github.com/akshataw/filemetadata.git

2. Navigate to the repository:
     cd filemetadata

3. Install the dependencies :
     npm install     

4. Run the project :
     node server.js
