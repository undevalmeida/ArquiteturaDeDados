># Modelagem de dados

        No power BI existem dois tipos de modelo de organização de tabelas, independente da sua quantidade, 'Tabela Fato' e a 'Tabela Dimensão".
        
## Tabela Dimensão
        Tabela dimensão é composta por mais de uma tabela com caracteristicas do produto. Essas tabelas podem ter suas caracteristicas vinculadas pela 'ID' do produto ou 'CÓDIGO' do produto, funcionando basicamente como o banco de dados, no qual toda tabela existe um PK(Primary Key ou Chave primária) restringindo o produto a chave.
        Exemplo: 
            Tabela Loja: Características -  Loja, endereço, gerente
            Tabela Produtos: Características - SKU, produto, marca, preço unitário
            Tabela Devoluções: Características - SKU, quantidade, data de devolução, loja
            Tabela Vendas: Características - SKU, quantidade vendida, data de venda, loja
        Elas podem ser relacionadas utilizando  a aba de relacionamentos do power BI.
        Outro é que caso não exista essas tabelas separadamente e organizadas. você pode criá-las. 
        
        Mas como consigo criar?
        
        1. Abrir tabela desejada com Power Query
        2. Primeiro passo será duplicar a tabela desejada
        3. Tratar mantendo apenas as colunas que deseja
           1. Página inicial -> Escolher colunas -> selecionar somente as desejadas
        4. Remover tudo que está repetido.
           1. Página inicial -> Reduzir Linhas -> Remover Duplicatas.
        5. Ao finalizar as transformações, fechar e aplicar. 
---
* [Link da Vídeo Aula](https://www.youtube.com/watch?v=hK0iKKhJ16I&list=PLL-6y89GGNdSu9utTLYuzwPGNXQNT0KWm&index=10)