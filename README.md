 # Análise Exploratória de Dados com Python - Telecom

### Projeto Telecom

`Problema`

Imaginamos uma empresa de telecom que tem clientes de vários serviços diferentes, entre os principais: `INTERNET` e `TELEFONE`.

O problema é que, analisando o histórico desses clientes nos últimos anos, percebeu-se que a empresa está com `CHURN` de mais de 26%.

Isso representa uma perda de milhões para a empresa.

O que a empresa precisa fazer para resolver isso?

----------------------------------------------------------------------------------------------------------------------------------------------------

1. Entendimento do problema
2. Escrita do passo a passo da lógica de programação para depois passar para o código
3. Leitura e entendimento da base de dados
4. Análise das informações de tipagem e dados ausentes
5. Análise inicial para confirmar se o problema exposto confere com os dados
6. Análise detalhada por meio de gráficos para fácil entendimento e visualização
7. Conclusão e proposta de ações

-----------------------------------------------------------------------------------------------------------------------------------------------------

### Informações

`Origem:` /dataset/telecom_users.csv

`Python Interpreter:` python 3.9.7 64-bit

`Bibliotecas Utilizadas:` pandas / plotly

-----------------------------------------------------------------------------------------------------------------------------------------------------

### Conclusões e Ações

- Clientes com `contrato mensal` tem muito mais chance de cancelar
Ação: Podemos fazer promoções para o cliente ir para o contrato anual
    
- `Famílias maiores` tendem a cancelar menos do que famílias menores
Ação: Podemos fazer promoções pra pessoa pegar uma linha adicional de telefone
    
- Clientes com `pouco tempo de utilização do serviço` tendem a cancelar muito mais
    - A primeira experiência do cliente na operadora pode ser ruim
    - Talvez a captação de clientes está trazendo clientes desqualificados
Ação: Podemos criar incentivo para fidelizar o cliente
    
- Quanto `mais serviços contratados` a pessoa tem, menos chance dela cancelar
Ação: Podemos fazer promoções com mais serviços para o cliente
    
- `Serviço de Fibra` faz com os clientes cancelem mais
Ação: Agir sobre este serviço
    
- Clientes que têm como `forma de pagamento o boleto bancário`, têm muito mais chance de cancelar
Ação: Propor alguma ação para eles migrarem para as outras formas de pagamento

---------------------------------------------------------------------------------------------------------------------------------------------------