# FCC_Redux

const reducer = (state = 5) => {
  return state;
}
const store = Redux.createStore(reducer)

/////////////////////////////////////////////////////////

const store = Redux.createStore(
  (state = 5) => state
);
const currentState = store.getState()

//////////////////////////////////////
