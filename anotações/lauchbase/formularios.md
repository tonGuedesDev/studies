# Trabalhando com formulários

> para que serve?
<p>Formulario é um bloco onde o usuario coloca dados. Dados esses que podem ser enviados para ser tratados no servidor ou usados para outro motivo</p>

> Sintaxe

```
<form action="/pagina-processa-dados-do-form" method="post">
    <div>
        <label for="nome">Nome:</label>
        <input type="text" name="nome" />
    </div>
    <div>
        <label for="email">E-mail:</label>
        <input type="email" name="email" />
    </div>
    <div>
        <label for="msg">Mensagem:</label>
        <textarea name="msg"></textarea>
    </div>
</form>
```

> Parâmetros

#### method
<p>O parâmetro <strong>method</strong> informa para onde os dados serão enviados.</p>

#### action
<p>O parâmetro <strong>action</strong> informa o tipo de requisição que será feita, <strong>GET</strong> ou <strong>POST</strong>.</p>

#### input
<p>A tag <strong>input</strong> será onde o usuário digitará os dados que serão enviados.</p>
<p>Existem alguns tipos de dados que podem ser passados, como: texto, email, password.</p>

<p>Exemplo:

     o input do tipo email, apenas poderá receber dados que corresponda a um email, como: exemplo@gmail.com

    o input do tipo texto, pode receber qualquer tipo de dado, contanto que seja texto.
</p>

#### label
<p>A tag <strong>label</strong> serve para linkar o campo input</p>
<p>Exemplo:
    
    <label for="email">E-mail:</label>
    <input type="email" name="email" />
    

    Se o usuário clica no nome "email", o cursor irá automaticamente para o input "email"
</p>

#### textarea
<p>A tag <strong>textarea</strong> serve para o usuário digitar texto</p>
<p>Geralmente usado para o usuário enviar algum comentário, sugestão ou alguma informação adicional</p>