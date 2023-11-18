# WebGi starter project

⚡️ Live Link: [http://drill-webgi-tutorial.vercel.app](http://drill-webgi-tutorial.vercel.app)

<a href="http://drill-webgi-tutorial.vercel.app"><img src="assets/images/preview.jpg" style="border: 1px solid black"></a>

A template for a vanilla(no ui-framework) project with webgi engine in typescript using parcel bundler.
## Course content
On Anderson Manchini's channel,who is a creative developer you can find a **step by step** video on how to use this source code to build your own pages.

- Chosing a model
- Use WEBGi editor to create images 
- Design the page using exported images from WEBGi
- Setup the WEBGi boilerplate into VSCODE
- Change the model
- Create the html and CSS
- Import GSAP and setup the library
- Create the ScrollTrigger animation for the camera
- Final adjustments

<a href="https://www.youtube.com/watch?v=mpTZbJPYZas"><img src="assets/images/cover.png" style="border: 1px solid black"></a>
[Click here](https://www.youtube.com/watch?v=mpTZbJPYZas) or on the image to visit the Free course on Youtube.  

About webgi: [https://webgi.xyz/](https://webgi.xyz/)

## Running
First install the dependencies:
```bash
npm install
```

To run the project in development mode:
```bash
npm start
```
Then navigate to [http://localhost:1234/index.html](http://localhost:1234/index.html) in a web browser to see the default scene in a viewer.

The assets are stored in the `assets` directory.

To build the project for production:
```bash
npm run build
```

## Updates
Check the [webgi manual](https://webgi.xyz/docs/manual/#sdk-links) for the latest version.
To use the different version:
* Update the version number in `package.json` file for both `webgi` and `@types/webgi`.
* Run `npm install` to update the dependencies.
* Delete `.cache` folder created by parcel bundler: `rm -rf .cache`
* Run `npm start` or `npm run build` to run or build the project.

## Documentation
For the latest version and documentation: [WebGi Docs](https://webgi.xyz/docs/).

## License 
For license and terms of use, see the [SDK License](https://webgi.xyz/docs/license).
