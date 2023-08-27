# Image Reader

This project build on Tensorflow models(coco-ssd), express framework to host server, so that we can connect API.

1. Download project files into your local.
2. Run 'npm i' to install require packages.
3. Run 'npm start' or 'npm run dev'(for nodemon) to launch server.
4. Create .env file with property PORT, else server will launch on port- 4200.
5. Post an form data with image file, at path http://localhost:4200/predict.
6. Response json will receive with output data from predicted percentage value from models.

Credit: https://betterprogramming.pub/node-js-implementation-of-image-recognition-using-tensorflow-and-express-js-b006f5609415
