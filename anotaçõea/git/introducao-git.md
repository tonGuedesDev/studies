# git e github

## git
<p>o git e um sistema de versionamento de arquivos(seja codigo, ou arquivos de texto normais), atraves dele e possivel controlar versoes diferentes de um projeto. Nao so isso, o git e muito importante para o trabalho em equipe, pois diferentes pessoas podem contribuir para o projeto ao mesmo tempo. Todos os arquivos versionados sao armazenados localmente</p>

## github
<p>O github e uma plataforma para armazenar os arquivos versionados pelo git na nuvem, permitindo que esses arquivos possa ser acessado de qualquer lugar do planeta, indepente do computador usado.</p>

## Elementos importantes do git

### Repositorios
<p>O github trabalha com um sistema de repositorios, quenada mais e do que as pastas que o git usa para armazenar os arquivos. Atraves desses repositorios seu projeto pode ser visto e receber contribuicoes(se tiver sido definido como publico), receber forks(ser copiados) etc... </p> 

### Branch
<p>A branch e uma ramificacao na linha cronologica principal do projeto. Imagine que voce precisa criar uma nova funcao na sua pagina web, porem nao quer usar a versao principal do seu codigo. A branch permite que voce crie uma ramificacao dessa pagina e modifique, podendo adicionar essa funcionalidade na linha principal posteriormente. Isso e importante, pois possibilita que tudo seja testado antes de entrar em producao.</p>

### commit 
<p>Quando uma alteracao e feita em um arquivo, ela precisa ser salva, o commit faz justamente isso, pega essa alteracao e salva localmente no seu repositorio</p>

### merge
<p>O merge e responsavel por juntar duas ramificacoes distintas; Aqui entra uma funcionalidade muito importante do git, atraves do git e possivel que duas ou mais pessoas modifiquem um arquivo ao mesmo tempo</p>

<p>Por exemplo: Imagine que seu chefe pede para voce criar uma branch para fazer um formulario na pagina web da empresa, enquanto voce faz isso, outro companheiro da equipe adiciona um botao na mesma pagina na linha principal e faz um commit. E agora? Teoricamente isso iria criar uma bagunca, pois na sua versao aquele botao nao existe, mas e ai que entra o merge e faz a magica acontece; Se voce e seu companheiro nao tiver feito a modificacao exatamente na mesma linha, e possivel fazer a juncao das duas branches sem problema algum</p>

### remote
<p>Tudo que foi dito ate agora e utilizado pelo git localmente, porem e interessante armazena esses arquivos em um repositorio remoto; O remote e responsavel por fazer a ligacao entre o git e a plataforma na nuvem</p>

### pull
<p>Quanto um commit e feito, esse arquivo e salvo apenas no repositorio local, o push faz a funcao de levar esses arquivos para o repositorio remoto</p>

### push
<p>O push e justamento o contrario do pull, enquanto o pull empurra, o push puxa os arquivos do repositorio remoto </p>







