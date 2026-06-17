Código usado na tarefa de detecção de objetos da liga @Home em 2021.

Uma explicação breve do código pode ser vista em:
https://www.youtube.com/watch?v=hn7FEuZLm4c&list=PL9ESgQmnVQPZaqi1JAqaa_HBL3-dX_GLO&index=9&pp=iAQB

O código tem dois arquivos principais:

keras_transfer_learning.py -> Treinamento do modelo
keras_model_loading -> Carregamento do modelo e detecção de objetos em imagens

Para rodar a detecção utilize:
python keras_model_loading.py 2> /dev/null
O envio da saída de erro para /dev/null é para fazer com que algumas mensagens de aviso
não sejam mostradas
