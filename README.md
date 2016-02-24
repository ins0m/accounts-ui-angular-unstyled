# accounts-ui-angular-unstyled
AngularJS wrapper for Meteor's Account-UI-unstyled package

# How to use?
- Make sure you have the `angular` package in your root account.
- Add the package:
`meteor add ins0m:accounts-ui-angular-unstyled`
- Add a dependency on your AngularJS module. For example:
```javascript
angular.module('myApp', ['angular-meteor', 'accounts.ui']);
```

- Use it in your app, for example:
```html
<login-buttons></login-buttons>
```
