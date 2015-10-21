paper-alert-dialog [![Bower version](https://badge.fury.io/bo/paper-alert-dialog.svg)](http://badge.fury.io/bo/paper-alert-dialog)
=========

`paper-alert-dialog` renders a material design dialog to alert users (Polymer 1.x).


## Usage

`bower install paper-alert-dialog`

```html
<paper-alert-dialog
  title="Congratulations"
  message="It works!"
  button="OK">
</paper-alert-dialog>
```


## Properties

Property    | Description                                    
----------- | -----------------------------------------------
**title**   | Title of the alert dialog
**message** | Message that is shown in the main part of the dialog
**button**  | Text of the confirm button
**opened**  | Flag if the dialog is currently opened


## Methods

Property | Description                                    
-------- | ----------------
**open** | Opens the dialog

There is no explicit close() method because the user is expected to click the confirm button.


## Continuous integration

[Travis-CI](https://travis-ci.org/Collaborne/paper-alert-dialog) [![Travis state](https://travis-ci.org/Collaborne/paper-alert-dialog.svg?branch=master)](https://travis-ci.org/Collaborne/paper-alert-dialog)


## License

    This software is licensed under the Apache 2 license, quoted below.

    Copyright 2011-2015 Collaborne B.V. <http://github.com/Collaborne/>

    Licensed under the Apache License, Version 2.0 (the "License"); you may not
    use this file except in compliance with the License. You may obtain a copy of
    the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS, WITHOUT
    WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the
    License for the specific language governing permissions and limitations under
    the License.
    
