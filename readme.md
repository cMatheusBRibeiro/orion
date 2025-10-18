# Orion

Plataforma dedicada à gerenciamento de pedidos e pagamentos.

## Funcionalidades

**Obs:** As funcionalidades descritas a seguir podem sofrer alterações, sendo definir melhor a regra de negócio, adicionar novos requisitos, remover requisitos, diminuir os requisitos e entre outras mudanças.

### Produtos

|    | ID     | Requisito                        | Descrição                                                    |
| -- | ------ | -------------------------------- | ------------------------------------------------------------ |
| [] | REF001 | Criação de produtos              | Permitir o usuário cadastrar novos produtos                  |
| [] | REF002 | Listagem de produtos             | Permitir o usuário buscar pelos produtos que criou           |
| [] | REF003 | Remoção de produtos              | Permitir o usuário remover os produtos que ele havia criado  |
| [] | REF004 | Atualização de produtos          | Permitir o usuário atualizar as informações de seus produtos |
| [] | REF005 | Controle de estoque              | Permitir o usuário gerenciar o estoque de seus produtos      |
| [] | REF006 | Cache de produtos mais acessados | Deve criar cache dos produtos mais acessados                 |



### Pagamentos

- [] Adicionar pagamento com um boleto bancário;
- [] Adicionar pagamento com outro boleto bancário;
- [] Adicionar pagamento via pix;
- [] Adicionar pagamento via cartão de crédito;
- [] Adicionar pagamento com dois cartões de crédito;

### Pedidos

- [] Criação de pedidos;
- [] Atualização de status de pedidos;
- [] Envio e rastreamento;
- [] Histórico de eventos;

### Notificações

- [] Envio de e-mail;
- [] Template dinâmico (pedido pago, boleto emitido, etc);
- [] Reenvio automático;

### Observabilidade e Monitoramento

- [] Logs estruturados;
- [] Métricas;
- [] Tracing distribuídos;
- [] Alertas;

### Arquitetura

- [] API Gateway;
- [] Rate Limiting;
- [] Auditoria;
- [] Histórico de ações;
- [] Feature flags;