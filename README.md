# Boe - Aplicação Web

<p>É uma Aplicação Web exclusiva para dispositivos móveis com o sistema de classificação de imagens por meio da aplicação de aprendizagem profunda para o pré-diagnóstico de Dermatofitose Bovina</p>

### Como instalar este projeto?
<p>Execute o seguinte comando em seu terminal Git Bash para instalar este projeto:</p>

```
git clone https://github.com/RebecaBaruch/boe_app.git
```

<p>Depois de clonar o repositório, instale suas dependências:</p>

```
pip install -r Requirements.txt
```

<p>Caso ocorra problemas na instalação com o comando acima, aqui se encontra o comando para instalar todas as bibliotecas usadas no desenvolvimento da aplicação:</p>

```
pip install bcrypt bson cachelib Flask Flask-Caching Flask-Cors opencv-python Pillow PyJWT pymongo python-dateutil python-dotenv werkzeug
```

⚠️ É necessário ter o MongoDB Compass instalado e dentro do MongoDB criar uma base de dados: boe-app
⚠️ Certifique-se de que é possível conectar com o MongoDB Compass

### Como executar este projeto?
<p>Para executar este projeto, em seu terminal do repositório, execute a aplicação em Python pelo seguinte comando:</p>

```
py app.py
```

<p>Após rodar a aplicação em Python, execute a página login.html pela extensão LiveServer, por exemplo.</p>

Após todo esse processo a aplicação deve rodar normalmente.
