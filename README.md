# AngularJS Theory

This repository covers the theory of AngularJS. It will take you step by step through the fundamentals of AngularJS to help understand with clarity as quickly and efficiently as possible. 

## Table of Contents

1. [Expressions]
2. [Modules]
3. [Directives]
4. [Model]
5. [Data Binding]
6. [Controllers]
7. [Scope]
8. [Filters]
9. [Services]
10. [$http]
11. [DOM]
12. [Events]
13. [Forms]
14. [API]
15. [Includes]

## Expressions
Angular expressions are much like **JavaScript expressions**: They can contain *literals, operators,* and *variables*. Expressions can be written inside double braces like `{{...}}`

## Modules
A module is a collection of *services*, *directives*, *controllers*, *filters*, and configuration information. AngularJS module is created by using `angular.module("moduleName", [])` function by passing the **module name** and specifying a **list of dependencies** if there's any. The `"moduleName"` parameter refers to an HTML element `ng-app="moduleName"` to initialize the application.

## Directives
Directives are markers on a DOM element (such as an *attribute*, *element name*, *comment* or CSS *class*) that tell AngularJS's HTML compiler (`$compile`) to **attach** a specified **behavior** to that DOM element (e.g. via *event listeners*), or even to transform the DOM element and its children. Angular directives are extended HTML attributes with the prefix `ng-*`, like `ngBind`, `ngModel`, and `ngClass`. To determine which **elements** match which **directives**, Angular typically refer to directives by their **case-sensitive camelCase** normalized name (e.g. `ngModel`). However, since HTML is **case-insensitive**, we refer to directives in the DOM by **lower-case** forms, typically using **dash-delimited** attributes on DOM elements (e.g. `ng-model`).

## Controllers
A controller is a JavaScript Object, created by a standard JavaScript **object constructor** that **control the data** of AngularJS applications. The controller is defined by `ng-controller="XController"` attribute (directive), the `XController` value is a JavaScript function.
