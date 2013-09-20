_Todo Application_
==================
This is simple todo application/module/widget. **add_Item_** to start.

Use: Widget(**don't** _watch_), _Bootstrap_.  
View: **addItem**. _Items List_. __Status Widget__.  
View-mode: block inline
    
## **add_Item_ Widget**
View: __todo Field__, __Add Button__.

1. **input** some text into the __todo Field (up to 36 symbols, No _watch_)__
2. **press** Enter OR **click** __Add Button__

> **new** _Item_ (**input** _text_ from __todo Field__) should be **add**ed to the _Items List_.   
> And __todo__ will be **clear**ed.

## _*Item*s List Widget_
View: _check Box_, _text Field (up to 36 symbols)_, __delete Button__.
### **delete**

1. **click** on the __delete Button__

> _Item_ will be **delete**d from _Items List_.

## __Status Widget__
View: _Items_ **count**, _Items_ (_complete_d **only**) **count** (IF only >0).


_Application Language_
=======================
Use: Html, JavaScript
## _Widget_
watch: Yes — update value from/to server, when modified.
## _Storage_
### _Local Storage_
### _Express Storage_

_Html Language_
===============

## _Widget_
View: "LABEL" OR _List of Item_
Template of Widget. See template folder of module.
**click**
## _List Widget_
View: "UL"
## _Item List Widget_
View: "LI"

## __Button Widget__
View: "BUTTON"

## _Field Widget_
Simple text field.
View: "INPUT"
_value_: Text
### **input**    
1. **click** on the _Field_
2. **input** some text into the _Field_ 
3. **lost focus**

## _Box Widget_
Checkbox.
View: "INPUT[type=checkbox]"
_checked_: No
### **toggle**
- **click** on the _Box_
IF _checked_:
**set** No _checked_.
ELSE:
**set** _checked_.
   
_Language_
==========
Step By Step language specification.  
The basic module, incapsulates programming language.

## _Item_
Basic type in SBS. The parent of all types.
value: Unknown
Use: (_Language_) _List_ — List of dependencies.

**new**
creates new Item.
**set**
sets the value.

## _Action_
before steps: _List of Item and Action_ — Events
do: _List of Item and Action_ — 

## _List_
The collection of _Item_s.
**delete _List.Item_ from _List_**
### _Item_
idx: 0
## _Text_
value: ""
## _Number_
value: 0
## _Boolean_
value: Yes
**don't**
## _No  Boolean_
## _Yes Boolean_
## _Unknown_

_JavaScript Language_
=====================

## _Item_
```javascript
Object
```
**new**
**set**
## _Action_ 
```javascript
Function
```      
## _Text_
```javascript
String
```    
## _Number_
```javascript
Number
``` 
## _Boolean_
```javascript
Boolean
```
**don't**
```javascript
! this
```
## _No Boolean_
```javascript
false
``` 
## _Yes Boolean_
```javascript
true
```     
## _Unknown_
```javascript
undefined
```

## __Versions__

### _ECMA3 JavaScript_
### _ECMA3 JavaScript_
### _ECMA5 JavaScript_
### _ECMA5proto JavaScript_
### _ECMA6 JavaScript_
### _V8 JavaScript_
JavaScript, optimized for V8 engine (Google Chrome, NodeJS, Opera 15+).
