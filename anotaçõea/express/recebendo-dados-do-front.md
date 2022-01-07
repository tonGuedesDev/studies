# Recebendo dados do front-end
<p>É possivel pegar dados do front com o express de duas formas</p>

### req.query
<p>O <strong>req.query</strong> pega os dados que são passados na url</p>

### req.body 
<p>O <strong>req.body</strong> pega os dados que são passados no corpo da pagina</p>

Após chamar o req.body é necessario passar um midleware no arquivo principal

```
server.use(express.urlencoded({ extended: true }))
```
Essa linha será o resposável pelo funcionamento do req.body