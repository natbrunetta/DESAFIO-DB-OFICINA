Projeto: Sistema de Gestão para Oficina Mecânica


Este projeto foi desenvolvido como parte do desafio da DIO com o objetivo de criar um banco de dados completo para uma oficina mecânica. O desafio consistiu em transformar um modelo conceitual em um esquema lógico relacional, implementá-lo em SQL e desenvolver consultas avançadas para extrair informações estratégicas.

O sistema foi projetado para gerenciar clientes, veículos, ordens de serviço, mecânicos e peças em estoque. O fluxo principal começa quando um cliente agenda um serviço, gerando uma ordem de serviço (OS) que é atribuída a um mecânico. Conforme os serviços são realizados e peças utilizadas, o sistema atualiza automaticamente o valor total da OS e o estoque disponível.

O banco de dados foi estruturado seguindo princípios de normalização para evitar redundâncias, com chaves primárias e estrangeiras bem definidas. Além da criação das tabelas, foram implementados triggers para cálculos automáticos e atualização de estoque, garantindo a integridade dos dados.

Foram desenvolvidas consultas SQL avançadas para fornecer insights valiosos, como análise financeira mensal, desempenho dos mecânicos, controle de estoque e identificação de clientes mais frequentes. Essas queries utilizam junções complexas, agregações, filtros com HAVING e atributos derivados para transformar dados brutos em informações acionáveis.

O projeto está organizado em scripts separados para criação do esquema, inserção de dados de teste e consultas analíticas, facilitando a implementação e testes. O sistema oferece uma base sólida para a gestão eficiente de uma oficina mecânica, permitindo o acompanhamento de todos os aspectos operacionais e financeiros do negócio.

