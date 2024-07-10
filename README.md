<h1>Planejador de Viagem - Backend</h1>

<p>
Bem-vindo ao repositório do Planejador de Viagem! Este projeto permite que os usuários convidem amigos para participar de uma viagem e planejem tarefas para serem executadas durante o período da viagem. Este repositório contém toda a lógica de backend necessária para a aplicação.
</p>

<h2>Tecnologias Utilizadas</h2>

<ul>
  <li><strong>Python</strong>: Linguagem de programação principal utilizada no projeto.</li>
  <li><strong>Virtualenv</strong>: Ferramenta para gerenciar as dependências da aplicação de forma concisa e organizada.</li>
  <li><strong>Postman</strong>: Utilizado para testar o bom funcionamento da API criada.</li>
  <li><strong>Flask</strong>: Framework utilizado para a criação do servidor HTTP.</li>
  <li><strong>PyTest</strong>: Ferramenta para a criação de testes unitários.</li>
  <li><strong>PyLint</strong>: Utilizado para garantir uma boa estrutura do código e manter um código limpo.</li>
</ul>

<h2>Instalação e Configuração</h2>

<p>Siga os passos abaixo para configurar o ambiente de desenvolvimento:</p>

<ol>
  <li><p><strong>Clone o repositório</strong>:</p>
    <pre><code>git clone  https://github.com/Lucas-Sabbatini/NLW_Python.git
cd planejador-de-viagem</code></pre>
  </li>
  <li><p><strong>Crie um ambiente virtual</strong>:</p>
    <pre><code>python -m venv venv</code></pre>
  </li>
  <li><p><strong>Ative o ambiente virtual</strong>:</p>
    <p>Windows:</p>
    <pre><code>venv\Scripts\activate</code></pre>
    <p>MacOS/Linux:</p>
    <pre><code>source venv/bin/activate</code></pre>
  </li>
  <li><p><strong>Instale as dependências</strong>:</p>
    <pre><code>pip install -r requirements.txt</code></pre>
  </li>
</ol>

<h2>Executando o Servidor</h2>

<p>Para iniciar o servidor Flask, execute o comando abaixo:</p>

<pre><code>flask run</code></pre>

<p>O servidor estará disponível em <code>http://127.0.0.1:5000/</code>.</p>

<h2>Testando a API</h2>

<p>Utilize o Postman para testar as rotas e verificar o bom funcionamento da API. Importe a coleção de requests do Postman disponível no repositório para facilitar os testes.</p>

<h2>Testes Unitários</h2>

<p>Os testes unitários foram criados utilizando o PyTest. Para executá-los, utilize o comando:</p>

<pre><code>pytest</code></pre>
