# Programador ruby 👋

[... English Recruiter or Tech Leader? For you ❤️](https://github.com/Pauloparakleto/resume/blob/main/README.md)

Meu nome é Paulo Felipe Souza, sou de Belém do Pará, Norte do Brasil (*the north remember*).

Sobre projetos pessoais, sou um dos contribuidores do projeto [opoloo/lines-engine](https://github.com/opoloo/lines-engine), um blog engine feito em rails 5. Você também está convidado a participar. Atualmente, meu foco é na internacionalização de todas as views.

<h3 align="left">Linguagens e ferramentas:</h3>
<p align="left"> <a href="https://circleci.com" target="_blank"> <img src="https://www.vectorlogo.zone/logos/circleci/circleci-icon.svg" alt="circleci" width="40" height="40"/> </a> <a href="https://git-scm.com/" target="_blank"> <img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="git" width="40" height="40"/> </a> <a href="https://www.linux.org/" target="_blank"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/linux/linux-original.svg" alt="linux" width="40" height="40"/> </a> <a href="https://www.postgresql.org" target="_blank"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/postgresql/postgresql-original-wordmark.svg" alt="postgresql" width="40" height="40"/> </a> <a href="https://rubyonrails.org" target="_blank"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/rails/rails-original-wordmark.svg" alt="rails" width="40" height="40"/> </a> </p>

## Objetivo Profissional

Meu objetivo profissional é me aprofundar ainda mais em desenvolvimento web (Ruby e Ruby on
Rails) para, com isso, alinhar com a habilidade que cultivei durante a minha formação educacional e profissional
como mestre em economia.

E o que um bacharel em economia, mestre também em economia, formado pela Universidade Federal do Pará, está fazendo no mundo do desenvolvimento web? Perguntaria o RH.

Bem, essa história é um pouco longa e espero ligar os pontos dela até fazer sentido também para você. Mas antes, eu gostaria de te apresentar alguns dos projetos que tenho trabalhado/concluido no ramo do universo do código ruby.

## Experiência

### Backend Ruby on Rails

Desenvolvedor Backend Júnior para a empresa Certus, uma fintech e Startup.

## Projetos Pessoais

### CSV Uploader

É um sistema em Ruby on Rails 6 que resolve o seguinte cenário:

Documentação dos items de uma Loja Virtual especializada na venda de aparelhos de telefonia celular. Para criar o inventário inicial da loja, com todos os telefones disponíveis, o estoque e seus preços, envia-se arquivos CSV com os dados a incluir. Também se pode periodicamente atualizar o inventário com planilhas idênticas, assim como dando a possibilidade de aplicar alguns filtros.

A aplicação está coberta com testes e os detalhes de como você pode roda-la em sua máquina local estão descritos no repositório do projeto.

- [Repositório do Projeto CSV Uploader](https://github.com/Pauloparakleto/csv_uploader)

### Almocherif

Sistema em Rails 6 para cadastro de estoque com nome e quantidade. Sua funcionalidade principal é dar entrada e saída na quantidade dos itens do estoque. Observa-se os seguintes critérios: 
1. Um item do estoque já movimentado, com entrada ou saída em sua quantidade, não pode ser deletado por motivo de futura auditoria.

2. Não se pode movimentar os itens do estoque em horário fora do horário comercial.

- [Repositório do Projeto Almocherif](https://github.com/Pauloparakleto/almocherif)

Sua atual fase de construção está documentada em um check list no REAEDME do repositório.

### Order Wizard Manager

Sistema básico de gerenciamento de pedidos (de compra/venda). Suas funcionalidades:

1. Uma ordem criada possui status pendente
2. Pode-se alterar status de pendente para em progresso e, por fim, para completo.
3. Uma ordem possui autoincremento de seu código de pedido.
4. Pode-se filtrar ordem por status ou por código de controle.

- [Order Wizard-Management Repository](https://github.com/Pauloparakleto/order-management-system)
- [Check the live application](https://order-wizard-manager.herokuapp.com)

### Projeto Diário de Estudos

Projeto realizado durante o processo seletivo da Iugu for Devs. É um sistema criado em Rails 6 e totalmente testado em sua integralidade.
Seu fluxo de autenticação é via Devise. Usei Simple Form para as views do Devise. Seu método de pesquisa é feito via Ransack e seu layout foi feito com Bootstrap.

- [Repositório do Projeto e detalhes técnicos](https://github.com/Pauloparakleto/aquecimento-iugu-study-diary-rails)

### Projeto Nintendo Mania

Este é um projeto pessoal de download de jogos antigos de Super Nintendo feito em Ruby on Rails 6. Sua versão atual e todos os detalhes técnicos de como acessá-lo e fazer seu deploy estão em meu repositório no Github.

Nesse projeto, eu resolvi desafiar a mim mesmo a não usar Bootstrap e
construir todo o layout responsivo com CSS. Isso me deu a vantagem de encontrar rapidamente eventuais problemas na view e corrigí-los imediatamente.

Vá em frente e teste em diferentes dispositivos, inclusive vertical e horizontalmente em smart phones. A aplicação consome um storage na google cloud. Faça o teste, pesquise pelo seu jogo de Super Nintendo favorito e baixe-o. Mas se for jogar mesmo, use o emulador snes9x, um dos melhores emuladores que eu conheço.

 - [Live demo do projeto Nintendo Mania](https://ancient-bayou-79761.herokuapp.com/)
 - [Sobre o projeto e detalhes técnicos](https://github.com/Pauloparakleto/download_games)
 
 ### Webhook API Feita em Ruby on Rails 6
 
Este projeto consiste de uma aplicação que posta no banco de dados Postgresql os eventos relacionados a issues no GitHub. Caso uma issue seja aberta ou fechada, o banco de dados vai receber este evento.

As instruções de como utilizar este projeto estão no meu repositório GitHub. Caso o time tenha um sênior, ele facilmente consegue adaptar o projeto para receber issues de membros específicos com um simples método condicional.

- [Detalhes do projeto e como configurá-lo localmente](https://pauloparakleto.github.io/webhookrails/)

### Pymenta Open Source

Refatoração de código legado de projeto open source em Rails 5. O escopo deste trabalho foi a aplicação da responsividade de acordo com a filosofia “mobile first” com o Bootstrap. Para tal projeto, foi necessário ler uma documentação do JQuery, uma vez que o Bootstrap usa JQuery para alterar as classes do layout.

A experiência com o meu primeiro projeto pontuado aqui, o Nintendo Mania, foi importante para entender o comportamento das classes do Bootstrap e alterá-lo manualmente de acordo com o escopo do projeto. Aconselho você a testar as views dos dois projetos, o original e meu fork, em diferentes telas. Ainda, alterar no seu computador o tamanho da tela do seu navegador para ver como ambos se comportam.

- [Live demo do meu fork](https://damp-meadow-76948.herokuapp.com/)
- [Meu fork do repositório](https://github.com/Pauloparakleto/pymenta)

A minha está totalmente responsiva, adaptada ao Desktop, smart phones e suas vistas vertical e horizontal.

Uma lição extra que aprendi deste projeto: entrega contínua é importante.

### Tema de Cores Matrix Revolution para Visual Studio Code

Se você usa vscode e é fã dos filmes matrix, eu te convido a baixar meu tema pessoal matrix revolution. Ele está no marketplace do vscode grátis. Até agora, já foram mais de 70 downloads em menos de um mês.

- [Installar Matrix Revolution direto do Marketplace do vscode](https://marketplace.visualstudio.com/items?itemName=PauloSouza.matrix-revolution-color-theme)

## Conheça algumas das minhas soft skills

### Gestor de Projetos na Startup Desenvolve Tributação Municipal Sustentável

Trabalhei como gestor de projetos na empresa DESENVOLVE - TECNOLOGIA, TREINAMENTO E GESTÃO POR RESULTADO PARA ADMINISTRAÇÃO PÚBLICA EIRELI no Estado do Pará durante o ano de 2017 e 2018. Na ocasião, atuei como ponte entre a equipe de desenvolvedores java e o cliente final, os governos municipais.

Por ser uma empresa Businnes to Government, necessitava visitar as secretarias das prefeituras, identificar ineficiências, vulnerabilidades fiscal e jurídica a fim de propor soluções via sistema web e decretos municipais. O objetivo final aqui era fortalecer o Direito municipal.

Portanto, tenho forte expertise em soluções para sturtups. Minha eventual contratação aceleraria a entrada da empresa neste nicho.

Foi o constante contato com a equipe de desenvolvedores que me instigou a me aprofundar em desenvolvimento web com ruby e Rails.

### Pesquisador Científico do CNPq

Fui pesquisador do CNPq pela Universidade Federal do Pará onde, durante os anos de 2013 e 2014, emitia relatório de acompanhamento das finanças públicas de municípios carentes do Pará e apontava distorções na repartição das receitas Fiscais.

Eu tinha uma motivação pessoal para continuar neste projeto até o final. Durante os anos de 2013 e 2014, o município de Melgaço no Pará foi apontato como o mais pobre do Brasil. Isso me instigou a pesquisar a fundo as raízes desse problema.

O diagnóstico a que cheguei me rendeu a premiação descrita no próximo item.

### Premiações

Sou um dos vencedores do **Prêmio SOF de monografias do Tesouro Nacional** do ano de 2016 na modalidade Aperfeiçoamento do Orçamento Público com o tema *As Finanças Públicas das Municipalidades Paraenses em Período Recente: uma análise segundo região de integração de planejamento regional*. Essa habilidade de tratar problemas complexos eu trago para a área do desenvolvimento web.

Caso sua startup seja do setor público, faz muito sentido você acompanhar a metodologia que eu implantei neste artigo. Será muito útil para a construção da sua persona.

[Site para download do artigo premiado pelo Tesouro Nacional](https://repositorio.enap.gov.br/handle/1/4717)

### Certificação

Tenho certificado pela Escola de Idiomas Minds. Tenho facilidade em ler documentação oficial em inglês. Sobre a conversação em inglês, julgo que é boa. Mas preciso de um ambiente que me faça ativar minha *chavezinha* do inglês.

## Comheça minha trajetória profissional

[Como eu, um mestre em economia vim parar no mundo do desenvolvimento web](https://github.com/Pauloparakleto/history)
