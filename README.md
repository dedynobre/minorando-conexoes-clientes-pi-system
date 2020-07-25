
<h1 align="center">
<br>
Monitorando conexões de ferramentas clientes do PI System
</h1>

<p align="center">O desenvolvimento tem como finalidade mostrar quantas conexões diferentes houve nas duas principais ferramentas de visualização de dados da OSISoft.</p>

<p align="center">
  <a href="https://www.apache.org/licenses/LICENSE-2.0">
    <img src="https://img.shields.io/badge/apache-2.0-blue" alt="License MIT">
  </a>
</p>

<div>
  <img src="https://github.com/dedynobre/monitorando-conexoes-clientes-do-pi-system/blob/master/event.gif" alt="conexoes-clientes" height="300">
</div>

<hr />


## Recursos utilizados

- **Node-Red** - Versão 1.1.0
- **Grafana** - Versão 7.1.0
- **PI Server** - Versão 2012

## Desenvolvimento

A ideia principal era saber quantos usuários diferentes estavam se conectando diariamente no PI Server para definição de estratégia de licenciamento.
Então foi feito levantamento de quantos usuários diferentes estavam se conectando diariamente no PI Server para obter dados usando as ferramentas Datalink e Processbook.
Como o primeiro passo foi levantar as conexões e assim fazer o somatório os eventos de conexão,esta coleta foi feita a partir da opção abaixo e no campo mensagem com os seguintes filtros:
Processbook -> Successful*Procbook.EXE* 
Excel -> Successful*EXCEL.EXE*

<img src="https://github.com/dedynobre/monitorando-conexoes-clientes-do-pi-system/blob/master/img2.png" alt="conexoes-clientes" height="300">





