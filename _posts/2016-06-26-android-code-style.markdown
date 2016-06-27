---
published: false
title: Android  Code Style
layout: post
---
# Android Code Convection 

## Introduction 


Code  convection is very important for developers. It helps developers to write readable, maintainable, reusable and expendable code that maintain long-term projects and new developers can easily understand  the  project. Code convection is important in code documentation. It manages the risk running project. Let us start with the code convection which is using in an android programming language. Android SDK is designed in java programming  language.

### Variable name 

The variable name should be meaningful and sound good. It should be in camalCase. non-public and nonstatic variable should start with lower letter m.  where static and public variable start with lower letter s. 

### Constant name

It should be upper letter and  separated by underscores. a constant name should be meaningful and sounds good.


### Method name

The method name should in camelcase , use  underscore what is begin tested. Like isInternet_available(). 

### UI and Other UI component 

UI is related to  its class. so that class name and UI name should be same. Like for MainActivity UI component name should  be main_activity.  a new word  should  be separated by an underscore.

UI component like Textview, it starts with their respective class  than name  and end with their type. like main_activity_name_tv

## Comments 
### Begining comment 
 Begining comment should contain developer name,version information and copywrite. Like 

### Method comment 

Method comment should start with behavior, parameter and return type  information. 

## Import statements 

In android import order is like this 

1. Android imports 
2. Import from third parties 
3. java and javax

## Use space  Indentation 

## Use standard brace style

## Use standard java annotation 

use proper annotation, like @override , @Dprecated etc .  If there are multi annotation or parameterized annotation, they each should be listed one-per-line in alphabetical order. 

## Acronyms as world 

XMLHTTPRequest is wrong, it should be XmlHttpRequest. 

## Use   Todo Comments 

Use Todo comments for code that is temporary , a short term solution or good enough but not perfect. 


For future Todo 
write particular date of change  or a very specific event.