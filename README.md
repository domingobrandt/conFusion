# Ionic
ConFusion Docs 

   * Setting up the Ionic Framework
        To install the Ionic framework's command line interface (CLI) and Cordova, at the prompt type:

                $ npm install cordova ionic -g
                
If you are installing on OSX or Linux, make sure to precede with sudo.

   * Creating an Ionic Project
    Go to a convenient location on your computer and create a folder named Ionic. Then move to that folder in the command window.
    To scaffold out a new Ionic project, type the following at the command prompt:

                $ ionic start conFusion sidemenu
             
    * Shared folder in the src: recibe the data json-server is up and running.


## To see the resulting project in your browser, type the following at the command prompt:
         ionic serve --lab
    Run ionic serve 

##Error
* “has no exported member 'Observable'”

 Run:
   
        npm install rxjs-compat --save    

* "Cannot find module '@angular/http'"

        npm i @angular/http

    to install. Should fix it.

* ERROR in src/app/home/home.page.ts:2:31 - error TS2307: Cannot find module 'ionic-angular'.
[ng] 2 import { NavController } from 'ionic-angular';
     change:
     import { NavController } from 'ionic-angular';
     for 
     import { NavController } from '@ionic/angular';
