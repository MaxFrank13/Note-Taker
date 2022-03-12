# Note-Taker

## Description

This is an application for taking notes and having them saved permanently. A `.json` file is used to persistently store the data. Express.js is used to route the application.

[Note Taker](https://young-springs-38790.herokuapp.com/)

![Note-Taker](https://github.com/MaxFrank13/Note-Taker/blob/main/public/assets/app-photo.png)

## Installation

You'll need node installed if you want to clone the application. From there, run `npm i` or `npm install`. The only dependencies used in this application are Express and UUID. After installation is complete, run `node server.js` to boot up the server. You will then be able to access the application at PORT 3001. This can be changed in the server.js file.

## Usage

Click the 'Get Started' button on the homepage. You will be presented with a blank page with the option to fill in two text inputs. One for 'Note Title' and the other for 'Note Text'. Once both fields have been typed into, a save icon will appear in the top right corner of the screen. Clicking this save button will save your inputs to a note. Each saved note is listed on the left side of the screen. Any previously saved notes can be accessed by clicking on them. Each item also has its own trash can icon which can be clicked to delete it from the list.
