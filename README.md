# Notas

Este repositorio contiene diferentes customHooks de utilidad
constante a lo largo de diferentes proyectos para evitar reescribirlos.

**useCounter**
```
	const {counter, increment, reset, decrement} = useCounter(1)
```

**useFetch**
```
	const url = 'Endpoint de una API'
	const {loading: true, data: null, error: null} = useFetch(url)
```

**useFetch**
```
	const initialState = {
		name: '',
		age: 0,
		email: ''
	}
	const [values, handleInputChange, reset] = useForm(initialState)
```