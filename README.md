# IaaS, PaaS, SaaS e o Modelo de Responsabilidade Compartilhada no Microsoft Azure

## IaaS (Infrastructure as a Service)

- **Descrição**: Fornece infraestrutura de TI virtualizada através da internet.
- **Recursos típicos**: Máquinas virtuais, redes, armazenamento, e sistemas operacionais.
- **Responsabilidade do cliente**: Gerenciar o sistema operacional, aplicações, dados e configurações.
- **Exemplo no Azure**: Azure Virtual Machines (VMs).

## PaaS (Platform as a Service)

- **Descrição**: Fornece uma plataforma para desenvolvimento, execução e gerenciamento de aplicações sem se preocupar com a infraestrutura.
- **Recursos típicos**: Serviços de banco de dados, ambiente de desenvolvimento, gerenciamento de API.
- **Responsabilidade do cliente**: Gerenciar apenas as aplicações e dados.
- **Exemplo no Azure**: Azure App Service, Azure SQL Database.

## SaaS (Software as a Service)

- **Descrição**: Software completo entregue pela internet, acessado via navegador ou aplicativo.
- **Recursos típicos**: Aplicações prontas para uso como e-mail, CRM, colaboração.
- **Responsabilidade do cliente**: Usar o software e proteger os dados do usuário.
- **Exemplo no Azure**: Microsoft 365, Dynamics 365.

---

## Modelo de Responsabilidade Compartilhada no Microsoft Azure

No Azure, a responsabilidade pela **segurança e gerenciamento** é dividida entre o **provedor de nuvem (Microsoft)** e o **cliente**, variando conforme o tipo de serviço:

| Elemento                      | IaaS                  | PaaS                 | SaaS                  |
|------------------------------|-----------------------|----------------------|-----------------------|
| Segurança física             | Microsoft             | Microsoft            | Microsoft             |
| Rede e hardware              | Microsoft             | Microsoft            | Microsoft             |
| Sistema operacional          | Cliente               | Microsoft            | Microsoft             |
| Aplicações                   | Cliente               | Cliente              | Microsoft             |
| Dados                        | Cliente               | Cliente              | Cliente               |
| Identidade e acesso          | Cliente               | Cliente              | Cliente               |
| Conformidade de dados        | Compartilhada         | Compartilhada        | Compartilhada         |

- **Importante**: O cliente é sempre responsável pelos **dados, identidade e acesso**.
- O nível de controle e responsabilidade **diminui conforme se sobe de IaaS para SaaS**.

---
