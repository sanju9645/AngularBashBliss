# AngularBashBliss
A collection of hilariously simple commands for angular dev giggles

>To check node version
```
node -v
```
>To check npm version
```
npm -v
```
## Installing angular
```
sudo npm install -g @angular/cli
npm update
```
> Checking Angular Version
```
ng version
```

## Creating new Project 
```
ng new <project name>
```

## To start a development server
```
ng serve
```

## To build an Angular application for production deployment
```
ng build --output-path docs --base-href angular-github-hosting
```
> 1 The ng build command is used in Angular to build an Angular application for production deployment.

> 2 '--output-path docs' This part of the command specifies the output path where the built application files will be placed. In this case, it's set to docs, which means the production build will be saved in a directory called docs

> 3 '--base-href angular-github-hosting' This part of the command specifies the base URL for the application. It is used when you intend to host your Angular application on a specific location within your domain. In this case, it's set to angular-github-hosting, which means the application will be accessible at a URL like http://yourdomain.com/angular-github-hosting/

> 4 This specific command is useful when you want to build your Angular application for deployment on platforms like GitHub Pages. By specifying --output-path docs, you configure Angular CLI to place the production build in the docs directory, and by setting --base-href to angular-github-hosting, you configure the base URL accordingly.

