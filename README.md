<h1 align="center">Web Development with Python, HTML and CSS</h1>

<p align="center">
  Aplicação web desenvolvida como parte do estudo prático de desenvolvimento backend e frontend.
</p>

<hr>

<h2>📌 Visão Geral</h2>

<p>
Este projeto documenta a construção de uma aplicação web utilizando <strong>Python</strong> com <strong>Flask</strong>, 
integrando <strong>HTML</strong>, <strong>CSS</strong>, templates dinâmicos com <strong>Jinja2</strong> e persistência de dados com <strong>SQLite</strong>.
</p>

<p>
O objetivo foi compreender, na prática, como estruturar uma aplicação web completa, 
desde a camada de apresentação até a manipulação de dados no backend.
</p>

<hr>

<h2>🛠 Tecnologias Utilizadas</h2>

<ul>
  <li>Python 3</li>
  <li>Flask</li>
  <li>Jinja2</li>
  <li>HTML5</li>
  <li>CSS3</li>
  <li>SQLite</li>
  <li>Virtual Environment (venv)</li>
</ul>

<hr>

<h2>⚙️ Funcionalidades Implementadas</h2>

<ul>
  <li>Configuração de servidor Flask com variáveis de ambiente</li>
  <li>Rotas dinâmicas</li>
  <li>Renderização de templates com Jinja2</li>
  <li>Separação entre lógica e apresentação</li>
  <li>Persistência de dados com SQLite</li>
  <li>Organização modular do projeto</li>
  <li>Gerenciamento de dependências com requirements.txt</li>
</ul>

<hr>

<h2>🗄 Banco de Dados</h2>

<p>A aplicação utiliza SQLite para armazenamento de dados.</p>

<p>Tabela principal:</p>

<ul>
  <li><strong>posts</strong></li>
</ul>

<p>Campos:</p>

<ul>
  <li>id (INTEGER - chave primária)</li>
  <li>titulo (TEXT)</li>
  <li>texto (TEXT)</li>
  <li>data_criacao (DATETIME)</li>
</ul>

<hr>

<h2>🚀 Como Executar o Projeto</h2>

<h3>1. Clonar o repositório</h3>

<pre>
git clone https://github.com/eduardabmfm/python-web-fev-2026.git
cd python-web-fev-2026
</pre>

<h3>2. Criar ambiente virtual</h3>

<pre>
python -m venv venv
</pre>

<p>Ativação:</p>

<pre>
Windows:
venv\Scripts\activate

Linux/Mac:
source venv/bin/activate
</pre>

<h3>3. Instalar dependências</h3>

<pre>
pip install -r requirements.txt
</pre>

<h3>4. Inicializar o banco de dados</h3>

<pre>
python init_db.py
</pre>

<h3>5. Executar a aplicação</h3>

<pre>
python app.py
</pre>

<hr>

<h2>📚 Conceitos Aplicados</h2>

<ul>
  <li>Arquitetura básica de aplicações web</li>
  <li>Separação de responsabilidades</li>
  <li>Templates dinâmicos</li>
  <li>Configuração via variáveis de ambiente</li>
  <li>Organização e versionamento de projeto</li>
</ul>

<hr>

<h2>👩🏻‍💻 Autora</h2>

<p>
Eduarda Bomfim<br>
Projeto desenvolvido para fins educacionais e consolidação de fundamentos em desenvolvimento web.
</p>
