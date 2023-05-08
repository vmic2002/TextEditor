# TextEditor

## Contributor
[Victor Micha](https://github.com/vmic2002)

## About
TextEditor coded in Java using the Eclipse IDE. Using [Stanford's acm library](https://cs.stanford.edu/people/eroberts/jtf/), more specifically the [acm.graphics package](https://cs.stanford.edu/people/eroberts/jtf/rationale/GraphicsPackage.html).

This is an ongoing project from October 2021 - Now

Supports importing text file from your computer into this TextEditor. Can also save from this TextEditor to a text file in your computer.

There are four buttons on the right side of the editor to import a file, save to a file, scroll up, and scroll down.

You could technically use this TextEditor to modify its own source code!

## Project Setup
The java files are in the `src` folder. If you open this project in Eclipse, modify the code and compile, the `.class` files in the `bin` folder will be updated.

These `.class` files are the ones being used to run the TextEditor from the command line.

## How to use this TextEditor
1. Open up your Terminal App.
2. Clone this repo by running:
```bash
git clone https://github.com/vmic2002/TextEditor.git
```
3. Run
```bash
cd TextEditor
./openTextEditor.sh
```
The openTextEditor.sh file is a bash script that will run the TextEditor from the command line.

<img width="1000" alt="Screenshot 2023-05-07 at 8 19 39 PM" src="https://user-images.githubusercontent.com/89990471/236726381-f209cb42-87ba-4a73-bf68-219489390415.png">
