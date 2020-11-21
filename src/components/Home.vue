<template>
  <div class="container">
    <div class="row">
      <div class="col-md-8 col-sm-12">
        <div class="logo">
          <img class="logo-imagem" src="../assets/logo.png" alt="Logo Poalab" />
          <h1 class="logo-texto">POALAB</h1>
        </div>
      </div>
      <div class="col-md-4 col-sm-12 menu">
        <ul class="menu-lista">
          <li class="item-menu"><a href="#sobre-nos">Sobre nós</a></li>
          <li class="item-menu"><a href="#links-uteis">Links úteis</a></li>
          <li class="item-menu"><a href="#espaco">Espaço</a></li>
          <li class="item-menu"><a href="#equipamentos">Equipamentos</a></li>
          <li class="item-menu"><a href="#nossos-canais">Nossos canais</a></li>
          <li class="item-menu"><a href="#open-day">Open Day</a></li>
          <li class="item-menu"><a href="#calendario">Calendário</a></li>
        </ul>
      </div>
    </div>
    <div class="row secao" id="sobre-nos">
      <p>
        O POALAB é um laboratório de fabricação digital e está conectado à rede
        mundial de fab labs. Opera como um programa de extensão do IFRS campus
        Porto Alegre.
      </p>

      <p>
        Temos como missão popularizar o acesso e letramento na fabricação
        digital, funcionando como uma plataforma de criatividade, aprendizagem e
        invenção.
      </p>

      <p>
        Ser um Fab Lab significa estar conectado a uma comunidade mundial de
        alunos, educadores, técnicos, pesquisadores e inovadores e desenvolver
        atividades dentro da filosofia do conhecimento aberto.
      </p>

      <p>
        Conheça a
        <a
          class="link-destaque"
          href="http://www.fabfoundation.org/index.php/the-fab-charter/index.html"
          target="_blank"
          >FAB CHARTER</a
        >, a carta de intenções que regra os Fab Labs.
      </p>
    </div>
    <div class="secao-titulo" id="links-uteis">Links Úteis</div>
    <div class="secao"></div>
    <div class="secao-titulo" id="espaco">Espaço</div>
    <div class="secao"></div>
    <div class="secao-titulo" id="equipamentos">Equipamentos</div>
    <div class="secao">
      <div class="tiles">
        <a class="tile" href="#">
          <img
            title="Wanhao"
            alt="impressora 3D"
            src="https://www.poalab.net.br/images/wanhao.png"
            width="230"
          />
          <div class="details">
            <span class="title">2 Impressoras 3D Wanhao<br />Duplicator 4</span>
            <span class="info">
              2 extrusores<br />
              filamento 1.75mm<br />
              camada entre 0.1 e 0.5mm<br />
              área: 225mm x 145mm x 150mm<br />
              base aquecida<br />
            </span>
          </div>
        </a>
      </div>
      <div class="tiles">
        <a class="tile" href="#">
          <img
            title="Printrbot"
            alt="impressora 3D"
            src="https://www.poalab.net.br/images/printrbot.png"
            width="230"
          />
          <div class="details">
            <span class="title"
              >1 Impressora 3D printrbot<br />simple metal</span
            >
            <span class="info">
              filamento de 1.75mm<br />
              resolução de camada entre 0.1 e 0.5mm<br />
              área de trabalho: 152mm x 152mm x 152mm<br />
            </span>
          </div>
        </a>
      </div>
    </div>
    <div class="secao-titulo" id="nossos-canais">Nossos canais</div>
    <div class="secao">
      <a
        class="redes-sociais"
        href="https://www.facebook.com/poalab"
        target="_blank"
      >
        <img
          title="facebook"
          alt="facebook"
          src="https://www.poalab.net.br/images/redes/facebook.png"
          width="50"
        />
      </a>
      <a
        class="redes-sociais"
        href="https://www.youtube.com/channel/UCWZzR8M4KKD6l7hpOZb9viA"
        target="_blank"
      >
        <img
          title="youtube"
          alt="youtube"
          src="https://www.poalab.net.br/images/redes/youtube.png"
          width="50"
        />
      </a>
    </div>
    <div class="secao-titulo" id="open-day">Open Day</div>
    <div class="secao">
      <p>Sextas-feiras das 14h às 18h</p>
      <p>
        Os open days são um dos requisitos para a existência de um fab lab.
        Nestes dias, a comunidade externa têm a possibilidade de conhecer as
        ferramentas existentes no lab e aprender sobre fabricação digital. Cada
        fab lab possui suas regras de open day.
      </p>
      <p>Essas são as regras do PoaLab:</p>
      <p>
        Não existe custo para acessar o lab ou utilizar as máquinas; Não existe
        reserva de equipamento; Os usuários são convidados a cadastrar os seus
        projetos no sistema de projetos do PoaLab para compartilhamento com a
        comunidade; Os usuários devem trazer os insumos necessários para os
        projetos; Temos material, equipamento, pessoal e disposição para atender
        a todos, independente de conhecimento; Em 2 anos de funcionamento a
        faixa etária de usuários variou entre 5 e 76 anos... queremos avançar
        nos dois limites; O objetivo do lab é o de disseminar conhecimento -- se
        você não tem nenhum conhecimento sobre fabricação digital, o lab foi
        feito pra você!
      </p>
      <p>
        Continua com dúvidas? Mande mensagem via email ou via página do
        Facebook!
      </p>
    </div>
    <div class="secao-titulo" id="calendario">Calendário</div>
    <div class="secao">
      <iframe
        src="https://calendar.google.com/calendar/embed?src=poalabifrs%40gmail.com&ctz=America%2FSao_Paulo"
        style="border: 0"
        width="800"
        height="600"
        frameborder="0"
        scrolling="no"
      ></iframe>
    </div>
  </div>
</template>

<script>
export default {
  name: "Home",
};
</script>

<style scoped>
.container {
  max-width: 100%;
  text-align: center;
}

.logo {
  display: inline-block;
}

.logo-imagem {
  max-width: 100%;
  max-height: 100%;
  display: block;
}

.logo-texto {
  font-family: "Lucida Console";
  font-size: 100px;
}

.menu {
  background-color: #35469d;
  max-width: 100%;
  max-height: 100%;
}

.menu-lista {
  display: flex;
  flex-direction: column;
  justify-content: space-around;
  padding: 10%;
  margin: 0;
  list-style: none;
  height: 100%;
}

.menu-lista .item-menu {
  font-size: 1.5em;
  font-weight: 300;
  line-height: 1.7em;
  color: white;
}

.menu-lista .item-menu a,
.menu-lista .item-menu a:hover,
.menu-lista .item-menu a:focus {
  color: inherit;
  text-decoration: none;
}

a:hover {
  font-weight: bolder;
}

.secao-titulo {
  background-color: #35469d;
  color: white;
  font-size: 1.7rem;
}

.secao {
  padding: 5% 25% 5% 25%;
  font-family: "Lucida Console";
  color: #696969;
  text-align: center;
}

.redes-sociais {
  margin: 0 15px;
}

.link-destaque {
  color: #35469d;
}
</style>
