# Redux

Useful References: https://react-redux.js.org/

Useful Resources:

- Redux Form: https://redux-form.com/8.2.2/docs/gettingstarted.md/

---------------Notes---------------:
- Routing

- Async
> Callbacks - Good
> Promises  - Better
> Generators- Awesome

> Redux-thunk and Redux-saga are middleware (higher order functions) that are used to make asynchronous API calls in Redux.
```
export const sinFunction = () => (dispatch, getState) => {
 dispatch({
  type: GET_DETAILS
 })
 setTimeout(() => {
  dispatch({
   type: CANCEL_FETCH
 })
 }, 2000)
}
```
<img src="images/workflow.png" width="600"/>
