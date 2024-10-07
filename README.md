# 08 TypeScript and OOP: towmato 🍅


# Table of Contents
* [Task](#task)
* [User Story](#user-story)
* [Acceptance Criteria](#acceptance-criteria)
* [Additional Requirements](#additional-requirements)
* [Notes](#notes)
* [Video](#video)
* [Repository](#repository)


## Task


My task was to update an existing TypeScript command-line application that builds and uses cars to have additional options for motorbikes and trucks. The application prompts the user to create a new vehicle or select an existing vehicle. After going through the creation process or the selection process, the user is able to perform certain actions with the selected vehicle. Different actions are available for Truck and Motorbike than there are for Car. The user is returned to the actions menu after each action until they decide to exit the application.



### User Story

```md
AS a developer
I WANT to update an existing application to include additional vehicle types
SO THAT I am able to comprehend and work with existing code bases.
```

## Acceptance Criteria

```md
GIVEN a command-line application that accepts user input
WHEN I am prompted to create a new vehicle or existing vehicle
THEN I can choose between the two options
WHEN I am prompted to choose the vehicle type during creation
THEN I can choose between car, truck, and motorbike
WHEN I am prompted for details about the vehicle
THEN I can enter the vehicle information
WHEN I have entered all the vehicle information
THEN I can use the created vehicle
WHEN I select an existing vehicle
THEN I can use the selected existing vehicle
WHEN I have created a new vehicle or selected an existing vehicle
THEN I can perform actions with that vehicle
WHEN I perform an action with a vehicle
THEN I see the result of the action in the command-line
WHEN I complete the process of performing an action
THEN I can perform additional actions until I choose to exit
```

## Additional Requirements

Use [Inquirer](https://www.npmjs.com/package/inquirer) for collecting input from the user. The application will be invoked by using the following command:

Right click on the Develop directory to Open in Integrated Terminal. 

```bash
npm start
```

## 📝 Notes
Speed up, slow down, wheelie, or tow! Each vehicle has specific actions available to it. A Motorbike only has 2 wheels and can't tow a Car. A Truck can tow a Car, but cannot perform a wheelie! 

## 🎥 Video

* This [link](https://www.insertvideolinkhere.com) will take you to [YouTube](https://www.insertvideolinkhere.com) to view the [video walkthrough](https://www.insertvideolinkhere.com) of this application. 



## Repository

* This [link](https://www.insertvideolinkhere.com) will take you to my [GitHub Repository](https://www.insertvideolinkhere.com).