# NotifyMe

## Descrição
NotifyMe é um sistema de notificação de eventos em tempo real projetado para permitir que usuários se inscrevam e recebam notificações de eventos conforme ocorrem. O sistema utiliza uma arquitetura de microserviços com uma abordagem de Domain-Driven Design (DDD) para garantir que cada componente seja bem encapsulado e mantenha um foco claro nas regras e lógicas de negócios.

## Finalidade
Este projeto foi desenvolvido para demonstrar a aplicação de arquitetura de microserviços e DDD, integrando várias tecnologias modernas para criar um sistema escalável e de alta disponibilidade. NotifyMe serve como uma solução robusta para empresas e desenvolvedores que precisam de um sistema de notificação confiável e eficiente.

## Regras de Negócio
1. **Cadastro e Autenticação de Usuários**: Usuários devem se registrar fornecendo um e-mail e senha. A autenticação é necessária para acessar o sistema.
2. **Gerenciamento de Subscrições**: Usuários podem se inscrever para receber notificações de tipos específicos de eventos. Eles podem cancelar suas subscrições a qualquer momento.
3. **Geração e Distribuição de Notificações**: Notificações são geradas automaticamente quando eventos inscritos ocorrem e são enviadas em tempo real.
4. **Pesquisa Avançada de Notificações**: Usuários podem realizar pesquisas complexas nas notificações recebidas, filtrando por conteúdo, data, tipo de evento, etc.
5. **Análise de Dados**: Dashboards analíticos fornecem insights sobre o comportamento dos usuários e a eficácia das notificações.

## Tecnologias Utilizadas
- **Spring Boot**: Framework principal para o desenvolvimento de microserviços.
- **PostgreSQL**: Usado para gerenciar dados de usuários e subscrições, aproveitando suas capacidades transacionais.
- **Cassandra**: Utilizado para armazenar logs de eventos e notificações devido à sua alta escalabilidade e performance em escrita.
- **Elasticsearch**: Aplicado para permitir pesquisa rápida e eficiente, bem como funcionalidades de análise de grandes volumes de dados.
- **Spring Security**: Para autenticação e segurança das APIs.
- **Spring Data JPA**: Para integração com PostgreSQL.
- **Spring Data Cassandra**: Para interação com o Cassandra.
- **Spring Data Elasticsearch**: Para integração com Elasticsearch.

