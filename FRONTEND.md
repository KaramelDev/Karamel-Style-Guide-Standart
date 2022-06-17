## Frontend (javascript)

### Standard:
- **eslint** standard
- use 2 spaces for indentation
- **vue** style compliant ([Vue Style](https://v2.vuejs.org/v2/style-guide/))

### Tools:
- eslint

### Variable Naming:
- please use english
- **variable** name should be camelCase
- **function** name should be camelCase
- **class** name should be UpperCamelCase (the first letter must uppercase)

### API Error handling
- Standart Response Status Code
- Parse error notification from API to `$axios.onError()`
  ```
  const dataError = e.response.data.errors
  Object.keys(dataError).forEach((item) => {
    app.$toast.error(dataError[item]) // alert or messages
  })
  ```
