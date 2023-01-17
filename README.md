# cars

Exercise for starting a rest API with java and implementing data persistence.

## Routes

```yml
POST /api/cars
    - Route to add a car.
    - headers: {}
    - body: {
	            modelo: "Fiat Argo 1.3",
	            fabricante: "Fiat",
	            dataFabricacao: "10/02/2006",
	            valor: 10.000,
	            anoModelo: 2023,
            }
```

```yml
GET /api/cars
    - Route to return a list car.
    - headers: {}
    - body: {}
```
