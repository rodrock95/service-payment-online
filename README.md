# Projeto Java - Serviço de pagamento de parcelas online

Uma empresa deseja automatizar o processamento de seus contratos. O processamento de um contrato consiste em 
gerar as parcelas a serem pagas para aquele contrato, com base no número de meses desejado.

A empresa utiliza um serviço de pagamento online para realizar o pagamento das parcelas.
Os serviços de pagamento online tipicamente cobram um juro mensal, bem como uma taxa
por pagamento. Por enquanto, o serviço contratado pela empresa é o do Paypal, que aplica
juros simples de 1% a cada parcela, mais uma taxa de pagamento de 2%.

Fazer um programa usando Orientação a Objetos para ler os dados de um contrato 
(número do contrato, data do contrato, e valor total do contrato). Em seguida, o programa deve 
ler o número de meses para parcelamento do contrato, e daí gerar os registros de parcelas a serem pagas (data e valor),
sendo a primeira parcela a ser paga um mês após a data do contrato, a segunda parcela dois
meses após o contrato e assim por diante. Mostrar os dados das parcelas na tela.

## Exemplo:

![example1Interface](https://github.com/rodrock95/service-payment-online/assets/79290866/fa842b32-3603-42be-98d8-b1b6b3824814)

## Modelo de domínio (Entidades)

![domainEntitiesInterface](https://github.com/rodrock95/service-payment-online/assets/79290866/956b8239-3c2e-4948-9e32-9a26f9df8e28)

## Modelo de domínio (Serviços)

![domainEntitiesService](https://github.com/rodrock95/service-payment-online/assets/79290866/97b7ce42-371a-4ccd-bd08-426bf40fd551)
