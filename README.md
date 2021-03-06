# Sybank-Front-Test #

![SY BANK LOGO](Logo.png)

## Descrição ##
Precisamos desenvolver uma pequena interface que simule o funcionamento de saque em um caixa eletrônico. O usuário deve poder inserir o valor desejado e visualizar quais notas o caixa irá disponibilizar.

## Requisitos técnicos e funcionais ##
* Desenvolver utilizando HTML, CSS e Javascript;
* O caixa deve entregar sempre o menor número possível de notas;
* O caixa deve validar se é possível sacar o valor solicitado com as notas disponíveis;
* As notas disponíveis são: R$ 100,00; R$ 50,00; R$ 20,00 e R$ 10,00;

## Considerações importantes ##
* Não é necessário validar o saldo do cliente, para esse teste o saldo é infinito.
* O valor solicitado será sempre positivo.
* A quantidade de notas é infinita;

Para validação, pode-se usar os exemplos abaixo:
> Valor do Saque: **R$ 30,00**. Resultado Esperado: **1** nota de **R$ 20,00** e **1** nota de **R$ 10,00**.

> Valor do Saque: **R$ 80,00**. Resultado Esperado: **1** nota de **R$ 50,00**, **1** nota de **R$ 20,00** e **1** nota de **R$ 10,00**.

> Valor do Saque: **R$ 100,00**. Resultado Esperado: **1** nota de **R$ 100,00**.

> Valor do Saque: **R$ 105,00**. Resultado Esperado: **Falha**, notas de indisponíveis.

## Layouts e referencias ##
Os layouts podem ser encontrados no link: https://www.figma.com/file/YNG7dUBzTry4BmtfDGLMfl/Teste-Front-End-%7C-Synapcom-%7C-TI-%26-Sistemas?node-id=292%3A1365.\

Para este teste, deve-se utilizar o conceito *Mobile First*, então é possível encontrar as duas versões (desktop+mobile) na referência acima.

Um detalhe, o Figma possui um modo de protótipo navegável que você pode usar para visualizar as animações da tela.

![SY BANK LOGO](Mobile.png) ![SY BANK LOGO](Desktop.png)

## Instruções de Entrega ##
Ao finalizar, basta fazer um pull do seu projeto nos enviar o link do repositório para avaliarmos, tudo bem?

Faça o teste com calma, da forma que for mais confortável para você.

Boa sorte! :D
