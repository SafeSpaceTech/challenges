### Desafio Backend

Esta é a descrição de uma aplicação de teste que faz parte do processo seletivo da SafeSpace para a vaga de Pessoa Desenvolvedora backend com foco em NodeJs.

#### Sobre o projeto

Você deverá construir um serviço de ouvidoria simples que receberá mensagens, anônimas ou não, e que permita consulta através de um código único. A API backend deverá ser desenvolvida preferencialmente em NodeJS utilizando as bibliotecas e frameworks a sua escolha e seguindo os seguintes critérios descritos a seguir.

#### Requisitos

- O serviço deve permitir enviar uma mensagem que poderá ser anônima ou identificada.
- Quando identificada, o usuário deverá fornecer nome e email ao enviar a mensagem.
- Esta mensagem poderá ser classificada como: Sugestão, Reclamação, Dúvida ou Outro.
- Ao enviar uma mensagem, o usuário deve receber um código para acompanhamento.
- Deverá ser possível consultar uma mensagem através do seu código.
- Ao enviar o código do relato a mensagem poderá ser exibida seguindo as seguintes regras de validação:
   - Se for um envio anônimo, retorne um cálculo matemático de simples resolução como 3+9 ou 2x5. O usuário deverá responder corretamente a equação para poder visualizar a mensagem.

  - Se o relato não for anônimo, simule o envio de um PIN de desbloqueio temporário para o email do usuário (não precisa enviar o email de fato, apenas gerar e armazenar um código de desbloqueio e o tempo de expiração deste código). O usuário deverá enviar este código e caso seja válido poderá visualizar a mensagem.

  - Se a validação falhar para qualquer um dos modos de envio, a mensagem não deverá ser exibida.

#### O que será avaliado

- Entendimento dos requisitos.
- Clareza do código das aplicações.
- Uso de boas práticas, arquitetura escolhida e padrões de projeto.
- Segurança.
- Cobertura de Testes.
- Controle de versão utilizando git.
- Iniciativa e Proficiência,
- Documentação.

#### Prazo

O prazo para entrega deste teste deverá ser feita em até 15 dias. O código com a solução poderá ser enviada via ferramenta de controle de versão git (Github, Bitbucket, Gitlab...) em um repositório aberto ou compartilhado com o usuário tech@safe.space com instruções de como executar o projeto.

#### Informações complementares

Fique a vontade para pensar na solução de autenticação se achar que necessário e para utilizar bibliotecas e frameworks que façam sentido para a aplicação.

Itens opcionais mas podem gerar um diferencial na avaliação:
- GraphQL
- Docker