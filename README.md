# Modelagem do Banco de Dados
Repositório para modelagem do banco de dados

<i>Integrantes</i>
<ul>
 <li>Akecio Palhano</li>
 <li>Paulo Henrique Fernandes</li>
</ul>

<i>Professor</i>
<ul>
 <li>Adeilson Aragão</li>
</ul>

<div align="center">
  <img src="https://raw.githubusercontent.com/Akecio/ProvaBD/master/L%C3%B3gico_1.png"/>
</div>

# Descrição das tabelas do modelo

<h2>Tabela <i>Turma</i></h2>
A tabela <i>Turma</i> Descreve as informações sobre a turma.
Nela possuímos os atributos/colunas:
<ul>
  <li>cod_turma: chave primária da tabela</li>
  <li>cod_disc: informação sobre o código da disciplina</li>
  <li>cod_prof: informação importante para identificar o professor</li>
  <li>horario: horário de cada turma</li>
</ul>

<h2>Tabela <i>Professores</i></h2>
A tabela <i>Professores</i> será na nossa base de dados a responsável por manter os dados dos professores.
Nela possuímos os atributos/colunas:
<ul>
  <li>cod_prof: chave primária da tabela</li>
  <li>nome: nome do professor</li>
  <li>cidade: informação importante para saber a cidade do professor</li>
  <li>endereco: informação importante para saber a localização do professor</li>
</ul>

<h2>Tabela <i>Disciplina</i></h2>
Tabela <i>Disciplina</i> aqui teremos na nossa base informações sobre as instituições que recebem e realizam o processo de transplantes.
Nela possuímos os atributos/colunas:
<ul>
  <li>cod_disc: chave primária da tabela</li>
  <li>nome_disc: nome da disciplina<li>
  <li>carga_hor: informação sobre a carga horária</li>
 </ul>
 
 <h2>Relacionamento <i>Possui</i></h2>
Relacionamento <i>Possui</i> tabela de ligação entre as tabelas </i>professores</i> e <i>turma</i>.
Nela possuímos os atributos/colunas:
<ul>
  <li>fk_professores_cod_prof<i>professores</i></li>
  <li>fk_turma_cod_turma<i>turma</i> </li>
</ul>

<h2>Tabela <i>Aluno</i></h2>
Tabela <i>Aluno</i> Nesta tabela temos as informações sobra cada aluno
Nela possuímos os atributos/colunas:
<ul>
 <li>matricula: chave primária da tabela</li>
 <li>nome: nome de cada aluno</li>
  <li>cidade: informação importante para saber a cidade do aluno</li>
  <li>endereco: informação importante para saber a localização do aluno</li>
</ul>

<h2>Tabela <i>Historico</i></h2>
Tabela <i>Historico</i> nesta tabela temos as informações do histórico
Nela possuímos os atributos/colunas:
<ul>
  <li>matricula: informações sobre a matricula</li>
  <li>cod_disc: informações de disciplina</li>
  <li>cod_prof: informações do professor</li>
  <li>cod_turma: informações da turma</li>
  <li>ano: informação sobre o ano</li>
  <li>frequencia: informações de frequência </li>
  <li>nota: informação sobre nota</li>

</ul>
