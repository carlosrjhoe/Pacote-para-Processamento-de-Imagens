Projeto: Pacote para Processamento de Imagens
Autora Original do Projeto: Karina Kato
Aula: Coding Lab PRO - Digital Innovation One
(Acesse o meu perfil na plataforma aqui)

Linguagem: Python
Data: 04/09/2024
Descrição
Este pacote, denominado "image_processing_test", é utilizado para:

Módulo "Processing":

Realizar a correspondência de histograma entre imagens;
Verificar a similaridade estrutural;
Redimensionar imagens conforme necessário;
Módulo "Utils":

Leitura de imagens;
Salvamento de imagens;
Exibir e plotar gráficos;
Exibir histogramas.
Como configurar o ambiente de testes Test PyPI para hospedar um pacote Python
 Atualize as ferramentas "setuptools" e "wheel":
bash
Copy code
py -m pip install --user --upgrade setuptools wheel
 Navegue até o diretório do arquivo "setup.py" no terminal:
bash
Copy code
C:\User\Henrique\image-processing-package> py setup.py sdist bdist_wheel
 Após a execução, verifique a criação das seguintes pastas no projeto:

 build;
 dist;
 image_processing_test.egg-info.
 Para enviar os arquivos ao Test PyPI usando Twine:

bash
Copy code
py -m twine upload --repository testpypi dist/*
 Após rodar o comando, será solicitado inserir usuário e senha. Com isso, o projeto será hospedado no Test PyPI.
Nota: O objetivo deste passo é apenas ilustrar o processo de hospedagem no Test PyPI, visto que o projeto original é de Karina Kato. O projeto não será publicado no meu perfil no PyPI.

Observação: Para disponibilizar o projeto publicamente, é necessário hospedá-lo no site oficial do PyPI e não apenas no ambiente de testes.

Como instalar localmente após a hospedagem no Test PyPI
 Instale as dependências com o comando abaixo:
bash
Copy code
pip install -r requirements.txt
 Instale o pacote diretamente:
bash
Copy code
pip install -i https://test.pypi.org/simple/ image-processing-test
Como utilizar o pacote em outros projetos
python
Copy code
from image_processing_test.processing import combination
combination.find_difference(image1, image2)
<img width="auto" src="">
Autor do Upload no Test PyPI
Henrique Matheus Alves Pereira

Licença
MITProjeto: Pacote para Processamento de Imagens
Autora Original do Projeto: Karina Kato
Aula: Coding Lab PRO - Digital Innovation One
(Acesse o meu perfil na plataforma aqui)

Linguagem: Python
Data: 04/09/2024
Descrição
Este pacote, denominado "image_processing_test", é utilizado para:

Módulo "Processing":

Realizar a correspondência de histograma entre imagens;
Verificar a similaridade estrutural;
Redimensionar imagens conforme necessário;
Módulo "Utils":

Leitura de imagens;
Salvamento de imagens;
Exibir e plotar gráficos;
Exibir histogramas.
Como configurar o ambiente de testes Test PyPI para hospedar um pacote Python
 Atualize as ferramentas "setuptools" e "wheel":
bash
Copy code
py -m pip install --user --upgrade setuptools wheel
 Navegue até o diretório do arquivo "setup.py" no terminal:
bash
 Após a execução, verifique a criação das seguintes pastas no projeto:

 build;
 dist;
 image_processing_test.egg-info.
 Para enviar os arquivos ao Test PyPI usando Twine:

bash
Copy code
py -m twine upload --repository testpypi dist/*
 Após rodar o comando, será solicitado inserir usuário e senha. Com isso, o projeto será hospedado no Test PyPI.
Nota: O objetivo deste passo é apenas ilustrar o processo de hospedagem no Test PyPI, visto que o projeto original é de Karina Kato. O projeto não será publicado no meu perfil no PyPI.

Observação: Para disponibilizar o projeto publicamente, é necessário hospedá-lo no site oficial do PyPI e não apenas no ambiente de testes.

Como instalar localmente após a hospedagem no Test PyPI
 Instale as dependências com o comando abaixo:
bash
Copy code
pip install -r requirements.txt
 Instale o pacote diretamente:
bash
Copy code
pip install -i https://test.pypi.org/simple/ image-processing-test
Como utilizar o pacote em outros projetos
python
Copy code
from image_processing_test.processing import combination
combination.find_difference(image1, image2)
<img width="auto" src="">
Autor do Upload no Test PyPI
Carlos Roberto Conceição Junior

Licença
MIT