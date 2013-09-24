Todo Application
=================
This is simple todo application/module/widget. _create item_ to start.

Use: Bootstrap.  
View: _create record_. Records List. Status Widget.  
View-mode: block inline

## _create record_ Widget
View: todo Field, add Button.

1. _input_ some text into the [todo Field (up to 36 symbols, No _watch_)]
2. _press_ Enter OR _click_ [add Button]

> _new_ [Item (_set_ [text] from [todo Field])] should be _add_ed to the [Items List].   
> And [todo] will be _clear_ed.

## Records List Widget
View: check Box, text Field (up to 36 symbols), X Button.

### _delete_

* _click_ on the [X Button]

> [Record] will be _delete`d from_ [Records List].

## Status Widget
View: Records _count_, _only_ check'ed Records _count_.


Application Language
=======================
Use: Html, JavaScript
## Widget
watch: Yes — update value from/to server, when modified.
## Storage
### Local Storage
### Express Storage

Html Language
===============

## Widget
View: "LABEL" OR [List of Item`s]
Template of Widget. See template folder of module.
_click_
## List Widget
View: "UL"
## Item List Widget
View: "LI"

## Button Widget
View: "BUTTON"

## Field Widget
Simple text field.
View: "INPUT"
value: Text
### _input_    
1. _click_ on the [Field]
2. _input_ some text into the [Field] 
3. _lost focus_

## Box Widget
Checkbox.
View: "INPUT[type=checkbox]"
checked: No
### _toggle_
* _click_ on the [Box]

> IF [checked]:
  _set_ No [checked].
  ELSE:
  _set_ [checked].
   
Language
==========
Step By Step language specification.  
The basic module, incapsulates programming language.

## Item
Basic type in SBS. The parent of all types.
value: Unknown
Use: (Language) List — List of dependencies.

### _new_
creates new Item.
### _set_
sets the value.

## Action
before steps: [List of Item and Action] — Events
do: [List of Item and Action] — 

## List
The collection of [Item]s.
### _delete [List.Item] from [List]_
### _only_
Filter list.

### Item
idx: 0
## Text
value: ""
## Number
value: 0
## Boolean
value: Yes
### dont
## No  Boolean
## Yes Boolean
## Unknown

JavaScript Language
=====================

## Item
```javascript
Object
```
### _new_
### _set_
## Action 
```javascript
Function
```      
## Text
```javascript
String
```    
## Number
```javascript
Number
``` 
## Boolean
```javascript
Boolean
```
### _dont_
```javascript
! this
```
## No Boolean
```javascript
false
``` 
## Yes Boolean
```javascript
true
```     
## Unknown
```javascript
undefined
```

## Versions

### ECMA3 JavaScript
### ECMA3 JavaScript
### ECMA5 JavaScript
### ECMA5proto JavaScript
### ECMA6 JavaScript
### V8 JavaScript
JavaScript, optimized for V8 engine (Google Chrome, NodeJS, Opera 15+).
