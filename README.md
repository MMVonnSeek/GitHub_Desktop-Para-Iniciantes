# **Criando seu primeiro repositório usando o GitHub Desktop**

> ## Aprenda como configurar, autenticar o GitHub Desktop para Windows e permitir que você contribua em projetos diretamente da sua máquina.

![Max Müller](https://img.shields.io/badge/Autor-Max%20M%C3%BCller-blue?style=for-the-badge&logo=github)
![GitHub Desktop](https://img.shields.io/badge/GitHub%20Desktop-Tutorial-8023F9?style=for-the-badge&logo=github)
![Step by Step](https://img.shields.io/badge/Aprendizado-Passo%20a%20Passo-orange?style=for-the-badge&logo=gitbook)


## Introdução
O GitHub Desktop é um aplicativo gratuito e de código aberto que ajuda você a trabalhar com código hospedado no GitHub ou em outros serviços de hospedagem Git. Com o GitHub Desktop, você pode executar comandos do Git, como fazer commits e push de alterações, em uma interface gráfica do usuário, em vez de usar a linha de comando. Para mais informações, consulte Sobre o GitHub Desktop .

Ao final deste guia, você terá usado o GitHub Desktop para criar um repositório, fazer alterações no repositório e publicar as alterações no GitHub.

Após instalar o GitHub Desktop e fazer login no GitHub ou GitHub Enterprise, você poderá criar e clonar um repositório de tutoriais. O tutorial apresentará os conceitos básicos de trabalho com o Git e o GitHub, incluindo a instalação de um editor de texto, a criação de uma branch, a criação de um commit, o envio para o GitHub e a abertura de um pull request. O tutorial está disponível caso você ainda não tenha nenhum repositório no GitHub Desktop.

Recomendamos concluir o tutorial, mas se você quiser explorar o GitHub Desktop criando um novo repositório, este guia o orientará no uso do GitHub Desktop para trabalhar em um repositório Git.

## Parte 1: Instalando o GitHub Desktop e autenticando sua conta
Você pode instalar o GitHub Desktop em qualquer sistema operacional compatível. Após instalar o aplicativo, você precisará fazer login e autenticar sua conta no GitHub ou GitHub Enterprise antes de criar e clonar um repositório de tutoriais.

Para obter mais informações sobre instalação e autenticação, consulte Configurando o GitHub Desktop .

## Parte 2: Criando um novo repositório
Se você não tiver nenhum repositório associado ao GitHub Desktop, verá uma visualização "Vamos começar!", onde poderá escolher criar e clonar um repositório de tutoriais, clonar um repositório existente da Internet, criar um novo repositório ou adicionar um repositório existente do seu disco rígido.
![lets-get-started](https://github.com/user-attachments/assets/3cd68c4a-a5c2-4e0d-afc9-954dba5ef85c)

### Criando e clonando um repositório de tutoriais
Recomendamos que você crie e clone um repositório de tutoriais como seu primeiro projeto para praticar o uso do GitHub Desktop.

1. Clique em Criar um repositório de tutoriais... .
2. Siga as instruções do tutorial para instalar um editor de texto, criar uma ramificação, editar um arquivo, fazer um commit, publicar no GitHub e abrir uma solicitação de pull.

### Criando um novo repositório
Se não desejar criar e clonar um repositório de tutoriais, você pode criar um novo repositório.

1. Clique em Criar um novo repositório no seu disco rígido... .
2. Na janela "Criar um novo repositório", preencha os campos e selecione suas opções preferidas.
+ "Nome" define o nome do seu repositório localmente e no GitHub.
+ "Descrição" é um campo opcional que você pode usar para fornecer mais informações sobre a finalidade do seu repositório.
+ "Caminho local" define a localização do seu repositório no seu computador. Por padrão, o GitHub Desktop cria uma pasta do GitHub dentro da sua pasta Documentos para armazenar seus repositórios, mas você pode escolher qualquer local no seu computador. Seu novo repositório será uma pasta dentro do local escolhido. Por exemplo, se você nomear seu repositório como " " Tutorial, uma pasta chamada " Tutorial " será criada dentro da pasta que você selecionou para o seu caminho local. O GitHub Desktop lembrará o local escolhido na próxima vez que você criar ou clonar um novo repositório.
+ Inicializar este repositório com um README cria um commit inicial com um arquivo README.md . Os READMEs ajudam as pessoas a entender o propósito do seu projeto, por isso recomendamos selecionar esta opção e preenchê-la com informações úteis. Quando alguém visita seu repositório no GitHub, o README é a primeira coisa que verá ao aprender sobre o seu projeto. Para mais informações, consulte Sobre os READMEs .
+ O menu suspenso "Ignorar" do Git permite adicionar um arquivo personalizado para ignorar arquivos específicos no seu repositório local que você não deseja armazenar no controle de versão. Se você usar uma linguagem ou framework específico, poderá selecionar uma opção na lista disponível. Se você está apenas começando, sinta-se à vontade para pular esta seleção. Para mais informações, consulte " Ignorando arquivos" .
+ O menu suspenso Licença permite adicionar uma licença de código aberto a um arquivo LICENSE no seu repositório. Você não precisa se preocupar em adicionar uma licença imediatamente. Para obter mais informações sobre as licenças de código aberto disponíveis e como adicioná-las ao seu repositório, consulte Licenciando um repositório .
3. Clique em Criar repositório .

## Parte 3: Explorando o GitHub Desktop
No menu Arquivo, na parte superior da tela, você pode acessar as configurações e ações que pode executar no GitHub Desktop. A maioria das ações também possui atalhos de teclado para ajudar você a trabalhar com mais eficiência. Para obter uma lista completa de atalhos de teclado, consulte Atalhos de teclado do GitHub Desktop .

### A barra de repositório do GitHub Desktop
Na parte superior do aplicativo GitHub Desktop, você verá uma barra que mostra o estado atual do seu repositório.
![explore-github-desktop](https://github.com/user-attachments/assets/e45d765e-cd8d-4647-9292-802c22efc817)

Captura de tela do aplicativo GitHub Desktop. Uma barra mostrando detalhes do repositório "hello-world" ocupa a parte superior da janela e está contornada em laranja.

+ O repositório atual mostra o nome do repositório em que você está trabalhando. Você pode clicar em Repositório atual para alternar para um repositório diferente no GitHub Desktop.
+ A ramificação atual mostra o nome da ramificação em que você está trabalhando. Você pode clicar em "Ramal atual" para visualizar todas as ramificações no seu repositório, alternar para uma ramificação diferente ou criar uma nova. Depois de criar pull requests no seu repositório, você também pode visualizá-las clicando em "Ramal atual" .
+ Publicar repositório aparece porque você ainda não publicou seu repositório no GitHub, o que será feito posteriormente na próxima etapa. Esta seção da barra mudará com base no status da sua ramificação e repositório atuais. Diferentes ações dependentes do contexto estarão disponíveis para permitir a troca de dados entre seus repositórios locais e remotos.
### Mudanças e História
Na barra lateral esquerda, você encontrará as visualizações Alterações e Histórico .
![changes-and-history](https://github.com/user-attachments/assets/a7754c9b-6882-4a5b-a1cd-9acecfe2a6da)

Captura de tela do aplicativo GitHub Desktop. Uma barra lateral à esquerda, com as abas "Alterações" e "Histórico", está destacada em laranja.

+ A visualização Alterações mostra as alterações que você fez nos arquivos da sua ramificação atual, mas que ainda não foram submetidas ao seu repositório local. Na parte inferior, há uma caixa com as caixas de texto "Resumo" e "Descrição" e um botão " Submeter à RAMIFICAÇÃO " . É aqui que você submeterá as novas alterações. O botão " Submeter à RAMIFICAÇÃO" é dinâmico e exibirá para qual ramificação você está submetendo as alterações.
+ A visualização Histórico mostra os commits anteriores na ramificação atual do seu repositório. Você deverá ver um "commit inicial" criado pelo GitHub Desktop quando você criou seu repositório. À direita do commit, dependendo das opções selecionadas ao criar seu repositório, você poderá ver os arquivos .gitattributes , .gitignore , LICENSE ou README. Você pode clicar em cada arquivo para ver um diff para aquele arquivo, que contém as alterações feitas no arquivo naquele commit. O diff mostra apenas as partes do arquivo que foram alteradas, não todo o conteúdo do arquivo.
## Parte 4: Publicando seu repositório no GitHub
Ao criar um novo repositório, ele só existe no seu computador e você é o único que pode acessá-lo. Você pode publicar seu repositório no GitHub para mantê-lo sincronizado em vários computadores e permitir que outras pessoas o acessem. Para publicar seu repositório, envie suas alterações locais para o GitHub.

1. Na barra de repositório, clique em Publicar repositório .
![publish-repository](https://github.com/user-attachments/assets/3e356834-50cf-4a66-b468-e7c66598fbdb)
2. Captura de tela da barra de repositórios. Um botão, denominado "Publicar repositório", é destacado com um contorno laranja.
Na janela "Publicar repositório", insira detalhes para seu novo repositório.
+ O GitHub Desktop preenche automaticamente os campos "Nome" e "Descrição" com as informações que você inseriu ao criar o repositório.
+ Manter este código privado permite que você controle quem pode visualizar seu projeto. Se você deixar esta opção desmarcada, outros usuários no GitHub poderão visualizar seu código. Se você selecionar esta opção, seu código não ficará disponível publicamente.
+ O menu suspenso Organização , se presente, permite que você publique seu repositório em uma organização específica à qual você pertence no GitHub.
a. Clique em Publicar Repositório .
b. Você pode acessar o repositório no GitHub a partir do GitHub Desktop. No menu Arquivo, clique em Repositório e, em seguida, em Exibir no GitHub . Isso o levará diretamente ao repositório no seu navegador padrão.
## Parte 5: Fazer, comprometer e impulsionar mudanças
Agora que você criou e publicou seu repositório, está pronto para fazer alterações em seu projeto e começar a elaborar seu primeiro commit em seu repositório.

1. Para iniciar seu editor externo a partir do GitHub Desktop, na barra de menu "GitHub Desktop", selecione Repositório e clique em Abrir no EDITOR . Para obter mais informações, consulte Configurando um editor padrão no GitHub Desktop .
![open-in-editor](https://github.com/user-attachments/assets/9a322c79-b424-48fd-bbf1-3aaf2254eded)
Captura de tela de uma barra de menus em um Mac. No menu suspenso "Repositório", um cursor passa sobre "Abrir no Visual Studio Code", destacado em azul.
2. Faça algumas alterações no arquivo README.md que você criou anteriormente. Você pode adicionar informações que descrevam seu projeto, como o que ele faz e por que é útil. Quando estiver satisfeito com as alterações, salve-as no seu editor de texto.

2. No GitHub Desktop, navegue até a visualização "Alterações" . Na lista de arquivos, você deverá ver o arquivo README.md . A caixa de seleção à esquerda do arquivo README.md indica que as alterações feitas nele farão parte do commit que você fizer. No futuro, você poderá fazer alterações em vários arquivos, mas só desejará fazer o commit das alterações feitas em alguns deles. Se você clicar na caixa de seleção ao lado de um arquivo, esse arquivo não será incluído no commit.
![viewing-changes](https://github.com/user-attachments/assets/edbf6569-99d4-4dbc-8354-f87c18e7a91d)
Captura de tela da aba "Alterações" na barra lateral. À esquerda do arquivo "README.md", uma caixa de seleção selecionada é destacada com um contorno laranja.
4. Na parte inferior da lista de Alterações , insira uma mensagem de commit. À direita da sua foto de perfil, digite uma breve descrição do commit. Como estamos alterando o arquivo README.md , "Adicionar informações sobre o propósito do projeto" seria um bom resumo do commit. Abaixo do resumo, você verá um campo de texto "Descrição", onde poderá digitar uma descrição mais longa das alterações no commit, o que é útil ao rever o histórico de um projeto e entender por que as alterações foram feitas. Como você está fazendo uma atualização básica de um arquivo README.md , pode pular a descrição.

![commit-message](https://github.com/user-attachments/assets/ee06eccc-7a1b-4f7e-a032-0f2d2fd27a4d)

Captura de tela da aba "Alterações" na barra lateral. À direita da foto do perfil, um campo de texto contendo uma mensagem de confirmação é destacado em laranja.
5. Abaixo da sua mensagem de commit, clique em Commit to BRANCH NAME . O botão de commit mostra sua branch atual para que você tenha certeza de que fará o commit na branch desejada.

6. Para enviar suas alterações para o repositório remoto no GitHub, clique em Enviar origem .
![push-to-origin](https://github.com/user-attachments/assets/74d42791-db86-4a84-8a66-430438dfd0e2)


Captura de tela da barra de menu "Repositório". Um botão, denominado "Push Origin", é destacado com um contorno laranja.
+ O botão "Push Origin" é o mesmo que você clicou para publicar seu repositório no GitHub. Este botão muda de acordo com o contexto em que você está no fluxo de trabalho do Git. Agora, ele deve exibir Push originum " 1ao lado", indicando que há um commit que não foi enviado para o GitHub.
+ A "origem" em " Push Origin" significa que você está enviando as alterações para o repositório remoto chamado origin, que neste caso é o repositório do seu projeto no GitHub. Até que você envie novos commits para o GitHub, haverá diferenças entre o repositório do seu projeto no seu computador e o repositório do seu projeto no GitHub. Isso permite que você trabalhe localmente e envie suas alterações para o GitHub somente quando estiver pronto.
7. Na janela à direita da visualização Alterações , você verá sugestões de ações que você pode realizar em seguida. Para abrir o repositório no GitHub no seu navegador, clique em Exibir no GitHub .
![available-actions](https://github.com/user-attachments/assets/60e5e06c-ddf3-484e-8057-777761037c03)


Captura de tela da tela "Sem alterações locais". Em uma lista de sugestões, um botão, denominado "Exibir no GitHub", é destacado com um contorno laranja.
8. No seu navegador, clique em 2 commits . Você verá uma lista dos commits neste repositório no GitHub. O primeiro commit deve ser o que você acabou de fazer no GitHub Desktop.

Captura de tela da página do repositório no GitHub. Acima da lista de arquivos e ao lado de um ícone de relógio, um link, rotulado "2 commits", está destacado em laranja.
![click-two-commits](https://github.com/user-attachments/assets/25da346e-0a27-4ed4-a65b-795607a3186d)

## Conclusão
Agora você criou um repositório, publicou-o no GitHub, fez um commit e enviou suas alterações para o GitHub. Você pode seguir esse mesmo fluxo de trabalho ao contribuir para outros projetos que você cria ou nos quais colabora.

#### Se este projeto ajudou você a evoluir, deixe uma ⭐ e compartilhe o conhecimento. Obrigado por usar este repositório!
