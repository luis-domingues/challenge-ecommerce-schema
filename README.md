## Database Schema Challenge ✏
O projeto consiste em modelar o conceito de um banco de dados de um e-commerce fictício, onde produtos são vendidos por diferentes vendedores, incluindo funcionalidades básicas no modelo, como:
- **Produtos**: Comercializados por diferentes vendedores e associados a um fornecedor.
- **Clientes**: Podem ser Pessoas Físicas (PF) ou Jurídicas (PJ), mas não ambos.
- **Pedidos**: Um pedido pode ser composto por um ou mais produtos e tem um status de entrega e pagamento.
- **Fornecedores**: Cada produto está associado a um fornecedor específico.
- **Formas de Pagamento**: O cliente pode ter múltiplas formas de pagamento associadas a um pedido.
- **Rastreamento de Entregas**: As entregas possuem status e código de rastreio.

### Requisitos de refinamento solicitados
1. **Cliente PJ e PF**: Diferenciação entre clientes Pessoa Física (PF) e Pessoa Jurídica (PJ). Uma conta pode ser de um tipo ou de outro, mas não ambas.
2. **Pagamento**: O cliente pode cadastrar múltiplas formas de pagamento (cartão de crédito, boleto, Pix, etc.) e associá-las ao pedido.
3. **Entrega**: O sistema deve manter o status da entrega e o código de rastreamento do pedido.

![20240909_140709(4)](https://github.com/user-attachments/assets/19767163-86ac-4814-9e38-a214a92da874)

> [!NOTE]
> O modelo foi feito com a ferramenta [Miro](https://miro.com/pt/).

## Licença
Este projeto está licenciado sob a licença MIT - veja o arquivo [LICENSE](https://github.com/luis-domingues/challenge-ecommerce-schema/blob/main/LICENSE.md) para mais detalhes.
