# Smart Brain Face Detection App (Backend Only)
> A face-detection app that takes image URLs and uses Clarifai's face recognition API to highlight faces in those images. To use the app, the user must first register. The app keeps track of every user's submissions and shows the user's total number of submissions upon successful login.

## Features
* Face detection via image URL
* User registration and authentication
* Image submission tracker for every user

## Install dependencies
```
# Clone the repo, then install dependencies in root folder
npm install
```
* You must add your own API key in the controllers/image.js file to connect to Clarifai API. Alternatively, create an .env file and store it there.
* You must add your own database credentials to server.js. Alternatively, create an .env file and store it there.
* Make sure you use postgreSQL instead of mySQL for this code base.
* :exclamation: The front-end code is in a separate repo (https://github.com/lenspira/smart-brain) - make sure to clone it as well to run the app.

## Environment Variables
Create a .env file in then root and add the following:

```
DATABASE_URL = your postgreSQL database url
API_CLARIFAI = your paypal client id
```

## Run
```
# Run frontend
npm start
```

## Build & Deploy
```
# Create backend prod build
npm build
```

## Contributing
If you'd like to contribute, please fork the repository and use a feature branch. Pull requests are warmly welcome.

## Links
* Project homepage: https://smart-brain-lenspira.herokuapp.com/
* Front-end repository: https://github.com/lenspira/smart-brain
* Back-end repository: https://github.com/lenspira/smart-brain-api
* Issue tracker: https://github.com/lenspira/smart-brain-api/issues

## License
The code in this project is licensed under MIT license.

Copyright (c) 2021 Leonard DeMarco.

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
