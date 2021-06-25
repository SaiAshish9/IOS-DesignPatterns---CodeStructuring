# MVC vs MVP vs MVVM

```
In MVC, View sends the event to controller which makes request to the model and it in turns returns back data
Security issues may take place as view has access to the entire model data
Spring MVC , Swift

In MVP, the role of controller is replaced with presenter . Presenter is at the same level as views , listening to
events from both the view and the model & mediating between between.
Android MVP

MVVM consequently allows us to create view specific subsets of a model , which can contain state & logic information, 
avoiding the need to expose the entire model to a view . View can bind to properties on view model which is turn data 
conatined in models to the view
Vue.js Flutter
```
