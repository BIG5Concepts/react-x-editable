# react-x-editable
 X-editable for react using [react-bootstrap](https://react-bootstrap.github.io/).		
 
## Quick Overview
react-x-editable allows text in place edit or click to edit functionality.

## Features :
 

* Support both `inline` and `popup` text edit mode (Form/Popover).
* Build in supported inputs are `Text`, `Textarea`, `Select`,`Checklist( check box list)`
* Supported `Custmizable` inputs where user can create own user defined inputs easily.

 ## Getting started	

 ```sh		
 npm install react-x-editable
 Or
 git clone https://github.com/ni3galave/react-x-editable.git		
 cd react-x-editable/		

 npm install		
 npm start		
 ```	

 Then open [http://localhost:8080/](http://localhost:8080/) to see demo examples.
 

## [Live Demo](https://jpr7xpv8yw.codesandbox.io/)


## Usage : 
Simple Text field example with popover edit mode.
 ```sh		
import Editable from 'react-x-editable';
..
...
render(){
    return (
      <Editable
        name="username"
        dataType="text"
        mode="popup"
        title="Please enter username"
      />

    );

}
```

## Documentation coming soon..	
