# Documentação.


respostas:

1- No requirements.txt será disponibilizado o flask (Flask==3.0.3) e o marshmallow 3 (provavelmente)

2- Os endpoints fornecidos sao o post('/aluno') e o post('/relatorio'). O referente ao aluno deseja adicionar informaçoes em aluno, para isso ele vai criar uma funcao e depois informar que o dado recebido sera em forma de json e chamar a funcao aluno schema que aponta para a idade e a disciplina, apos isso a tentativa é iniciada onde sera carregada as informacoes e respondidas chamando a funcao de cadastrar aluno com os parametros de data_now_json_str que recebera o resultado inputado e retornado como json response_data. em caso de erro, sera feita a excessao a partir do validationerror de erro e retornando a mensagem. O relatorio funciona da mesma maneira porem ele chamara outra funcao, a cadastrarrelatorio, onde os dados validados e recebidos serao titulo, criacao e aluno.

3-

4- O marshmallow serve para validar dados de entrada, desserializar e serializar dados, e esse objetos serializados podem então ser passados em formatos universais, como JSON, para assim serem usados e entendidos pela API e verificar possiveis erros. Ele funciona primeiro recebendo os dados de acordo com o que é passado e depois sao carregados no formato json para serem recebidos nos endpoints e processados e respondidos.

5- Os json fornecidos em cada endpoint serao recebidos pelas classes feitas e recebidas por schema, nessas classes sao informados e apontados os valores de recebimento do json.
