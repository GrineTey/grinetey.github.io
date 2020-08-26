---
layout: post
title:  "Usando Git e Github"
date:   2020-07-09
excerpt: "Um pouco de conhecimento sobre Git e GitHub"
image: "/images/eyeglasses-in-front-of-laptop-computer-1181253.jpg"
---

![Git and Github](https://miro.medium.com/max/700/1*D5zGIGFZoEO4uCTriOj4xg.jpeg)

## Primeiro passo para a utilização do Git
#### É fazer o Download do Git no site oficial do projeto.
Aqui [Site git](https://git-scm.com)
Primeiramente para usarmos git teremos que compreender realmente como é o funcionamento do Git, Git é um Sistema de controle de versão distribuído Open Source.
	Atualmente, o Git é a melhor escolha para a maioria das equipes de software.

### O que é controle de versão
#### Benefícios do controle de versão
Os sistemas de controle de versão são uma categoria de ferramentas de software que ajudam uma equipe de software a gerenciar alterações no código fonte ao longo do tempo. O software de controle de versão controla todas as modificações no código em um tipo especial de banco de dados. Se um erro for cometido, os desenvolvedores podem voltar no tempo e comparar versões anteriores do código para ajudar a corrigir o erro e minimizar a interrupção para todos os membros da equipe.

Depois de feito o Download e feita também a Instalação do Git, você tem que criar uma conta no Github, **( Lembrando que Git e Github são coisas diferentes)** entrando no site do Github crie um novo repositório no **+** que aparece no canto da tela, e coloque o nome do seu projeto. Depois de criado clique em Git Clone e copie o link que aparece na caixinha que foi aberta, agora no seu computador crie uma pasta do seu projeto de preferencia com o mesmo nome que você colocou no repositório do Github, abra o terminal dentro da pasta que você criou, e de um **git clone ( cole a url que vc copiou)** e de um enter, se tudo ocorrer corretamente ele vai fazer o download do repositório no caso ele vai ter criado com o arquivo **README.MD**

O arquivo README.MD é o arquivo onde vc vai escrever sobre o projeto e ele fica na pagina principal do repositório no Github, feito isso todo mundo que entrar na pagina do seu projeto se ele for publico vai conseguir ler o arquivo.

Se você for criar um repositório do seu computador você cria uma pasta com o nome do repositório e da um **git init** esse comando faz o computador entender que dentro daquela pasta tem um repositório ativo, quando vc for fazer qualquer modificação nos arquivos que estão dentro do repositório vc da o comando **git add** que ele vai fazer o computador entender que vc adicionou essas modificações que estão pronta para ser commitadas, más o que é commit ?

Commit é onde você vai fazer a confirmação da alteração e escrever um comentário, você usa o comando **git commit -m “aqui você escreve a modificação “**, com esse comando você está pronto pra poder enviar seu projeto pro Github.

Eu recomendo que sempre que você fizer todos esses comando siga com **git status** que vai te dar detalhadamente o que está acontecendo dentro do repositório, se ficar alguma linhas vermelhas, você provavelmente modificou algum arquivo e esqueceu de fazer o processo do **Git add .**, se não ficarem vermelhas o arquivo está pronto para ser commitado.

## E como eu envio esse projeto pro Github ?
Calma ai, é somente você dar o comando **Git push origin master** pode ser que ele vai pedir seu login e sua senha do Github pra confirmação, depois se tudo der certo vc pode verificar no site do Github onde você criou o projeto que seus arquivos vão estar lá.

Futuramente vou postar um tutorial de como fazer um pull request, e fork de projetos para fazer a contribuição dos projetos Open Source que existem no GitHub, ou mesmo contribuição com projetos da **Grine Tey.**

![Git Github](https://images.pexels.com/photos/1181253/pexels-photo-1181253.jpeg?cs=srgb&dl=eyeglasses-in-front-of-laptop-computer-1181253.jpg&fm=jpg)
