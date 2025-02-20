# [Desafio][DIO] MySQL - Ecommerce


# **Objetivo:** <br>
Refine o modelo apresentado acrescentando os seguintes pontos:

:arrow_right: Cliente PJ e PF – Uma conta pode ser PJ ou PF, mas não pode ter as duas informações; <br>
:arrow_right: Pagamento – Pode ter cadastrado mais de uma forma de pagamento; <br>
:arrow_right: Entrega – Possui status e código de rastreio;

# Arquivos :
:link: [e-commerce.pgn](https://github.com/horacioars/Desafio-DIO-Banco-Dados/e-commercio.pgn)
:link: [e-commerce.mwb](https://github.com/horacioars/Desafio-DIO-Banco-Dados/e-commercio.mwb)

![MySQL - ecommerce](https://raw.githubusercontent.com/horacioars/Desafio-DIO-Banco-Dados/refs/heads/main/e-commerce.png)

---

# [Desafio][DIO] Mysql - Oficina

# Descrição do Desafio
Agora você irá criar um esquema conceitual do zero. A partir da narrativa fornecida você será capaz de criar todas as entidades, relacionamentos e atributos. Caso encontre algo que não foi definido na narrativa, utilize a sua compreensão do contexto e deixe uma descrição no README do seu github. para verificação.

O esquema deverá ser adicionado a um repositório do Github para futura avaliação do desafio de projeto. Adicione ao Readme a descrição do projeto conceitual para fornecer o contexto sobre seu esquema.

# Objetivo:
:arrow_right: Cria o esquema conceitual para o contexto de oficina com base na narrativa fornecida

# Narrativa:
:arrow_right: Sistema de controle e gerenciamento de execução de ordens de serviço em uma oficina mecânica
:arrow_right: Clientes levam veículos à oficina mecânica para serem consertados ou para passarem por revisões  periódicas
:arrow_right: Cada veículo é designado a uma equipe de mecânicos que identifica os serviços a serem executados e preenche uma OS com data de entrega.
:arrow_right: A partir da OS, calcula-se o valor de cada serviço, consultando-se uma tabela de referência de mão-de-obra
:arrow_right: O valor de cada peça também irá compor a OSO cliente autoriza a execução dos serviços
:arrow_right: A mesma equipe avalia e executa os serviços
:arrow_right: Os mecânicos possuem código, nome, endereço e especialidade
:arrow_right: Cada OS possui: n°, data de emissão, um valor, status e uma data para conclusão dos trabalhos.
