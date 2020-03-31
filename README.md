![Image description](https://i1.faceprep.in/ProGrad/face-logo-resized.png)

# ProGrad Lab | ProGrad Contact List
## Introduction

Over here at the Prograd Community, we have found that students like to have a way to keep track of the contacts they make during their ProGrad Journey for furture collaborations, and may be sometimes to reminisce about the good old times.

For this, we are going to create a contact management application with Angular.

You can find the starter code in the starter code folder of this github repo.

## Learning Goals

After this lesson, you will be able to:

- Create a static Angular application with Angular CLI.
- Build an Angular application with multiple component.
- You will get to know array of objects, interfaces, classes.

## Requirements

- Fork this repo.
- Clone this repo.

## Submission

Upon completion, run the following commands:

```bash
$ git add .
$ git commit -m "done"
$ git push origin master
```

Navigate to your repo and create a pull request from your master branch to the original repository's master branch. In the pull request name, add your ProGrad id, name, and last name separated by a dash "-".

## Deliverables

You need to generate the starter code and fill it with the necessary code to satisfy the requirements described below.

## Starter Code

To generate the starter code, follow the steps given below

- To create a new application,
    - Open your ubuntu or cmd terminal and execute the following command
      - ```ng new app-name```
      - for example, ng new super-wars
    - To create a new component, execute the command 
      - ``` ng generate component component-name```
      - example, ng generate component contacts
      
## How to run

- To run the project go to your ubuntu terminal or VScode editor
    - open the ubuntu or cmd terminal or inside the vscode editor
    - run the command following command
    - ```ng serve --open or ng serve -o```

## Instructions
Once you clone your project, 
```cd lab-angular-prograd-contacts
   run the below command
   npm install --save-dev @angular-devkit/build-angular
```

## Progression 1: Display Contacts

Let's take a look at the starter code.

There is a file with fake contacts called contact.ts and the collection of contacts is being exposed to the template in a variable called `contacts`.

Using `*ngFor`, display the `name`, `email`, `phoneNumber`, and `image` of each contact.

## Progression 2: Add New Contacts

Currently, there's a form wired up to an `[(ngModel)]` called `newContact`.

When a user clicks the button below this form, it's *supposed* to be calling a function called `addContact`. Look carefully at the following line and see if you can detect the bug:

```html
<!-- contact-list.component.html -->
<button (click)="addContact">Submit New Contact</button>
```

Then, finish the function inside of the component that adds the contact to the list of contacts:

```typescript
addContact(){
  // add contact to contacts list
  // clear inputs
}
```

## Progression 3: Style Them

Unfortunately, our contacts list isn't really ready. May be we could style it a little before to finish off.

Remember these rules while styling: you can add a global stylesheet in your `index.html` and apply component specific styles in the `.component.css` files.

Happy Coding ProGrad ❤️!
