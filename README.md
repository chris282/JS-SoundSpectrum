
Welcome to my Sound Spectrum project, based on Angular 7 and Three.js !
Help me by contributing to this project, as I am learning Angular an javascript. I want to make this project as good as my Java sound spectrum project (available here : https://github.com/chris282/Java-SoundSpectrum ) :)

# First Run :
Run "npm install" inside this project folder to install all dependencies.

npm install

To build the project :

ng build

To launch the project :

ng serve

Open it on your browser : http://localhost:4200/ 

## RoadMap

- The 3D scene is working.
- The FFT algorithm is in place, I have to test it.

So here are the next steps TODO : 
- Get the audio stream of the computer or microphone.
- Put the audio stream to the DFT (FFT) transform
- Put the FFT output values into an array
- Display raw data from the FFT output values (with text).
- Display the FFT output values in 2D with simple visualization
- Display the FFT output values in 3D with a nice visualization

## History

This project was initiated from ng-three-template by JohnnyDevNull ( https://github.com/JohnnyDevNull/ng-three-template ) generated with [Angular CLI](https://github.com/angular/angular-cli) and is designed as a basic template for [ThreeJS](https://threejs.org/) combined with [Angular](https://angular.io/) and [Bootstrap](https://getbootstrap.com/) in Version 4.x

The project is setup to use global [SCSS](https://sass-lang.com/) only and [ViewEncapsulation.None](https://angular.io/api/core/ViewEncapsulation).

Feel free to do anything you want with this template.

## Three Links

* Three Extensions: https://github.com/Itee/three-full
* Three-Full Types: https://discourse.threejs.org/t/angular-threejs/2739/7

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `-prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).
