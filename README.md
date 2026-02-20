<h1 align="center">Web Development with Python, HTML and CSS</h1>

<p align="center">
  Aplicação web desenvolvida como parte da formação em desenvolvimento web.
</p>

<hr>

<h2>
  Instituição: 
  <a href="https://oceanbrasil.com/atividades/4888-Programando-para-web-com-Python-CSS-e-HTML" title="Samsung Ocean e UEA (Universidade Estadual do Amazonas)">
    Samsung Ocean e UEA (Universidade Estadual do Amazonas)
  </a>
</h2>

<p>
Este projeto foi desenvolvido durante as aulas do programa oferecido pela Samsung Ocean em parceria com a UEA (Universidade Estadual do Amazonas), 
com foco na construção prática de aplicações web utilizando Python.
</p>

<hr>

<h2>📌 Visão Geral do Projeto</h2>

<p>
O projeto foi construído em etapas, acompanhando a evolução dos conteúdos apresentados nas aulas.
</p>

<p>
O objetivo principal foi compreender como uma aplicação web funciona de ponta a ponta — 
desde a estrutura de uma página HTML até a manipulação de dados em um banco de dados integrado ao backend.
</p>

<hr>

<h2>📚 O que foi aprendido durante as aulas</h2>

<h3>🧱 Fundamentos de HTML</h3>
<ul>
  <li>Estrutura básica de um documento HTML</li>
  <li>Tags semânticas</li>
  <li>Listas, tabelas e formulários</li>
  <li>Organização e hierarquia de conteúdo</li>
</ul>

<h3>🎨 Estilização com CSS</h3>
<ul>
  <li>CSS inline, interno e externo</li>
  <li>Box Model</li>
  <li>Flexbox e Grid</li>
  <li>Responsividade</li>
  <li>Separação entre estrutura e estilo</li>
</ul>

<h3>🔥 Backend com Flask</h3>
<ul>
  <li>Criação de servidor web</li>
  <li>Definição de rotas</li>
  <li>Renderização de templates</li>
  <li>Uso de variáveis de ambiente</li>
  <li>Modo debug e organização do entrypoint</li>
</ul>

<h3>🧩 Templates Dinâmicos com Jinja2</h3>
<ul>
  <li>Injeção de variáveis no HTML</li>
  <li>Condicionais</li>
  <li>Loops</li>
  <li>Separação entre lógica e apresentação</li>
</ul>

<h3>🗄 Persistência de Dados com SQLite</h3>
<ul>
  <li>Criação de banco de dados</li>
  <li>Estruturação de tabelas via esquema.sql</li>
  <li>Script de inicialização (init_db.py)</li>
  <li>Manipulação e armazenamento de dados</li>
</ul>

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

<h2>🏗 Estrutura da Aplicação</h2>

<pre>
python-web-fev-2026/
│
├── app.py              # Aplicação principal Flask
├── init_db.py          # Script de inicialização do banco
├── esquema.sql         # Estrutura do banco de dados
├── banco.db            # Banco SQLite
├── requirements.txt    # Dependências do projeto
├── .env                # Variáveis de ambiente
│
├── templates/          # Templates HTML (Jinja2)
│   ├── index.html
│   └── user.html
│
├── static/             # Arquivos estáticos
│   └── styles.css
│
└── README.md
</pre>

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

<h2>📚 Resultados do Projeto</h2>

<p>
Ao final do desenvolvimento, a aplicação passou a integrar frontend e backend de forma estruturada, 
com persistência de dados e organização modular.
</p>

<p>
Este projeto consolidou minha base em desenvolvimento web, aplicando teoria e prática de forma integrada.
</p>

<hr>

<h2>👩🏻‍💻 Autora</h2>

<p>
Eduarda Bomfim<br>
Projeto desenvolvido para consolidação de fundamentos em desenvolvimento web.
</p>