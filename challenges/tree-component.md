---
description: Create a tree component in react and publish it
---

# Tree component

## Introduction

A company is creating an application for viewing and managing all the smart devices in hospitals. Smart devices are usually placed in rooms, but they could be in any level of the hierarchy.

They need a tree component that will be placed in a sidebar of the application, to allow the user to navigate through all the buildings, plants and rooms of the hospital to see the available devices.

The hospital is usually divided into buildings -&gt; plants -&gt; rooms, but the tree should accept any structure.

![Example of a tree component](https://lh6.googleusercontent.com/3023YsB1zOfCuoOOK4NGbZbaJ7xZy04i33RGemlvrg7mok2Sagjv-fmEhjC_p_IJWR036A9EyeqRKu_fTkP_ZmCvH756GGgoWXNcQD56xqZezr1zBWMBqxNnn5nhc_62_BDR0sGm)

## Requisites

* This should be a presentational component. It expects a tree structure as a prop.
* The component must be written in TypeScript and ship it's type definitions
* The component should be unit tested using Jest
* The component should be flexible
  * Allow any number of levels
  * Allow devices in any level
* Sections and devices must use different icons at the left of the label
* Show an arrow indicating if it's collapsed or not.
* Sections without children shouldn't have the arrow.
* The component should be published to a private NPM repo
* The component mush have a readme with an example and some documentation.
* Control the bundle size. Nobody uses a heavy library.
* That the component will be used in different scenarios and from different people. It must be resilient, flexible and easy to use.

## Tips

* Read all the document and understand it before doing any work. The way of validating the component is checking that it fits all the requirements.
* If there are technologies / techniques that are new for you, read about them first.
* Split the work into smaller tasks, from simple to complex.
* You can get started using create-react-app.
* The build as library requires some extra steps. There are some articles available describing that process. I suggest leaving that to the end.
* You'll need to use the "recursivity" pattern.
* You can use Github packages as private NPM repo.

## What you'll learn

* Recursivity pattern
* Unit Testing and Jest
* Publishing to a private NPM repo
* The importance of performance and keeping the bundle size low





