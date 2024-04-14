# NotifyMe

## Descrição
NotifyMe é um sistema de notificação de eventos em tempo real projetado para permitir que usuários se inscrevam e recebam notificações de eventos específicos conforme ocorrem. O sistema visa fornecer um método eficiente e flexível para gerenciar e distribuir notificações para uma base de usuários diversificada.

## Finalidade
Este projeto foi desenvolvido para demonstrar a aplicação de microserviços usando Spring Boot, integrando várias tecnologias modernas para criar um sistema escalável e de alta disponibilidade. NotifyMe serve como uma solução robusta para empresas e desenvolvedores que precisam de um sistema de notificação confiável.

## Regras de Negócio
1. **Cadastro e Autenticação de Usuários**: Usuários devem registrar-se com e-mail e senha. A autenticação é necessária para acessar o sistema.
2. **Gerenciamento de Subscrições**: Usuários podem se inscrever para receber notificações de tipos específicos de eventos. Eles podem cancelar suas subscrições a qualquer momento.
3. **Geração e Distribuição de Notificações**: Notificações são geradas automaticamente quando eventos inscritos ocorrem e são enviadas em tempo real.
4. **Visualização de Notificações**: Usuários podem visualizar e gerenciar suas notificações, marcando-as como lidas e ajustando suas preferências de recebimento.
5. **Segurança**: Todas as interações e dados são protegidos com protocolos de segurança atualizados.

## Tecnologias Utilizadas
- **Spring Boot**: Framework principal para o desenvolvimento de microserviços.
- **Spring Security**: Para autenticação e segurança das APIs.
- **Spring Data JPA**: Para persistência de dados em um banco de dados relacional.
- **Spring Kafka**: Para gerenciamento de mensagens e notificações em tempo real.
- **Redis**: Usado para caching e gerenciamento de sessões.
- **Docker**: Para contêinerização e implantação simplificada.

