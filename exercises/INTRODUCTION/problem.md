Single immutable state tree

The first principle of redux is that the whole state of your app is represented as a single JavaScript object.
All the state changes in redux are explicit, so it is possible to keep track of all of them.

The second priciple is that a state tree is read only, you cannot modify or write to it. So anytime you want to change the state you need to dispatch an action. An action is plain JavaScript object discrabing the change. Just like state is the minimal representation of the data in the app, the action is the minimal representation of the change to the data. The only requirement is that your action object has a type property.

----------------------------------------------------------------------

## HINTS
