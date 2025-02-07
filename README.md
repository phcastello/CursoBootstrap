<h1><a href="https://phcastello.github.io">Voltar à pagina inicial</a></h1>
<br>
<h1>Todos os sites de exemplo e desafios, por mais que peculiares, têm a forma na qual foram desenhados para ter!</h1>
<p>Espaços vazios, tags estranhas e etc são propositais e tiveram o intuito de aprendizado :)</p>

<!-- Container para os links -->
<div class="links-container">
  <h3><a href="https://phcastello.github.io/CursoBootstrap/Aula01" target="_blank">Aula 01</a></h3>
  <h3><a href="https://phcastello.github.io/CursoBootstrap/Aula02" target="_blank">Aula 02</a></h3>
  <h3><a href="https://phcastello.github.io/CursoBootstrap/Aula03" target="_blank">Aula 03</a></h3>
  <h3><a href="https://phcastello.github.io/CursoBootstrap/Aula04" target="_blank">Aula 04</a></h3>
  <h3><a href="https://phcastello.github.io/CursoBootstrap/Aula05" target="_blank">Aula 05</a></h3>
  <h3><a href="https://phcastello.github.io/CursoBootstrap/Aula06" target="_blank">Aula 06</a></h3>
  <h3><a href="https://phcastello.github.io/CursoBootstrap/Aula07" target="_blank">Aula 07</a></h3>
  <h3><a href="https://phcastello.github.io/CursoBootstrap/Aula08" target="_blank">Aula 08</a></h3>
  <h3><a href="https://phcastello.github.io/CursoBootstrap/Aula09" target="_blank">Aula 09</a></h3>
  <h3><a href="https://phcastello.github.io/CursoBootstrap/Aula10" target="_blank">Aula 10</a></h3>
  <h3><a href="https://phcastello.github.io/CursoBootstrap/Aula11" target="_blank">Aula 11</a></h3>
  <h3><a href="https://phcastello.github.io/CursoBootstrap/Aula12" target="_blank">Aula 12</a></h3>
  <h3><a href="https://phcastello.github.io/CursoBootstrap/Aula13" target="_blank">Aula 13</a></h3>
  <h3><a href="https://phcastello.github.io/CursoBootstrap/Aula14" target="_blank">Aula 14</a></h3>
  <h3><a href="https://phcastello.github.io/CursoBootstrap/Aula15" target="_blank">Aula 15</a></h3>
</div>

<h2>
  <h3>
    <a href="#" onclick="window.open('https://mail.google.com/mail/?view=cm&fs=1&to=contato.pedrocastello@gmail.com&su=Sugestões%20para%20Pedro%20Castello', '_blank'); return false;">Sugestões são sempre bem-vindas!</a>
  </h3>
</h2>

<!-- CSS para organizar os links em duas colunas -->
<style>
  .links-container {
    display: flex;
    flex-wrap: wrap;
    gap: 0px;
  }

  .links-container h3 {
    flex: 1 1 30%; /* Cada item ocupa aproximadamente 30% da largura */
    text-align: left;
    margin-top: 5px;
    margin-bottom: 5px;
  }

  /* Ajuste para telas menores */
@media (max-width: 768px) {
  .links-container h3 {
    flex: 1 1 45%; /* Em telas médias, duas colunas */
  }
}

@media (max-width: 480px) {
  .links-container h3 {
    flex: 1 1 100%; /* Em telas pequenas, cada link ocupa a linha inteira */
  }
}

  .links-container h3 {
   /* Alinhamento do texto */
}

/* Ajuste para telas menores */
@media (max-width: 768px) {
  .links-container h3 {
    flex: 1 1 45%; /* Em telas médias, duas colunas */
  }
}

@media (max-width: 480px) {
  .links-container h3 {
    flex: 1 1 100%; /* Em telas pequenas, cada link ocupa a linha inteira */
  }
}
</style>
