# Template Method

Quando se tem diferentes algoritmos que possuem estruturas parecidas.

Dessa forma é possível definir (em um nível macro) a estrutura do algortimo e deixar "buracos" que serão implementados de maneira diferente por cada uma das implementações específicas.

O modificador de acesso ideal para os métodos do template é o **protected**, pois as classes cliente não os enxergariam e as classes filhas do template conseguiriam sobreescrever esse método sem problemas.

Para evitar que o método principal seja sobreescrito, utilizar o modificador de acesso **final**.