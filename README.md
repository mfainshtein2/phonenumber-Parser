# phonenumber-Parser Release 1
A api server built to use for parsing phone number according from a text file. To do this we are using libphonenumber which was created by google.

## Prerequisites
This project is uses Node.js and Express
* [Node.js](https://nodejs.org/en/) Windows Version

To setup express you must have installed Node.js
```
$ npm install express --save
```
### Setup

1. Clone the repository:
```
git clone https://github.com/TheKinshu/phonenumber-Parser.git
```

2. Install the dependencies:
```
npm install
```

3. Run Applications:
```
$ node app
or
$ nodemon app
```

### How to use

## Get
```
localhost:9000/api/phonenumbers/parse/text/{TEXT_TO_PARSE}
```

## Post with text file
For POST request you will need to enter the following url.
```
localhost:9000/api/phonenumbers/parse/file
```
This here will bring you to a html file that will allow you to upload a text file.

## Post with PDF file
For POST request you will need to enter the following url.
```
localhost:9000/api/phonenumbers/parse/pdf
```
This here will bring you to a html pdf that will allow you to upload a pdf file.


