Descrição do projeto
Este projeto realiza o rastreamento de objetos selecionados e identificados com base em sua forma, utilizando técnicas de visão computacional e aprendizado de máquina.

Instruções de instalação
Instalar o Visual Studio Code (VS Code) .
Instale o Anaconda Navigator .
(Opcional) Instale o Iriun Webcam no computador e no celular, caso seu computador não possua webcam.
Utilize a Máquina Ensinável para criar o modelo de rastreamento dos objetos desejados.
Treine o modelo com as classes de objetos que você deseja considerar.
Exporte o modelo no formato Keras (.h5) para TensorFlow.
Baixe o arquivo classificacao_5_objetos-v4.pyque contém o código principal do projeto.
Baixe o arquivo env_teste_PI_2024.yml, que é o ambiente virtual com todas as dependências configuradas para o Anaconda Navigator.
Instruções de uso
Crie uma nova pasta no seu computador para armazenar todos os arquivos do projeto.
Extraia o arquivo do modelo Keras (.h5) dentro dessa pasta.
Copie o arquivo classificacao_5_objetos-v4.pypara essa mesma pasta.
Abra o Anaconda Navigator.
Na aba Environments , importe o ambiente virtual do arquivo env_teste_PI_2024.yml.
Com o ambiente virtual ativado, abra o VS Code pelo próprio Anaconda Navigator.
No VS Code, abra a pasta onde os arquivos estão armazenados.
Abra o arquivo classificacao_5_objetos-v4.py.
Verifique se o ambiente virtual env_teste_PI_2024está selecionado no VS Code.
Executar o projeto.
Observação: Caso ocorra algum erro relacionado ao arquivo do modelo, verifique se o nome do arquivo keras.model.h5está com sublinhado (_) ao invés de ponto (.). Caso esteja incorreto, altere o nome do arquivo, não o código.

Créditos
Projeto realizado no Laboratório de Sistemas de Informação da UFOPA.
