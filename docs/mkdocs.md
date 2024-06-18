# Instalação
Para instalar o MkDocs, você precisa ter o Python e o pip (gerenciador de pacotes do Python) configurados no seu sistema. O MkDocs é uma aplicação Python, então a instalação é feita utilizando o pip.

* Verifique se o Python está instalado:
```
python --version
```
* Instale o MkDocs:
```
pip install mkdocs
```
* crie uma pasta:
```
mkdir meu_projeto
```
* Inicialize o mkdocs:
```
mkdocs new novosite  
cd novosite
nano mkdocs.yml
```
* Iniciar o servidor de desenvolvimento:
```
mkdocs serve
```
* Quando o documento estiver pronto compile o site para copiar no servidor web:
```
mkdocs build
```

Para saber mais sobre o Mkdocs você pode consultar a documentação pelo link: `https://www.mkdocs.org/`

