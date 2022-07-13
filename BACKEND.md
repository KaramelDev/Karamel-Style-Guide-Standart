## Backend (python)

### Standard:
- **PEP8** style compliant
- **Django** style compliant ([Django Coding Style](https://docs.djangoproject.com/en/dev/internals/contributing/writing-code/coding-style/#python-style)) 
- use 4 spaces for indentation

### Tools:
- pycodestyle
- black

### Variable Naming:
- please use english
- **variable** name should be snake_case
- **function** name should be snake_case
- **class** name should be UpperCamelCase (the first letter must uppercase)

### API URL
- please use english
- use lowercase
- use kebab-case for two words or more
- end with `/` ex: `/api/master/category/`, `/api/master/category/{id}/`
- if use `/all/` should be non-pagination with simple result

### API Error handling
- Standart Response Status Code (please don't use 200 only)
- Response error data
  ```
  {
    "errors": [
      "Error message here."
    ]
  }
  ```
