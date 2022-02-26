# useForm

Example of use:

```
const initialState = {
    name: '',
    age: 0,
    email: '',
};

const [values, handleInputChange, reset] = useForm(initialState);
```