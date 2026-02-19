
# Esquema GraphQL

## ¿Qué es GraphQL?
GraphQL es un lenguaje de consulta y entorno de ejecución para APIs que permite
al cliente solicitar únicamente los datos que necesita.

## Características principales
- Schema tipado
- Un solo endpoint
- Queries declarativas
- Autodocumentación

## Ejemplo de Query
```graphql
query {
  pokemon(id: "1") {
    name
    weight
    height
  }
}
```

## Ventajas frente a REST

- Evita el over-fetching
- Reduce la cantidad de peticiones HTTP
- Permite obtener datos relacionados en una sola consulta