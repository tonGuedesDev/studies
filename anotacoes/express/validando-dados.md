# Validando dados recebidos

```
const keys = Object.keys(req.body)

for(key of keys) {
    if (req.body == "") {
        return res.send("retornando")
    }
}
```

Aqui estamos usando o constructor "Object.keys" para retorna um array apenas com as chaves passadas no  front, essa técnica é usada para fazer a validação de todos os campos de uma vez, usando o for. 