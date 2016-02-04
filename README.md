# ng-password-meter
An easy to implement password strength meter originally developed for the 
[Lifekees Password Manager](https://www.lifekees.com/)

Based on:

*	[https://github.com/subarroca/ng-password-strength][strength]
*	[http://blog.brunoscopelliti.com/angularjs-directive-to-test-the-strength-of-a-password][bruno]
*	[http://www.passwordmeter.com][meter]

  [strength]: https://github.com/subarroca/ng-password-strength 
  [bruno]: http://blog.brunoscopelliti.com/angularjs-directive-to-test-the-strength-of-a-password
  [meter]: http://www.passwordmeter.com

## Usage
1. Add the following in your web page:

  ```html
  <script src="ng-password-meter/ng-password-meter.js"></script>
  <script src="ng-password-meter/ng-password-meter.css"></script>
  ```

2. Set `ng-password-meter` as a dependency in your module
  ```javascript
  var myapp = angular.module('myapp', ['ngPasswordMeter'])
  ```

4. Add ng-password-meter to your html at the appropriote position and specify the model to measure. Example:
  ```html
  <ng-password-meter password="pass"></ng-password-meter>
  ```

## Dependencies
None

