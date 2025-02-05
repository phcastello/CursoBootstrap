<h1><a href="https://phcastello.github.io">Voltar à pagina inicial</a></h1>
<br>
<h1>Todos os sites de exemplo e desafios, por mais que peculiares, têm a forma na qual foram desenhados para ter!</h1>
<p>Espaços vazios, tags estranhas e etc são propositais e tiveram o intuito de aprendizado :)</p>

<!-- Container para os links -->
<div class="links-container">
  <h3 class="link"><a href="https://phcastello.github.io/CursoBootstrap/Aula1" target="_blank">Aula 1</a></h3>
  <h3 class="link"><a href="https://phcastello.github.io/CursoBootstrap/Aula2" target="_blank">Aula 2</a></h3>
  <h3 class="link"><a href="https://phcastello.github.io/CursoBootstrap/Aula3" target="_blank">Aula 3</a></h3>
  <h3 class="link"><a href="https://phcastello.github.io/CursoBootstrap/Aula4" target="_blank">Aula 4</a></h3>
  <h3 class="link"><a href="https://phcastello.github.io/CursoBootstrap/Aula5" target="_blank">Aula 5</a></h3>
  <h3 class="link"><a href="https://phcastello.github.io/CursoBootstrap/Aula6" target="_blank">Aula 6</a></h3>
  <h3 class="link"><a href="https://phcastello.github.io/CursoBootstrap/Aula7" target="_blank">Aula 7</a></h3>
  <h3 class="link"><a href="https://phcastello.github.io/CursoBootstrap/Aula8" target="_blank">Aula 8</a></h3>
  <h3 class="link"><a href="https://phcastello.github.io/CursoBootstrap/Aula9" target="_blank">Aula 9</a></h3>
  <h3 class="link"><a href="https://phcastello.github.io/CursoBootstrap/Aula10" target="_blank">Aula 10</a></h3>
  <h3 class="link"><a href="https://phcastello.github.io/CursoBootstrap/Aula11" target="_blank">Aula 11</a></h3>
  <h3 class="link"><a href="https://phcastello.github.io/CursoBootstrap/Aula12" target="_blank">Aula 12</a></h3>
  <h3 class="link"><a href="https://phcastello.github.io/CursoBootstrap/Aula13" target="_blank">Aula 13</a></h3>
  <h3 class="link"><a href="https://phcastello.github.io/CursoBootstrap/Aula14" target="_blank">Aula 14</a></h3>
  <h3 class="link"><a href="https://phcastello.github.io/CursoBootstrap/Aula15" target="_blank">Aula 15</a></h3>
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
    flex: 1 1 45%;
    text-align: left;
  }

  h3#link{
    margin-top: 5px;
    margin-bottom: 5px;
  }
  
  
  @media (max-width: 600px) {
    .links-container h3 {
      flex: 1 1 100%;
    }
  }
</style>
