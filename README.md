# reactjs


If you go to chrome redux tool then you gona see message no store found [follow this instruction](https://github.com/zalmoxisus/redux-devtools-extension#usage "follow this instruction")



we are not going to use this ,  we install the redux dev tool extenstions



```javascript

// src/store.js
// this is the boilerplate , a lot of store file just looks similar


import {createStore, applyMiddleware} from 'redux';
import {comoposeWithDevTools} from 'redux-devtools-extenstion';
import thunk from 'redux-thunk';
// we gona have mulitple reducers(auth,profile,post.. so on) but we are gonna combine them in root reducers
// since we gona call int index.js in reducers folder so we can sipmply import as './reducers'
import rootReducer from './reducers';


const initialState = {}





```
