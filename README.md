## Modelo conceitual Vendas

Deseja-se fazer um sistema para armazenar informações de vendas e vendedores de uma empresa. 
- Cada vendedor possui um id, nome, email e salário base. 
- Cada vendedor pertence a um departamento, sendo que se deve conhecer a data de início e fim da contratação de cada vendedor no departamento (nota: se a contração do vendedor no departamento ainda não terminou, a data de fim deverá ser nula). 
- Ao longo do tempo, o mesmo vendedor pode ser removido de um departamento e contratado para outro, podendo inclusive ser recontratado para o departamento em uma data futura.

Deseja-se também registrar as vendas realizadas pelos vendedores. 
- Cada venda possui uma data e um status (pendente, faturada ou cancelada), e pode ter um ou mais itens, sendo que cada item de venda corresponde a um produto, que pode ser vendido em quantidade 1 ou superior. Os dados do produto são nome e preço.

### Diagrama de classes

![modelo-conceitual-vendas-classe](https://user-images.githubusercontent.com/100785891/213074293-6c25032e-b468-41de-b4e5-d5ee35e54cb1.png)


### Instância mínima

![modelo-conceitual-vendas-objetos](https://user-images.githubusercontent.com/100785891/212748188-5c9ae337-2275-40f7-bfac-93ca6146ac4c.png)
