# ponderada_sem_3

## Casos de Teste

1 - Inserir e Buscar: Esse caso de teste verifica se a inserção de um par chave-valor ("key1", "value1") na DHT é bem-sucedida. Em seguida, ele verifica se a recuperação do valor associado à chave "key1" retorna o valor inserido. Isso é feito usando a função insert para adicionar um par chave-valor e a função get para buscar o valor associado à chave. O assert é usado para verificar se o valor retornado pela função get é igual ao valor esperado "value1".

2 - Inserir e Remover: Este caso de teste segue o mesmo padrão do primeiro, mas adiciona um passo adicional de remoção. Após inserir o par chave-valor "key2", "value2", o teste remove a chave "key2" da DHT usando a função remove. Em seguida, ele verifica se a função get retorna uma string vazia "" para a chave removida. O assert é usado para verificar se o valor retornado pela função get é igual à string vazia "".

3 - Inserir e Buscar Vários: Aqui, o caso de teste verifica se é possível inserir vários pares chave-valor na DHT e recuperar um valor específico com sucesso. Primeiro, são inseridos dois pares chave-valor: "key3", "value3" e "key4", "value4". Em seguida, o teste verifica se a função get retorna o valor "value3" quando a chave "key3" é passada como argumento. O assert é usado para verificar se o valor retornado pela função get é igual ao valor esperado "value3".

4 - Inserir e Remover Vários: Similar ao caso de teste anterior, este caso de teste testa a inserção e remoção de vários pares chave-valor. Ele adiciona dois pares chave-valor: "key5", "value5" e "key6", "value6", e, em seguida, remove a chave "key6" usando a função remove. O teste verifica se a função get retorna uma string vazia "" para a chave removida. O assert é usado para verificar se o valor retornado pela função get é igual à string vazia "".

5 - Buscar Chave Inexistente: Este caso de teste verifica se a função get retorna uma string vazia "" quando uma chave que não existe é passada como argumento. Primeiro, são inseridos dois pares chave-valor: "key7", "value7" e "key8", "value8". Em seguida, o teste verifica se a função get retorna uma string vazia "" quando a chave "key9" (que não foi inserida) é passada como argumento. O assert é usado para verificar se o valor retornado pela função get é igual à string vazia "".

