## Azure Pipeline Demo Website for Webmontag Kassel

Have look at the `azure-pipelines.yml` file.

You can access the Azure DevOps Project at:
https://dev.azure.com/lukaswoehrl/webmontag-kassel-azure-pipeline-demo/

The website this gets deployed to can be accessed via:
https://webmontag-kassel-lx.azurewebsites.net/

### The build pipeline which gets triggered on each push to GitHub
![Build Pipeline](docs/build_pipeline.png?raw=true)

### The release pipeline overview of the lastest releases
![Release Pipeline Overview](docs/release_pipeline.png?raw=true)

### The release pipeline with the concrete artefacts and stages
![Release Pipeline](docs/release_pipeline2.png?raw=true )

### The toggle you can set, to enable a continuous deployment on each successful build
![Continous Deployment](docs/release_pipeline_continous.png?raw=true)

---

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.<br>
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br>
You will also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.<br>
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.<br>
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.<br>
Your app is ready to be deployed!
