# 'HashLocationStrategy'in angular 10
 
HashLocationStrategy in angular is one of the solution by which one can resolve 
routing issue for any angular components or modules after performing ng build.

For any angular app higher than version 2 the following changes can be done as routing solution:
- Open app.module.ts file and add the following:
1. import { HashLocationStrategy, LocationStrategy } from '@angular/common';
2. providers: [{provide: LocationStrategy, useClass: HashLocationStrategy}] in @NgModule decorator.

 
