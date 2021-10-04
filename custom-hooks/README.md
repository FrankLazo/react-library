# Custom hooks

## useCounter

```js
const initialValue = 10;
const { state, increment, decrement, reset } = useCounter(initialValue);
```

## useFetch

```js
const url = 'Endpoint de la API';
const { data, loading, error } = useFetch(url);
```

## useForm

```js
const initialForm = { };
const { values, handleInputChange, reset } = useForm(initialForm);
```