# LocalStorage Var

Implementation of the mini-events variable interface using localStorage

## Usage

Call the exported function with a string key to get a function
which has the same type as `variable` from mini-events.

```ts
const [set, { get, changed }] = localStorageVar('myState')('initialState')
```

See [@lbfalvy/mini-events](https://github.com/lbfalvy/mini-events#variable)
for examples on how to use the variable interface.