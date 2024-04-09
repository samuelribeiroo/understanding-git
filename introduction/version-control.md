<h1>Controle de versão (Version Control - Tracking and managing)</h1>

<h2 style = 'text-align:center'>Definição</h2>Permite registrar, rastrear e alterar as versões em um ou mais arquivos (como se fosse o 'load' de um game). Com versionamento de controle é possível incluir features via commits, reverter as alterações feitas (a reversão pode ser feito em um arquivo ou no projeto todo, por isso a necessidade de backups/pull requests) e o mais importante, salvar as alterações.

<h4 style = 'text-align:left'>Exemplos de uso</h4>

<p style = 'text-align:left'>Correção de bug, Inclusão de features, Gerenciamento de conflito</p>


<h2>Quais problemas Sistemas de controle de versão resolvem ?</h2>
Em desenvolvimento de sistemas, programadores precisam trabalhar no código de forma colaborativa, dessa forma 'armazenar' o código com o objetivo de cada time entenda o que está sendo feito é a proposta.

<h3>MODELO CVCS</h2 Os arquivos eram armazenados em um servidor único e era acessado por determinado número 'x' de clients. Com isso, adms possuem maior controle do que é permitido fazer versus o que não é. k

>(Servidor Central -> Cliente)

A desvantagem consistem justamente na centralidade que o servidor exercia; HD do server corrompido ? Código Perdido.

<h3>MODELO DVCS</h2> <p>É aqui que o GIT entra em ação (não é o único, mas o mais popular), em sistema de controle distribuido a grande vantagem se concentra em cada client/user possuir localmente o repsitório completo (por sua vez fica hospedado na cloud, Github). Cada clone, é de fato, um backup - Se der ruim no server é possível qualquer repostório local pode ser copiado pro servidor original.
</p>

> Conceitos Fundamentais #01
> == Repostório = Local centralizado aonde os arquivos relacionaos ao desenvolvimento são armazenados, gerenciados e versionados.

> (Local repositories after 'git clone' doesn't change the main repo where is stored in the cloud, in that case github. Only changes if pull requests are made and accepeted)
