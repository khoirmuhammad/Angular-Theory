# CHAPTER 1 - BASIC
1. Angular is component-based framework for building web structure, and for buildinf single page application (only have single page, the content changed by replacing component. It usually doesn't need reload page when redirect to another component

2. NPM : Node package manager is online repository that we able to get plenty free libraries that can be used in angular/node project

3. Typescript provids type system, class, interface, enums, generics etc. But browser unable to execute the typescript. Thus, angukar will convert typescript to javascript. Typescript : (strongly typed language, OOP freidnly, detect error at compile time)
- strongly typed : when we declare variable in javascrio, we don't need set the data type of variable. However in typescript we have to declare its datatype
- compile time detection error : For instance, we have one string varibale. In the next code in case we change the value to integer, then compiler will consider as an error
- OOP friendly : it recognize interface, inheritance, instance object etc
- Superset of javascript : it means the way (method) that can be written in javascript, it's also able to be written in typescript

# CHAPTER 2 - COMPONENT & MODULE
1. Component : UI block that build a angular application such as login component, menu component, sidebar component etc. Component consist of component files like css, html, typescript and unit test. Typescript component will manage / link all of component files

2. Selector component : unique identity having by each component. It will be called on html file in order to change the component with other component

3. Module : Group of components, directives, pipes, services that relate to the application

4. How angular works :
- Once URL is typed on the browser, then it will redirect to index.htm (single page apps)
- index.html will call main.ts
- call app.Module.ts
- th last one is calling aap.Component.ts
