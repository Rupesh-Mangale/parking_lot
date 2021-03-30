# parking_lot
How to run?
This can be run in two modes:

Interactive Mode: An interactive terminal based shell where commands can be typed in to perform different actions.

File Mode: It accepts a filename as a parameter at the terminal and read the commands from that file.


Proceed to the steps below only if you've Node.js installed. If not, please refer pre requisites section.

For Interactive Mode
Open terminal and navigate (cd) to this folder and type the following commands:

1. npm install
2. npm start
For File Mode
Open terminal and type node src/index.js data/input.txt.

node src/index.js <path_to_file.txt>

example = node src/index.js data/file_inputs.txt


Note: You can find a few sample input files inside data/ folder.

Explained
STEP 1: npm install or npm i will download all the dependencies defined in package.json file and generate a node_modules/ folder with the installed modules. Learn more here.

STEP 2: npm start or npm run start will start the application. It is equivalent to node src/index.js


Modules - OOPS Approach

Test Scripts
Tests are written using Mocha

npm run test-unit : Run unit tests only (Tests for functions in Parking Class)

Unit tests are written for the methods of ParkingLot class.



