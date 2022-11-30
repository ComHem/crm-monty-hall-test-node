## Monty Hall - Problem to solve

The Monty Hall problem is based on an old "Let's make a deal" show. The name comes from the game host Monty Hall.

In the game, the participant gets to see three closed doors. There is a car behind one of them, while the other two are empty. The game starts by letting the participant choose one door without opening it. The game host then opens one of the other doors that does not contain the car to show that it is empty. There are now two unopened doors. The host asks the participant if he wants to change door or stick with the original selection.

Build an application that simulates this game to find out which strategy is the best one. The user should be able to select which strategy to use and how many simulations. Let the back end do the simulations and then print the result in the GUI.

To understand the problem, find a well balanced solution, and code with quality is important.

## Template

This is template git repo that you can use as a starting point.
Start by cloning this git repo into your own
Ett förberett projekt baserat på create-react-app och express hello world (med några tillägg).

### Systemkrav

[NodeJS](https://nodejs.org)

### Development mode

#### Start client

```
cd client
npm install
npm start
```

#### Start server

```
cd server
npm install
npm start
```

#### Verifikation

React appen har en komponent som pollar spring boot appens health endpoint och skriver ut svaret. Det som skrivs ut ska vara "UP" om allt funkar som det ska.
