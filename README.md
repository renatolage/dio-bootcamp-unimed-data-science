# Desafios Bootcamp Unimed - Data Science
  Repositório referente aos projetos realizados durante o bootcamp Geração Unimed BH - Data Science

# package-template-master
  Projeto criado para o desafio "Descomplicando a criação de pacotes
    - Foi usado um projeto que criei durante minhas primeiras aulas em python, onde o app basicamente gera 
      um número aleatório de cpf através da função geracpf() e através da função validacpf, o app recebe um número de cpf
      e verifica se esse número é válido.
    
  ## Comando Aprendidos durante o desafio:
    - python3 -m pip install --upgrade pip (Atualiza o pip)
    - python3 -m pip install --user twine (Instala o twine)
    - python3 -m pip install --user setuptools (Instala o setuptools)
    - python3 setup.py sdist bdist_wheel (Roda o setup.py onde contem as especificações do pacote, como nome, versão, etc)
    - python3 -m twine upload --repository-url https://test.pypi.org/legacy dist/* (Faz o upload de teste para test pypi)
    - python3 -m twine upload --repository-url https://upload.pypi.org/legacy dist/* (Faz o upload da versão final para o pypi)

