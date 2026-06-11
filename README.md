<div align="justify">

<h1>QUICK START</h1>

Caso esta seja sua primeira experiência com GitHub, uma das formas mais simples de começar é utilizando o GitHub Desktop, uma ferramenta gráfica que simplifica o envio e atualização de arquivos sem a necessidade de utilizar comandos do Git.

<h2>Passo 1 — Instalar o GitHub Desktop</h2>

Faça o download e instale o [GitHub Desktop](https://desktop.github.com/download/) em seu computador.

<h2>Passo 2 — Realizar o Login</h2>

Após a instalação, faça login utilizando sua conta GitHub.

Caso ainda não possua uma conta, será necessário criar uma gratuitamente antes de prosseguir.
O método mais simples costuma ser a autenticação utilizando uma conta Google. Entretanto, caso a intenção seja utilizar o GitHub como plataforma oficial da equipe, recomenda-se criar ou vincular a conta utilizando um e-mail institucional da equipe, evitando a dependência de contas pessoais dos membros.
Essa prática facilita a continuidade dos projetos ao longo dos anos, garante maior controle sobre os repositórios e reduz problemas relacionados à troca de integrantes ou responsáveis pela administração do conteúdo.

<h3>Passo 3 — Criar uma Pasta de Trabalho</h3>

Crie uma pasta em seu computador que será utilizada para armazenar os arquivos do projeto.

Exemplo:

```txt
Projetos
└── Simulation 3D
    ├── CAD
    ├── Code
    ├── Images
    └── Docs
```

<h3>Exemplo 1 — Criando uma Pasta Diretamente pelo GitHub Desktop</h3>

O primeiro método consiste em criar um novo repositório diretamente pelo GitHub Desktop. Nesse processo, o próprio software será responsável por criar a estrutura inicial da pasta e vinculá-la automaticamente ao GitHub.

<table align="center">

<tr>

<td align="center" width="800">
	<img src="https://github.com/FRCMT-Repositories/github/blob/main/img/EX1.gif" width="800">
</td>

</tr>

</table>

---

<h2>Exemplo 2 — Vinculando uma Pasta Já Existente</h2>

Caso você já possua uma pasta contendo arquivos, documentações, imagens ou projetos, também é possível associá-la diretamente ao GitHub através do GitHub Desktop.

Esse método é especialmente útil para projetos que já estão em desenvolvimento e apenas precisam ser adicionados ao controle de versão.

<table align="center">

<tr>

<td align="center" width="800">
	<img src="https://github.com/FRCMT-Repositories/github/blob/main/img/Ex2.gif" width="800">
</td>

</tr>

</table>

---

Após concluir uma das opções anteriores, a pasta do projeto será criada ou vinculada no local definido durante a configuração.

Para confirmar que o repositório foi criado corretamente e está hospedado no GitHub, utilize a opção `View on GitHub`, conforme ilustrado abaixo.

<table align="center">

<tr>

<td align="center" width="800">
	<img src="https://github.com/FRCMT-Repositories/github/blob/main/img/ViewGit.gif" width="800">
</td>

</tr>

</table>

</div>

> [!TIP]
> <div align="justify">
>
> Ao acessar a opção `View on GitHub`, verifique se:
>
> - o nome do repositório está correto
> - a descrição do projeto foi preenchida
> - os arquivos foram enviados com sucesso
> - o arquivo `README.md` está sendo exibido corretamente
>
> Essa simples validação ajuda a identificar problemas logo no início do projeto.
<h2>Passo 4 — Adicionar os Arquivos</h2>


Dentro dessa pasta, organize todos os arquivos que deseja enviar para o GitHub, mantendo uma estrutura de diretórios clara e padronizada.

Uma boa organização desde o início facilita a manutenção do projeto e a navegação dos demais colaboradores.

</div>

> [!IMPORTANT]
> <div align="justify">
>
> LIMITE DE TAMANHO DOS ARQUIVOS
>
> O GitHub possui um limite de aproximadamente 100 MB por arquivo para envios convencionais.
>
> Caso algum arquivo exceda esse tamanho, recomenda-se:
>
> Dividir o conteúdo em múltiplos arquivos menores
> Compactar os arquivos quando possível
> Utilizar ferramentas específicas para arquivos grandes, como Git LFS
>
> Em projetos CAD e simulações 3D, é comum que modelos, vídeos e animações ultrapassem esse limite, portanto verifique o tamanho dos arquivos antes de realizar o envio.

<h2>Passo 5 — GitHub Desktop e Primeira Documentação</h2>

Agora que o repositório foi criado e as pastas foram organizadas conforme desejado, vamos entender como utilizar o GitHub Desktop para armazenar arquivos, acompanhar alterações e criar documentações como esta que você está lendo.

Uma das grandes vantagens do GitHub é permitir que, além de armazenar código, também seja possível criar documentações completas para explicar projetos, procedimentos, tutoriais e materiais de apoio.

<h3>Criando seu Primeiro Arquivo de Documentação</h3>

Para começar, crie um arquivo chamado README.md na raiz do seu projeto.

O arquivo README.md é normalmente o primeiro conteúdo visualizado ao acessar um repositório e, por esse motivo, costuma ser utilizado para:

- apresentar o projeto
- fornecer instruções de utilização
- documentar procedimentos
- explicar conceitos
- disponibilizar tutoriais
- organizar links úteis
- compartilhar imagens e vídeos

O exemplo abaixo ilustra a criação do arquivo:
<table align="center">

<tr>

<td align="center" width="800">
	<img src="https://github.com/FRCMT-Repositories/github/blob/main/img/Readmemd.gif" width="800">
</td>

</tr>

</table>

<h3>O que é Markdown?</h3>

O arquivo README.md utiliza a linguagem Markdown, uma sintaxe simples criada para facilitar a construção de documentações.

Com ela é possível criar:

títulos e subtítulos
listas
tabelas
blocos de código
links
imagens
GIFs
caixas de aviso
trechos em HTML

Praticamente toda a documentação deste repositório foi construída utilizando Markdown combinado com HTML.

Nas próximas seções iremos explorar detalhadamente como utilizar esses recursos para criar documentações mais completas e profissionais.

<h3>Configurando o Editor</h3>

Após criar o arquivo, abra-o em um editor de texto de sua preferência.

Caso o editor apresente opções de formatação, recomenda-se selecionar o modo Markdown, conforme ilustrado abaixo:

<table align="center">

<tr>

<td align="center" width="800">
	<img src="https://github.com/FRCMT-Repositories/github/blob/main/img/ReadmeConfig.png" width="800">
</td>

</tr>

</table>

</div>

> [!NOTE]
> <div align="justify">
>
> Embora o Markdown seja suficiente para a maioria das documentações, o GitHub também permite a utilização de diversos elementos HTML, possibilitando a criação de tabelas, alinhamentos, imagens centralizadas e estruturas mais elaboradas.
>
> Essa combinação entre Markdown e HTML é amplamente utilizada neste projeto para melhorar a organização e a apresentação visual da documentação.

Agora que o arquivo `README.md` foi criado e configurado corretamente, podemos começar a explorar os principais recursos da linguagem Markdown, aprendendo a criar títulos, listas, links, imagens, GIFs, blocos de código e caixas de destaque para enriquecer a documentação do projeto.

<h3>Publicando seu Primeiro Arquivo</h3>

Antes de prosseguirmos com os recursos de documentação, vamos realizar o envio do arquivo README.md para o GitHub. Dessa forma, você já começará a se familiarizar com o processo de versionamento e atualização dos projetos.

Para isso, abra o GitHub Desktop e selecione o repositório criado anteriormente.

Utilizando este próprio repositório como exemplo, observe que o GitHub Desktop identifica automaticamente todas as alterações realizadas dentro da pasta do projeto. Como acabamos de criar o arquivo README.md, ele aparecerá listado na área de modificações.

<h4>Passo 1 — Verificar as Alterações</h4>

Antes de enviar qualquer arquivo, verifique quais alterações serão incluídas no próximo envio.

É uma boa prática conferir se:
- os arquivos corretos foram modificados;
- não existem arquivos temporários sendo enviados;
- a estrutura do projeto está organizada conforme esperado.

<h4>Passo 2 — Realizar o Commit</h4>

Após validar as alterações, preencha uma descrição resumida informando o que foi modificado.

Exemplo:

Add initial README documentation

ou

Criação da documentação inicial

Em seguida, clique em Commit to main.

O commit cria um registro permanente no histórico do projeto, permitindo rastrear todas as alterações realizadas ao longo do tempo.

<h4>Passo 3 — Enviar para o GitHub</h4>

Após realizar o commit, clique em Push Origin.

Esse processo envia todas as alterações armazenadas localmente para o repositório hospedado no GitHub.

Somente após o Push Origin os arquivos estarão disponíveis na plataforma online.

<h4>Passo 4 — Validar o Resultado</h4>

Ao finalizar o envio, acesse o repositório através da opção View on GitHub ou diretamente pelo navegador.

Verifique se:
- o arquivo README.md foi enviado corretamente;
- a estrutura das pastas está sendo exibida;
- o conteúdo da documentação aparece na página principal do repositório;
- não existem arquivos faltando ou enviados incorretamente.

A imagem abaixo ilustra o processo completo de submissão do arquivo `README.md`.

<table align="center">

<tr>

<td align="center" width="800">
	<img src="https://github.com/FRCMT-Repositories/github/blob/main/img/gitpush.gif" width="800">
</td>

</tr>

</table>

Qualquer alteração realizada no projeto, seja ela relacionada a código, documentação, imagens, modelos CAD ou qualquer outro arquivo, deverá seguir novamente o mesmo fluxo apresentado anteriormente:

```txt
Alteração → Commit → Push Origin → Verificação na Web
```


---

<h3>Titulos e subtitulos</h3>

```tex
<h1>Titulo 1</h1>
<h2>Titulo 2</h2>
<h3>Titulo 3</h3>
```
<h1>Titulo 1</h1>
<h2>Titulo 2</h2>
<h3>Titulo 3</h3>

---

<h3>Alinhamentos</h3>

```tex
<div align="left">
Texto alinhado a esquerda

<div align="center">
Texto alinhado ao centro

<div align="right">
Texto alinhado a direita

<div align="justify">
Texto distribuido
```
<div align="left">
Texto alinhado a esquerda

<div align="center">
Texto alinhado ao centro

<div align="right">
Texto alinhado a direita

<div align="justify">
Texto distribuido

---


</div>