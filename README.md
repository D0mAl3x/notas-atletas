# notas-atletas

<h2>Nome do Projeto:</h2>
<p>
  projetocertificacao1_devstart
</p>
<br><br>

<h2>Descrição do Projeto:</h2>
<p>
  Projeto criado para obtenção de certificação no curso <b>DevStart Senai - Trilha 1 - Lógica de Programação</b>. 
  Trata-se de um algoritmo escrito em JavaScript que lê os nomes e as cinco notas dos atletas de uma competição 
  de ginástica artistica e retorna a média das notas, descartadas a maior e a menor nota obtida por cada atleta.
</p>
<br><br>

<h2>Começando:</h2>
Durante a elaboração do código utilizei um notebook Asus, Intel core i3, 1.5GHz, 4GB de ram, com sistema operacional 
Windows 10 Home Single Language, x64. Usei ainda o Visual Studio Code, com as seguintes configurações:
<br><br>
<ul>
  <li>Version: 1.91.1 (user setup)</li>
  <li>Commit: f1e16e1e6214d7c44d078b1f0607b2388f29d729</li>
  <li>Date: 2024-07-09T22:06:49.809Z</li>
  <li>Electron: 29.4.0</li>
  <li>ElectronBuildId: 9728852</li>
  <li>Chromium: 122.0.6261.156</li>
  <li>Node.js: 20.9.0</li>
  <li>V8: 12.2.281.27-electron.0</li>
  <li>OS: Windows_NT x64 10.0.19045</li>
</ul>
<br><br>

<h2>Desenvolvimento:</h2>
Para iniciar o desenvolvimento, é necessário clonar o projeto do GitHub num diretório de sua preferência:<br><br>
<i>cd "diretório de sua preferência"</i><br>
<i>git clone https://github.com/D0mAl3x/notas-atletas.git</i>
<br><br>

<h2>Construção:</h2>
Não se aplica. O projeto em tela é composto de um único arquivo .js que pode ser executado diretamente no Visual Studio Code
ou em qualquer interpretador JavaScript.
<br><br>

<h2>Caracteristicas:</h2>
O algoritmo contém um objeto da classe Atleta, criado para receber e manipular os dados de entrada, quais sejam, uma matriz de objetos 
cujos atributos são o nome do atleta e as cinco notas obtidas (armazenadas em um array). Possui ainda quatro métodos:<br><br>
<p>
  <b>-> ordenaNotas():</b> criado para ordenar as notas de cada atleta em ordem crescente, visando posteriormente excluir do cálculo
      a menor e a maior notas obtidas;<br><br>
  <b>-> notasValidas(notasOrdenadas):</b> este método recebe uma matriz com as notas ordenadas de cada atleta e retorna outra
      matriz, contendo apenas as notas válidas para o cálculo da média;<br><br>
  <b>-> somatorioNotasValidas(notasValidas):</b> este método recebe a matriz de notas válidas como parâmetro, calcula e retorna o
      somatório das notas de cada atleta;<br><br>
  <b>-> calculoMediaValida(validadas, somaNotasValidas):</b> este método recebe dois parâmetros: a matriz de notas validadas e a
      matriz contendo a totalização das notas de cada atleta, calcula e retorna as médias válidas em um array.<br><br>
</p>
<br><br> 

<h2>Configuração:</h2>
Para executar o projeto, não há configurações adicionais a realizar. Basta apenas carregar o arquivo em um editor que suporte
a interpretação de scripts JS e executar o arquivo "notas-atletas.js".
<br><br>

<h2>Testes:</h2>
Os testes realizados no script estão devidamente identificados no arquivo. Eles começam a partir da linha 51. Adicionei 
comentários que considerei pertinentes em alguns trechos do código.
<br><br>

<h2>Contribuições:</h2>
Contribuições são sempre bem-vindas! Para contribuir lembre-se sempre de adicionar testes unitários para as novas classes com 
a devida documentação.
<br><br>

<h2>Links:</h2>
Não há links a serem adicionados.
<br><br>

<h2>Licença:</h2>
Não se aplica.


