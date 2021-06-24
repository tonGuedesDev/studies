# Salvando datas no arquivo json 

```
req.body.created_at = Date.now()

fs.writeFile("data.js", JSON.stringfy(req.body, null, 2), (err) => {
    if (err) return res.send("Houve um erro na escrita do arquivo")

    return res.redirect(alguma pagina)
})
```

A linha <strong>req.body.created_at = Date.now()</strong> está pegando o objecto que está sendo retornado pelo req.body e adicionando uma nova chave chamada created_at </br>
dentro dessa chave está sendo adicionado a data de agora.

Por padrão o Date usá um formato de data chamado timestamp, que é um formato que usa milisegundos baseado na data de 1 de janeiro de 1971 as 00:00 até o dado momento.</br>

Para converte algo para esse formato(como uma data por exemplo) basta usar o metódo parse
```
req.body.aniversario = Date.parse(req.body.aniversario)
req.body.created_at = Date.now()

fs.writeFile("data.js", JSON.stringfy(req.body, null, 2), (err) => {
    if (err) return res.send("Houve um erro na escrita do arquivo")

    return res.redirect(alguma pagina)
})
```