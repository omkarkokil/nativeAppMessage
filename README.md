# This is a react native App with prebuild



## Description
In this first we create a prebuild for the react native application : [android]


## Installation

In the prebuild we first need to create a basic app using react native

```sh
npx create-expo-app app-name --template tabs   
```

## Create and run the prebuild

To create a prebuild for react native we use follwing command.

### Create prebuild

```sh
npx expo prebuild  
```

### Run prebuild

```sh
 npx expo run:android --device  
```

## Issue facing when building the expo

Sometimes we get some issue when creating a prebuild the follwings are issue and their solutions

### SDK Isssue

React Native android build failed. SDK location not found

## Solutions
To solve this issue create a  local.properties in android folder and add this line

```sh
 sdk.dir = C:\\Users\\USERNAME\\AppData\\Local\\Android\\sdk
```
note change the username according to your username which is in Users folder 







