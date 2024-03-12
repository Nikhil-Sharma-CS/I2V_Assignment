# Test Repo i2v

This repository contains a DotNet 5 web API project and an Angular 12 application project. This is a test repo for correctly setting up a project with a DotNet API and an Angular application, and basics of both technologies.


## Prerequisites

Before you begin, make sure you have the following installed on your machine:

- .Net 5 SDK
- Node.js and npm
- Angular CLI
- Additionally you need to have proper versions of these techs.

## Setting up the DotNet API

1. Open a terminal and navigate to the `Test_DotNet` directory
2. Either run the command `dotnet run` or use Visual Studio to run the API

The API should now be running at `http://localhost:5000/`

## Setting up the Angular application

1. Open a terminal and navigate to the `TestAngular` directory
2. Run the command `npm install` to install the dependencies
3. Run the command `ng serve` to start the Angular application

The application should now be running at `http://localhost:4200/`

## Testing the solution
If you are unable to set up the angular application, you can use the tools like postman or curl to test the API.

1. Open a browser and navigate to `http://localhost:4200/`, the Angular application should be displayed, Navigate to `Hash` tab.
2. Enter your `first name` in the input field on the Angular application
3. Click the `Generate Hash` button. If the dotnet API is running correctly, and the logic is correct, the hash value should be displayed below the button.
4. Ex: If you enter `nikhil` in the input field, the hash value should be `D61D2A3588DC176C0476EC4BCE6BE1FBCCCFA99949F223591DEF2A2D13617BC0`.
5. The hash value for the name should be displayed below the button. Copy the hash value.

### Paste the hash value Here in the readme file: 

D61D2A3588DC176C0476EC4BCE6BE1FBCCCFA99949F223591DEF2A2D13617BC0

## Troubleshooting

If you run into issues while setting up the solution, try the following:

- Make sure you have the latest versions of .Net 5 SDK, Node.js, and npm installed, appropriate Angular version.
- Check that the API is running and accessible at `http://localhost:5000/`
- If you get a CORS error, make sure that the correct origins are allowed in the API

