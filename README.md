# Pre Rquired

- contexts API
- reducer
- action , dispatch

# Redux-1 :

It is a single place to manage all information.

- actions
- dispatch

Journey of Reduxe :

- cmd: `npm i redux react-redux`
- create Reducer Function.
- create initial state.
- createStore and Pass Reducer Function and initialState to it.
- wrap our Application ReduxeProvider and pass store to it.
- using useDispatch and useSelector in our application.

  - useDispatch to perform action.
  - useSelector for reading data from store.

Action Types Files :-

- create action.types.js file for keeping all the dispatch type variable.
- pass these variables all pages where required.

Actions :-

- create action.js file and do all the functions .
- pass these functions inside dispatch
- manage the argument of action too.

= Created BY Rovin Singh 07/06/2022
