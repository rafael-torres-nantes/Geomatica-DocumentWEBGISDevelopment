# Observatório Pantanal

## Instalação do PostgreSQL e PGAdmin 4.

Primeiramente, baixe o PostgreSQL e mantenha a instalação _default_ do programa. Segue o link para o [Download PostgreSQL](https://www.enterprisedb.com/downloads/postgres-postgresql-downloads).

<p align="center">
  <img src="https://user-images.githubusercontent.com/58231791/197791198-ac02747c-fc13-48bf-bd3b-35881581279c.png" width="720">
<p>
  
Seguindo com o processo, inicie a instalação do _Stack Builder_. No momento do __menu de extensões__, selecione a opção "PostGIS 3.3 Bundle for PostgreSQL 15 (64 bit)". 

<p align="center">
  <img src="https://user-images.githubusercontent.com/58231791/197800152-652cad07-b43e-413e-8d79-81b2d6aaadce.png" width="420">
<p>

Para saber mais sobre o manual aprofundado do PostGis acesse [PostGis WorkShop](https://docs.google.com/presentation/d/1qYXdeCIymLl32uoAHvAPrp1r-hK-_4Z8InG7sHEo6vc/edit?usp=sharing).


## Configuração o PGAdmin 4 e definindo o ambiente

Entre no aplicativo do PGAdmin 4, utilizando a senha definida pelo usuário. Inicialmente, cria-se um _server_ ao qual irá conter o banco de dados.

<p align="center">
  <img src="https://user-images.githubusercontent.com/58231791/198715495-e133441c-8667-4ecf-834b-d6bdad35031a.png" width="720">
<p>
 
Insira o nome do host que irá hospedar o servidor (no caso utilizaremos __localhost__). Além da senha estabelecidade e a porta, no nosso caso:
> 5432
  
<p align="center">
  <img src="https://user-images.githubusercontent.com/58231791/198717192-a057b5cd-0e81-419a-8537-bbd922e2390f.png" width="420">
<p>
