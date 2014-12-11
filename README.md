# CleanFileName

This is a node.js command line utility that cleanup filenames with url encode characters.

## Usage
First clone repository and access the new folder

    $ git clone <repository> && cd $_

then install necessary modules

    $ npm install

and just run with the name to clean in argument

    $ ./index.js <filename>

Run the test with

    $ gulp test

## ToDo

- [ ] Add a command line name
- [X] ~~Add test~~
- [ ] Add new function to normalize filename for the web
- [ ] Transform in Uppercase characters to decode
- [ ] Add parameter to get clipboard content and add to after
- [ ] Improve help command
- [X] ~~Use Encode/decode URI component~~
