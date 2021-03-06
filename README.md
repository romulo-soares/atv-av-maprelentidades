## Atividade Avaliativa - ``Mapeamento e Relacionamento de Entidades``

#### Dupla: ``Jozimar Soares`` e ``Rômulo Soares``

##### Instruções para Implantação

###### Cenário 1 - ``NÃO TEM IMPLANTAÇÃO``

> 1. Acesse o arquivo ``der-cenario1.png`` no diretório ``/atv-av-maprelentidades/cenario1`` para vizualizar o **DER** do dóminio de negócio.

> 2. Para obter acesso ao mapeamento reflexo do **DER** com **JPA**, abra o projeto ``maprelentidades-cenario1`` no diretório ``/atv-av-maprelentidades/cenario1`` e acesse as classes no diretório ``/atv-av-maprelentidades/cenario1/maprelentidades-cenario1/src/main/java/br/edu/ifpb/maprelentidades/cenario1``.

###### Cenário 2  

> 1. Acesse o diretório ``/atv-av-maprelentidades/cenario2/maprelentidades-cenario2`` para obter acesso aos arquivos de execução do projeto.

> 2. No terminal execute o arquivo ``sh`` **run.sh** 

> 3. Espere o processo de construção e execução das imagens e dos containers

> 4. Após o passo 3, espere mais alguns segundos 

> 5. A aplicação foi implantada

> 6. Acesse a ``URL`` da [Página Inicial](http://localhost:8081/maprelentidades-cenario2/) para a tarefa agendada ser persistida: *persistência de um transporte com uma carga de Cajazeiras a João Pessoa, em 23 de outubro com o valor de R$ 2.500, em um Navio comandado por Capitão Jack Sparrow*

> 7. Os dados foram persistidos pela aplicação

> 8. Para ter acesso ao Banco de Dados (``PostgreSQL``) gerenciado pelo ``Docker`` e verificar a persistência, digite no terminal ``docker exec -it banco /bin/bash`` para ter acesso ao container do banco que foi configurado.

> 9. Para acessar o database que foi definido, ainda no terminal digite: ``psql -U postgres mapreldois``

> 10. Com o acesso ao banco, digite no terminal o **script** ``SELECT * FROM transporte;`` para checar as informações de transporte persistidas. 

##### Instruções para Desimplantação 

> 1. Execute o arquivo ``sh`` **kill.sh** no terminal
