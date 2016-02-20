react-runtime
====

#Overall
This repo is used to build ReactJS JSX file to Javascript file. 

#How to use it
 - Pull this image from `yanqiw/react-runtime`
 - Go to your project static file folder, such as `public`, `static` or something else... Be sure that your `app.js` under 'js' folder in your running container path.
 - run `docker run -v "$PWD":/runtime/src yanqiw/react-runtime`

The runtime will watching the app.js file under `js` folder, and build to `bundle.js` file in your static file folder.
