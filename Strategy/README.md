# Strategy

Padrão muito útil quando se tem um conjunto de algoritmos similares e precisamos alternar entre eles em diferentes trechos da aplicação.

Se houver apenas uma única estratégia não há necessidade de aplicar o padrão.

### Problema
Em uma empresa existem um conjunto de cargos e para cada cargo existem regras de cálculo de imposto onde determinada porcentagem do salário deve ser retirada de acordo com o salário base do funcionário.

Regras:
* O Desenvolvedor deve ter um imposto de 15% caso seu salário seja maior que R$ 2000,00 e 10% caso contrário;
* O Gerente deve ter um imposto de 20% caso seu salário seja maior que R$ 3500,00 e 15% caso contrário;
* O DBA deve ter um imposto de  de 15% caso seu salário seja maior que R$ 2000,00 e 10% caso contrário;
