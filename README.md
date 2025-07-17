# Django-Final
projeto-django
Entrega projeto final


Entrega final
Em forma individual, você criará um aplicativo web estilo blog programado em Python com Django. Este site terá admin, perfis, registro, páginas e formulários.

Briefing

Ter algum acesso visível à visualização de "Sobre mim", onde haverá informações sobre o proprietário da página, acessível na rota about/.

Ter algum acesso visível à visualização de blogs que deve ser hospedada na rota pages/.

Acessar uma tela que conterá as páginas. Ao clicar em “Leia mais”, deve navegar para o detalhe da página através de uma rota pages/.

Se não houver nenhuma página, mostrar "Ainda não há páginas".

Para editar ou excluir páginas, você deve estar logado.

Peças sugeridas

Recomendamos incluir:

NavBar

Home

Sobre

Páginas

Login

Inscrever-se

Mensagens

Perfil

Logout

Obter páginas

Obter página

Criar página

Atualizar página

Excluir página

Obter perfil

Atualizar perfil

Requisitos básicos

Os requisitos básicos serão parte dos critérios de avaliação para aprovação do projeto.

Tenha em mente que os requisitos nomeiam um modelo principal para que, caso você queira mudar de blog para outro tema, possa fazê-lo desde que atenda aos requisitos.

Entrega individual

Subir para o GitHub

Readme como a entrega 3

Vídeo de no máximo 10 minutos que mostre a página e suas funcionalidades (com ou sem áudio)

programas que podem ser utilizados freecam8, obs, filmora 12, etc.

Não adicionar o Banco de Dados (o arquivo db.sqlite3) na entrega. Ele deve estar no .gitignore.

Uso de herança de templates. No template base, implemente a tag de navegação nav que contém os acessos que você achar necessários para sua página.

Existir gitignore com:

pycache

db.sqlite3

media

Os últimos são para o fato de não compartilhar a informação do seu bd e, além disso, as imagens são arquivos muito pesados que não é recomendável ter no repositório. Por outro lado, as imagens que fazem parte do código do projeto devem ser armazenadas na pasta static.

Existência do arquivo requirements.txt atualizado.

Tenha em mente que ao lidar com formulários com imagens, é necessário adaptar o template e a visualização... não apenas o modelo e o formulário.

Uso de no mínimo 2 classes baseadas em visualização.

Uso de no mínimo um mixin em um CBV e um decorador em uma visualização comum.

Uma visualização de início/home.

Acesso a uma visualização "Sobre mim"/"About".

Criar um modelo principal (Blog/Post/Carro/Vendedor/Professor/etc.) que contenha os seguintes campos, no mínimo: 2 Charfield, 1 de texto enriquecido (usando ckeditor), 1 campo de imagem, 1 de data.

Visualização da lista de objetos do modelo principal (modelo à escolha). No qual cada objeto mostrará apenas alguns de seus dados.

Mensagem de aviso no caso de não haver nenhum objeto criado ou ao utilizar o mecanismo de pesquisa não encontrar nenhum objeto.
A partir da lista:
poder acessar uma visualização que mostre o detalhe do objeto selecionado

poder acessar uma visualização de criação, uma de edição e uma de exclusão de objetos.



Registre na seção de admin todos os modelos criados.

Ter um aplicativo (accounts/contas/etc.) para gerenciar todas as visualizações relacionadas ao usuário/autenticação.

Desenvolver as visualizações para um login, um logout e um registro para usuários. Neste último, deve-se solicitar: nome de usuário, email, senha.

Criar uma visualização de perfil onde os dados do usuário são exibidos:
nome

sobrenome

email

avatar

biografia/link/data de nascimento/etc.


Do perfil, crie um acesso a uma visualização de edição desses dados. Adicionar a alteração de senha.

Criar um aplicativo de mensagens com tudo o que for necessário para que os usuários possam se comunicar entre si por mensagens. Tudo neste aplicativo é a critério do aluno, desde que funcione corretamente.

TESTE, TESTE E TESTE ANTES DE ENVIAR O CÓDIGO PARA O GITHUB... (não se apresse para fazer o commit e enviar as alterações porque pode causar algum problema sem perceber)

Requisitos Extra

Os requisitos extra para pro-coders não estão incluídos nos critérios de avaliação.

Os requisitos extras são funcionalidades opcionais que não são incluídas nos critérios de avaliação, mas se você estiver entediado e quiser adicionar valor ao seu projeto... sob a única condição de que o que você incluir deve funcionar!

Messenger e like - integração com outro db

Não faça

Não é necessário nem recomendado.

Usar Python puro para o projeto final (espera-se o uso de Django).

Formato de Avaliação
Cada critério será avaliado de 0,5 a 2,5 pontos, conforme o nível de detalhe e qualidade apresentado.

A pontuação total máxima é de 22,5 pontos.

A entrega deve ser organizada em um documento ou link que permita o acesso ao site desenvolvido.

O arquivo deve ser nomeado como: “Nome e sobrenome + PF + Blog”, ex.: “Luke Skywalker - PF - Blog”.

Habilitar a opção de comentários no arquivo para feedbacks e incorporar elementos de design consistentes com o branding do site.

Confira a lista de verificação da entrega aqui
