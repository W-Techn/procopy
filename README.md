# ProCopy
micro serviço que copia banco de dados com todas as tabelas e dados e monitora os dados atualizando sempre que tiver um dado novo

# Criação de um micro-serviço de Monitoramento

criar um micro-serviço que monitora um banco de dados específico e copie todos os dados e tabela de um banco e grave esses dados em outra tabela ou banco com o mesmo nome ou com um nome diferente especificado no código

Inicialmente esse sistema tem que copiar todos os dado fazendo select de 1000 em 1000 linhas depois que a tabela for totalmente copiada o sistema deverá ficar monitorando para que toda nova linha inserida possa ser copiada para o novo banco de dados

requisitos funcionais
> o sistema deverá ser desenvolvido em Nodejs 
> utilizar es6 
> não utilizar promisses
> utilizar motores de conexão Mysql e MSSql Server
> fazer testes com banco de dados localhost pode ser qualquer banco

