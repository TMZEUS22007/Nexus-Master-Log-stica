# Nexus-Master-Logística
Modelo relacional de um sistema de uma empresa de logística fictícia

Membros da equipe: Joaquim Lourenço,Marcos Antônio,Geyson Johannes

**Turma: INFO20**

## Entidades e seus atributos:

- Fornecedores: Endereço;Nome;Produtos
- Armazenamento: Controle de inventário;Armazéns;Inventário dos produtos;Capacidade de armazenamento
- Distribuição: Centros de distribuição:Controle de entregas;Estratégias de distribuição
- Custos: Custos de transporte;Custos de armazenamento;Orçamento logístico
- Transporte: Frota;Rotas e motoristas;Modalidade
- Segurança: Monitoramento;Garantia
- Clientes: Nome;Número do pedido;Feedback;Código de identificação:Endereço;

# Entidades e seus relacionamentos:

- Fornecedores -> Repassam produtos para serem entregues -> Armazenamento
- Armazenamento -> Repassa os produtos para realizar a distribuição  -> Distribuição
- Distribuição -> Repassa os produtos selecionados para a avaliação do orçamento -> Custos
-Custos -> Prepara os produtos para a entrega após concluir o orçamento logístico -> Transporte
- Transporte -> Leva os produtos para os destinatários,garantindo sua entrega em segurança -> Segurança
-Segurança -> Entrega os produtos para os clientes com segurança e garantia -> Clientes
