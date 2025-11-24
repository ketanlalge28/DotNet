## Q1) Difference Between Angular and AngularJS

| Feature                  | **AngularJS**                             | **Angular**                                          |
| ------------------------ | ----------------------------------------- | ---------------------------------------------------- |
| **Released**             | 2010                                      | 2016+                                                |
| **Language**             | JavaScript                                | TypeScript                                           |
| **Architecture**         | MVC (Model–View–Controller)               | Component-Based                                      |
| **Mobile Support**       | Not good                                  | Excellent (designed for mobile)                      |
| **Performance**          | Slow (due to digest cycle)                | Very Fast (Ahead-of-Time compilation)                |
| **Data Binding**         | Two-Way only                              | One-way + Two-way (flexible)                         |
| **DOM Handling**         | Real DOM                                  | Virtual DOM (Improved rendering)                     |
| **Dependency Injection** | Basic                                     | Advanced & powerful DI                               |
| **Routing**              | Limited                                   | Advanced, modular routing                            |
| **Structure**            | Less structured, difficult for large apps | Highly structured, perfect for large enterprise apps |
| **Support**              | No longer supported by Google             | Actively supported                                   |
| **CLI**                  | Not available                             | Powerful Angular CLI                                 |
| **Syntax**               | Simple but less powerful                  | Strong typing, decorators, modularity                |


## Q2) What is typescript? what are the advantages of TS over JS?
- TypeScript (TS) is a superset of JavaScript developed by Microsoft.
- It adds static typing, classes, interfaces, and many other features on top of JavaScript.
- TypeScript is a strongly typed, object-oriented, compiled language that compiles to plain JavaScript.
- TypeScript reports errors while writing code (development time), not at runtime.
- It has oop Features

## Q3) What are component in angular?
- A component in Angular is a basic UI building block that controls a part of the screen. It consists of a TypeScript class (logic), HTML template (view), and CSS (styling). Components help build reusable and modular code.
- App.cs file used for styling.
- App.html modifyng the html template of the component
- App.spec.ts  weiting unit test for component
- App.component.ts links all other component file

## What is selector and Template?
- selector = Selector is used to identify each component uniquely into a component tree.
- Template = A template defines the HTML view of a component.

## What is a Module in Angular?
- A module in Angular is a container that groups related components, directives, pipes, and services. It organizes the application and helps Angular know how to compile and run different parts of the app.

## What is Data Binding in Angular?
- Data Binding in Angular is the process of connecting the component (TypeScript code) with the view (HTML template) so that data can flow between them.
# Types of binding
- Interpolation (One-way from TS → HTML)
- Interpolation (One-way from TS → HTML)
- Event Binding (One-way from HTML → TS)
- Two-Way Data Binding (TS ↔ HTML)

## What are Directives in Angular?
- Directives are classes that add additional behaviour to element in angular application
# Types of Directives
- Component Directives=It controls a portion of the screen (UI).
- Structural Directives= They change the DOM structure
                         Add or remove elements from the DOM
- Attribute Directives = They change the appearance or behavior of an existing element.

## Difference Between Component, Attribute Directive & Structural Directive

| Feature                 | **Component**                                     | **Attribute Directive**                               | **Structural Directive**                         |
| ----------------------- | ------------------------------------------------- | ----------------------------------------------------- | ------------------------------------------------ |
| **Purpose**             | Creates & controls a UI view                      | Changes appearance or behavior of an existing element | Changes the **structure** of the DOM             |
| **Template**            | ✔ Has its own HTML template                       | ❌ No template                                         | ❌ No template                                    |
| **DOM Manipulation**    | Creates a full UI block                           | Does **not** add/remove elements                      | Adds/removes elements from DOM                   |
| **Syntax**              | Uses a **selector** like `<app-test>`             | Used as an attribute `[ ]`                            | Uses `*` prefix                                  |
| **Examples**            | Components you create — `app-header`, `app-login` | `ngClass`, `ngStyle`, `ngModel`                       | `*ngIf`, `*ngFor`, `*ngSwitch`                   |
| **Usage**               | For building UI (screens, forms, pages)           | For styling, behavior changes                         | For loops, conditionals, and dynamic DOM changes |
| **How it affects HTML** | Inserts a complete HTML template                  | Modifies properties, styles                           | Adds/removes elements                            |
