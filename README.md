# Apress Source Code

This repository accompanies [*Building Offline Applications With Angular*](https://link.springer.com/book/10.1007/978-1-4842-7930-4) by V Keerti Kotaru (Apress, 2022).

[comment]: #cover
![Cover image](%isbn%.jpg)

Download the files as a zip using the green button, or clone the repository to your machine using Git.
## Web Arcade

An imaginary online gaming arcade. it is a sample use case for the book on Building Offline Applications with Angular.

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 12.0.1.

## Run the sample as a PWA (Progressive Web App)

Use the following command to run the application as a PWA

`npm run start-pwa`

(or)

`yarn start-pwa`

**Note:** The code sample uses 
1. Http Server for running a developer class web server hosting the Angular application
2. Express based HTTP server providing mock respones

## Run the code samples with Webpack (default Angular Dev Server)
Use the following command to run the application with the default Angular Dev Server

`npm run start`

(or)

`yarn start`

## Additional scripts and commands

Run the following scripts with `npm run [script-name]` or yarn `[script name]`

| Script Name                  | Purpose                                                                      |
|------------------------------|------------------------------------------------------------------------------|
| start-api                    | Runs Node.js based backend server                                            |
| start-http-server            | Performs production build on the Angular application and runs on Http-Server |
| start-http-server-no-install | Quick way to restart Http-server. Does not perform build or install          |

### Connect with the author
Twitter [@keertikotaru](https://twitter.com/keertikotaru) | [Code Venkey](https://codevenkey.com) 

## Releases

Release v1.0 corresponds to the code in the published book, without corrections or updates.

## Contributions

See the file Contributing.md for more information on how you can contribute to this repository.