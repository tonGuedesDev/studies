# Guardando os dados em um arquivo externo

### modulo fs
O módulo <strong>fs</strong> é um módulo do nodejs que permite você trabalhar com arquivos do sistema.

```
const fs = require("fs")
```

### metódo writeFile()
O método <strong>fs.writeFile()</strong> permite a criação de um arquivo no caminho especificado.

```
fs.writeFile("data.js", JSON.stringfy(req.body, null, 2), (err) => {
    if (err) return res.send("Houve um erro na escrita do arquivo")

    return res.redirect(alguma pagina)
})
```

O primeiro parâmetro é o caminho onde será salvo o arquivo, nesse caso como foi passado apenas o nome do arquivo, ele será criado na raiz.</br>

o segundo parâmetro é um metódo que transforma o objeto da requisição em um formato JSON, se esse metódo não fosse usado, os dados seriam salvos como um objeto normal</br>

O terceiro parâmetro é uma callback function</br>

Uma callback function é uma função que será executa após algo acontecer, nesse caso a callback será executa se tiver acontecido algum erro na escrita do arquivo. Se não acontecer nenhum erro, o fluxo normal da função continuará