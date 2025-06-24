Imagine que você está desenvolvendo um sistema de pedidos para uma loja virtual. Toda vez que alguém faz uma compra, o sistema precisa registrar o número do pedido, o nome do cliente e o status atual (por exemplo: "Pendente", "Enviado", "Entregue").

Meu papel é representar esse pedido como uma classe, com os principais atributos e um comportamento: permitir que o status seja atualizado conforme o pedido avança.

Criei uma classe chamada Pedido com:

- Propriedade pública NumeroPedido (string).
- Propriedade pública NomeCliente (string).
- Propriedade pública Status (string).
- Um método chamado AtualizarStatus(string novoStatus) para alterar o status.
- Um método chamado ExibirPedido() que mostre os dados na tela.
