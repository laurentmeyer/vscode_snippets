# vscode_snippets
I'm a noob, please help me enhance this!

To install the snippet on OSX, open `Code > Preferences > User Snippets` , then select the language of your choice and copy the content of the relevant json file.

#### Good to know
To delete with multi-cursor on, use `Ctrl-Del`.

## CPP snippets
**class_hpp** is to be triggered in a header file named `<Name>Class.hpp` (ex: `SampleClass.hpp`). Then you need to fill the type, capitalized name and lowercase name (if you know a trick to enter the name just once, please let me know). The lower half of the file is to be cut and pasted in the associated cpp file.

**get_set_value** and **get_set_reference** create automatic getters and setters, depending on whether you need to pass a value or a reference. It is better triggered in the private section of the class. Then cut-paste the relevant definitions in the cpp file.