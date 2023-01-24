# multiwozPortugues

Passos:
1.	Copiar o diálogo todo que queremos traduzir do ficheiro original de teste para o ficheiro dadosCoimbraTest.json;
2.	Verificar os serviços pedidos para esse diálogo;
3.	Substituir o serviço na respetiva base de dados (se ainda não estiver);
4.	Atualizar o valor dos slots;
5.	Retirar os campos “exclusive_end” e “start”;
6.	Traduzir as utterances;
7.	E repetimos estes passos (do 2 ao 6) até ao final do diálogo.


Bases de dados:

•	Hotéis – Ficheiro do MultiWOZ todo atualizado para dados de Coimbra;
•	Restaurantes – vai-se atualizando o ficheiro do MultiWOZ à medida que vão aparecendo nas utterances;
•	Atrações – vai-se atualizando o ficheiro do MultiWOZ à medida que vão aparecendo nas utterances;
•	Comboios – não estou a atualizar, vou vendo no site da CP e tenho um bloco de notas com os que já apareceram;
•	Táxis – não estou a atualizar, vou vendo no google os números. Não estou a colocar modelos nem cores dos táxis. Essa parte ignoro;
•	Autocarros – Ainda não me apareceu.
Notas importantes:
1.	Ver sempre os parâmetros dos serviços de Cambridge para tentarmos que sejam iguais ou parecidos aos serviços de Coimbra. Exemplo: restaurante no centro, com um preço moderado e comida italiana  Tentar arranjar um restaurante em Coimbra com estes parâmetros.
2.	Em todos os serviços acrescento os campos “idMultiWoz” e “nameMultiWoz” com o id e o nome que corresponde ao dataset original.

Train:
london kings cross - Aveiro
london liverpool street - Fontela
Peterborough - Figueira da Foz
Stevenage - Oliveira do Bairro
birmingham new street - Lisboa Oriente 
bishops stortford - Curia
Leicester - Entroncamento 
stansted airport - Mealhada
kings lynn - Pereira
ely - souselas 
Norwich - Fátima

