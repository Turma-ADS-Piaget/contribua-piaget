<h1>
     <img align="center" width="40px" src="https://imgur.com/hnaRmD3.png"></a>
    <span> Guia de Contribuição</span>
</h1>

Este repositório foi criado para introdução ao Git e contribuição em projetos Open Source.

O objetivo é simples: você deve adicionar um  README.md dentro da pasta alunos, apresentando-se.
> [!NOTE]  
> Você precisa instalar o Git e configurar o ambiente para utilizar o bash. <br>
> Para mais detalhes, acesse a documentação do Git: [Começando - Configuração Inicial do Git](https://git-scm.com/book/pt-br/v2/Começando-Configuração-Inicial-do-Git?form=MG0AV3).


<h2> 🛠 Passo a passo para contribuir </h2>

<h3>1 - Faça um fork do repositório</h3>
Acesse a página principal do repositório e clique no botão "Fork" no canto superior direito da página.

<h3>2 - Clone o repositório no seu computador</h3>
Abra o seu Git Bash e digite o comando git clone seguido da URL do seu fork para clonar o seu repositório localmente. Por exemplo:

```bash
git clone [Link-do-repositório].
```

Pressione enter, e uma cópia do seu fork no GitHub será criada localmente.

<h3>3 - Crie uma nova branch</h3>
Utilize o comando git checkout -b para criar e alternar para a nova branch e nomeie-a como feat/alunos/[Seu nome do GitHub].

> Exemplo: `git checkout -b feat/alunos/JoaoSilva`

<h3>4 - Crie o seu README.md</h3>
Dentro da pasta alunos, crie um arquivo em Markdown (extensão .md) e nomeie com o mesmo nome do seu usuário no GitHub:

> Exemplo: `alunos/JoaoSilva.md`>

<h3>5 - Adicione suas alterações</h3>
Utilize o comando git add alunos/[SeuArquivo].md para adicionar sua alteração à "staging area" no Git.

<h3>6 - Crie um Commit</h3>

```bash
git commit -m"feat: add [Seu Nome] Readme"
```
<h3>7 - Envie as Alterações para o seu Repositório Remoto</h3>
Envie as alterações realizadas no seu repositório local para a branch feat/alunos/[Seu nome do GitHub] no seu repositório remoto com o comando:

```bash
git push origin feat/alunos/[Seu Nome]
```

<h3>8 - Crie um Pull Request.</h3>
⚠️ Atente-se para a seguir as orientações para a contribuição, principalmente: <br>
Seu PR deve modificar apenas o arquivo alunos/[SeuNome.md] (dê uma olhadinha na aba "Files changed");

>[!NOTE]
> Caso não saiba como criar uma solicitação de pull, acesse a documentação do GitHub: [Como criar uma solicitação de pull
](https://docs.github.com/pt/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request)

Após criar o seu Pull Request, irei validar a sua submissão. Caso esteja tudo certo, seu Pull Request será Mergeado no Projeto, caso reprovada entrarei em contato explicando o motivo.


### Após concluir todas essas etapas você oficialmente terá contribuido ao um Projeto Open-Source meus parabéns 🏅

você também recebera uma Badge (Pull Shark) que será exibida no seu Perfil do GitHub.

| Badge | Name | How to get |
| :-: | :-: | :-: |
| ![Pull Shark](https://github.com/drknzz/GitHub-Achievements/blob/main/Media/Badges/Pull-Shark/PNG/PullShark.png) | Pull Shark | Opened a pull request that has been merged |


#### Links úteis
 Gerador de Profile Readme: https://profile-readme-generator.com <br>
 Como exibir seu Profile Readme na sua página do GitHub: https://docs.github.com/en/get-started/start-your-journey/setting-up-your-profile


>[!NOTE]
> Esse repositório foi inspirado no dio-lab-open-source
](https://github.com/digitalinnovationone/dio-lab-open-source/tree/main)
    


