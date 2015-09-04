# ng-file-model
----
[![Bower version](https://badge.fury.io/bo/ng-file-model.svg)](http://badge.fury.io/bo/ng-file-model)
----
Angular File Model is a directive for angularjs to help you make a model for input file and you can send it to sever for next step.

## Installation

`> bower install ng-file-model --save`

## Usage
on application :
`angular.module("myApp", ["ng-file-model"])`

on html :
`<input type="file" ng-file-model="testFile" />`

Result :


    {
        "lastModified": 1438583972000,
        "lastModifiedDate": "2015-08-03T06:39:32.000Z",
        "name": "gitignore_global.txt",
        "size": 236,
        "type": "text/plain",
        "data": "data:text/plain;base64,DQojaWdub3JlIHRodW1ibmFpbHMgY3JlYXRlZCBieSB3aW5kb3dz…xoDQoqLmJhaw0KKi5jYWNoZQ0KKi5pbGsNCioubG9nDQoqLmRsbA0KKi5saWINCiouc2JyDQo="
    }
    




----
Created By Mistral Works | 2015