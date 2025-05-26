# Task Management App
* add tasks for users
* mark tasks as complete
* display list of tasks for each user

<img width="1137" alt="Screenshot 2025-05-27 at 1 04 59 AM" src="https://github.com/user-attachments/assets/f5817e51-3159-4a14-b2e4-82f4c00e2e62" />
<img width="1178" alt="Screenshot 2025-05-27 at 1 05 09 AM" src="https://github.com/user-attachments/assets/a175a190-8cbd-4218-8d64-82d385286f42" />

# This Project includes Angular Essentials

Components: Core of every Angular app. They're just classes decorated with @Component, and they control how stuff shows up and behaves on the screen.

Communication Between Components:
  * Use @Input() to pass data into a component (usually from a parent).
  * Use @Output() + EventEmitter to send data out (from child to parent). Super useful for interaction.

Data Binding:
  * String interpolation ({{ }}) – great for quick display.
  * Property binding ([prop]) – dynamic values in templates.
  * Event binding ((event)) – capture things like clicks.
  * Two-way binding ([(ngModel)]) – especially helpful for forms.

Change Detection:
  * Angular watches for changes with zone.js.
  * Angular 16 added Signals – they're a more efficient way to track state changes. Worth digging deeper here.

Conditional Rendering:
  * @if in Angular 17 – cleaner and easier to read.
  * Older versions still use *ngIf.

Array Iteration:
  * @for is the new *ngFor. Makes loops feel more modern and readable.

Dynamic Styling & Content Projection:
  * Can bind CSS classes dynamically.
  * ng-content lets you slot in content – super handy for reusable components.
  * Pipes = great for formatting stuff (dates, currencies, etc.).

Form Handling:
  * Use ngSubmit to handle form logic in Angular (no default HTTP requests getting in the way).

Services & DI:
  * Keep business logic out of components.
  * Create a Service (@Injectable) and inject it where needed. Keeps things clean and modular.
 
# Angular Project Setup
1. Install the Angular CLI
- need node.js and npm first (node.js v20 and npm v10 as per project)
  
`npm install -g @angular/cli`

2. navigate to the folder you want
`ng new first-angular-app(name)`

3. start local dev server
`npm start`

4. Make sure to
`npm install` - have the packages needed

# Create New Angular Component (CLI Commands)

Basic Component Creation: 
`ng generate component component-name` 

or shorthand:
`ng g c component-name`

Skip Test File: 
`ng g c header --skip-tests`

Generate in a Specific Folder: 
`ng g c components/header`

Use Inline Styles and Templates: 
`ng g c header --inline-style --inline-template`

# Essentials

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 17.1.2.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The application will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.
