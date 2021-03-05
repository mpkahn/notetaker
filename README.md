# Express.js: Note Taker

## Description 

Express note taker is a node.js note taking application that allows notes to be stored, received, and deleted. 
![landing page](Assets/images/img1.jpg)


## Installation

* Navigate to https://github.com/mpkahn/notetaker and clone repository to access app.js file located in Develop folder.
* Once on local machine:
* Install npm (npm i) and (if needed) npm install express.
* In gitbash, run node server.js, and once you see local host is running, visit in your browser: http://localhost:3001/

## Usage 

*  Utilize local host above of visit heroku hosted app - https://thawing-thicket-51345.herokuapp.com/notes
*  Click "get started" 
*  Enter notes in empty fields and hit the disk icon to save
![notes page](Assets/images/img2.jpg)


## Errors

Unfortunately I was unable to get the notes to properly display on the HTML page. They do seem to copy to the db.json, but I have not routed everything correctly.
![example note](Assets/images/img3.jpg)
![example db file](Assets/images/img4.jpg)


## Credits

node.js and its documentation on file systems https://nodejs.org/api/fs.html & https://nodejs.org/en/knowledge/file-system/how-to-write-files-in-nodejs/
npm js, 
Express.js 


## License

MIT License

Copyright (c) [2021] [Michael Kahn]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.