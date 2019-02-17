# Projeto de Load Dados - Neoway (Teste)

Objetivo:
Desenvolva um serviço de manipulação de dados e persistência em base de dados relacional.


Requisitos:
- Criar um serviço em GO que receba um arquivo csv/txt de entrada (Arquivo Anexo)
- Este serviço deve persistir no banco de dados relacional (postgres) todos os dados contidos no arquivo
  Obs: O arquivo não possui um separador muito convencional
 
- Deve-se fazer o split dos dados em colunas no banco de dados
 Obs: pode ser feito diretamente no serviço em GO ou em sql
 
- Realizar higienização dos dados após persistência (sem acento, maiusculo, etc)
- Validar os CPFs/CNPJs contidos (validos e não validos numericamente)
- Todo o código deve estar disponível em repositório publico do GIT
 
Desejável:
- Utilização das linguagen GOLANG para o desenvolvimento do serviço
- Utilização do DB Postgres
- Docker Conpose , com orientações para executar (arquivo readme) 

Você será avaliado por:
- Utilização de melhores práticas de desenvolvimento (nomenclatura, funções, classes, etc);
- Utilização dos recursos mais recentes das linguagens;
- Boa organização lógica e documental (readme, comentários, etc);
- Cobertura de todos os requisitos obrigatórios.

## Licença

Este material é livre, licenciado sobre a licença Creative Commons <a rel="license" href="http://creativecommons.org/licenses/by-nc/4.0/"><img alt="Licença Creative Commons" style="border-width:0" src="https://i.creativecommons.org/l/by-nc/4.0/88x31.png" /></a> e pode ser utilizado livremente para estudo e em palestras desde que seja dado credito ao autor.
Este material é livre, licenciado sobre a licença Creative Commons <a rel="license" href="http://creativecommons.org/licenses/by-nc/4.0/"><img alt="Licença Creative Commons" style="border-width:0" src="https://i.creativecommons.org/l/by-nc/4.0/88x31.png" /></a> e pode ser utilizado livremente para estudo e em palestras desde que seja dado credito ao autor [Jeff Prestes](https://github.com/jeffprestes).
