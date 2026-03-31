# Projeto Integrador - Modelo
*(Coloque aqui o nome do seu projeto.)*

Um modelo para o desenvolvimento do Projeto Integrador do Curso de Técnico em Desenvolvimento de Sistemas para a Internet Integrado ao Ensino Médio do IFC - Campus Araquari.
*(Coloque aqui uma breve descrição do seu projeto.)*

**IMPORTANTE**: [**Cadastre seu projeto nesta planilha**](https://docs.google.com/spreadsheets/d/1bSb1-S9qOf46fNH8quyoFpcjcTuBMj_EdSPchOuFULY/edit?usp=sharing).

Professor: [Marco André Mendes](github.com/marcoandre)

Equipe:
- [Kauã Martins Baarros]

Links do projeto:
(*Coloque aqui os links para a documentação do projeto e os repositórios e plubicação do backend e frontend.*)
-   [Documentação (esse documento)](github.com/marcoandre/pi-modelo)
-   Backend: [Repositório](https://github.com/kauabarros-24/haircut.git) e [Publicação](https://pi-backend.herokuapp.com/)
-   Frontend: [Repositório](https://github.com/kauabarros-24/haircut-Frontend.git) e [Publicação](https://pi-frontend.herokuapp.com/)

# 1. Desenvolvimento
1.1 Modelos de Sistemas
1.1.3 Ordem de Serviço (O.S.)

Descrição do sistema e motivo da escolha

O sistema escolhido para desenvolvimento foi o de Ordem de Serviço (O.S.), adaptado para um contexto moderno com uso de inteligência artificial.

A escolha foi feita porque o sistema permitirá gerenciar atendimentos relacionados a cortes de cabelo e simulações visuais, organizando solicitações de clientes, geração de imagens e acompanhamento dos pedidos. Além disso, esse modelo se encaixa perfeitamente na proposta do projeto, que envolve prestação de serviço ao cliente.

# 2. Situação-Problema
Introdução

A empresa fictícia escolhida é a Kalium Hair AI, uma startup que oferece simulação de cortes de cabelo utilizando inteligência artificial. O serviço permite que clientes enviem uma foto e recebam uma prévia de como ficariam com diferentes estilos de cabelo.

A empresa é recente e conta com uma pequena equipe: um desenvolvedor responsável pela IA, um atendente e um gestor.

Situação-Problema

Atualmente, o processo de atendimento da Kalium Hair AI é desorganizado e pouco eficiente. Os clientes enviam suas fotos e pedidos através de mensagens (como WhatsApp ou redes sociais), informando o tipo de corte desejado.

O atendente recebe essas solicitações manualmente e encaminha para o desenvolvedor ou sistema de geração de imagens. Muitas vezes, as informações chegam incompletas ou confusas, dificultando o processamento.

Além disso, não há um controle adequado das solicitações. Não é possível acompanhar facilmente quais pedidos já foram processados, quais estão pendentes ou quais já foram entregues ao cliente.

Outro problema é a falta de histórico. Quando um cliente deseja testar novos cortes, não há um registro organizado das imagens geradas anteriormente.

Também não existem relatórios ou métricas, como quantidade de simulações realizadas, tipos de cortes mais solicitados ou tempo médio de entrega.

Conclusão

Com base nessa situação, é evidente que a falta de organização compromete a eficiência do serviço e a experiência do cliente.

Um sistema de Ordem de Serviço integrado com inteligência artificial poderia automatizar o fluxo de atendimento, organizar as solicitações, armazenar históricos e melhorar significativamente a produtividade e qualidade do serviço.

# 3. Descrição da Proposta

O sistema proposto será uma plataforma de simulação de cortes de cabelo com inteligência artificial, integrada a um gerenciamento de ordens de serviço.

O foco principal será permitir que clientes enviem suas fotos e recebam imagens geradas por IA com diferentes estilos de corte, de forma rápida e organizada.

O sistema contará com dois níveis de usuário:

Administrador: responsável por gerenciar o sistema, visualizar relatórios, acompanhar todas as solicitações e configurar o funcionamento da IA.
Usuário/Cliente: poderá enviar sua foto, escolher o tipo de corte desejado e visualizar os resultados gerados.

No sistema, será possível:

Enviar fotos para simulação de cortes;
Inserir descrições de cortes desejados (prompt);
Gerar imagens automaticamente com IA;
Acompanhar o status da solicitação (processando, concluído);
Visualizar histórico de simulações realizadas;
Gerenciar solicitações em um painel administrativo;
Gerar relatórios básicos de uso da plataforma.

Com esse sistema, o processo será automatizado, organizado e escalável, permitindo que a empresa atenda mais clientes com maior eficiência e qualidade.
