# Validar CPF

## Exemplo de utilização

Para validar um cpf basta instanciar a classe e passar o cpf a ser validado,
e chamar o método `isValid()` o qual irá retornar um booleano.
```javascript
    const cpf = new ValidCPF('374.615.055-80')

    if(cpf.isValid()) {
        console.log("CPF válido")
    }else{
        console.log("CPF Inválido")
    }

    // CPF Válido
```
