<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>2026-303-Amunet</title>
</head>
<body>

  <h1>2026-303-Amunet</h1>
  <p>
    Repositório oficial do jogo desenvolvido para a disciplina de <b>Tópicos Avançados de Programação Orientada a Objetos (TAPOO)</b> do COLTEC / UFMG.
  </p>

  <h2>Sobre o Jogo</h2>
  <p>
    <b>Amunet</b> é um jogo focado na exploração de mistérios no Egito Antigo. O jogador transita entre ambientes como o interior de uma pirâmide e um quarto temático egípcio. 
    Toda a direção arte foi feita em <b>pixel art</b>, combinando iluminação interior, ruínas e móveis característicos da época.
  </p>

  <!-- Imagem -->
  <img src="Imagens/image.png" alt="Menu do jogo" width="700">

  <h2>Estrutura de Cenas do Projeto (Godot)</h2>
  <p>O projeto é estruturado utilizando a engine Godot e conta com as seguintes cenas e ambientes mapeados[cite: 1]:</p>

  <ul>
    <li>
      <b>Menu Principal / Interface de Usuário (UI):</b>
      <ul>
        <li>Interface baseada em botões de pergaminho antigo (<code>perga.png</code>)[cite: 1].</li>
        <li>Opções de navegação: <i>Jogar</i>, <i>Configurações</i> e <i>Créditos</i>[cite: 1].</li>
      </ul>
    </li>
    <li>
      <b>Cenas de Cenários e Interação (<code>node2_2d.tscn</code> / <code>node3_2d.tscn</code>):</b>[cite: 1]
      <ul>
        <li><b>Quarto Egípcio:</b> Cenário de fundo em pixel art inspirado em acomodações do Egito Antigo (<code>lucid-origin_Crie_um_fundo...jpg</code>)[cite: 1].</li>
        <li><b>Mesa de Interação / Visão Superior:</b> Elemento de cenário e puzzle interativo contendo mesas vistas tanto de frente quanto em perspectiva superior/top-down[cite: 1].</li>
        <li><b>Interior da Pirâmide:</b> Salas e corredores com teto fechado e ambientação temática (<code>gemini-2.5-flash-image...jpg</code>)[cite: 1].</li>
      </ul>
    </li>
    <li>
      <b>Personagens e Entidades:</b>
      <ul>
        <li><b>Amunet:</b> Sprites e arte da protagonista.</li>
        <li><b>NPCs:</b> Personagens não jogáveis espalhados pelos cenários para interação e progressão de diálogos/questões[cite: 3].</li>
      </ul>
    </li>
  </ul>

  <!-- ONDE ADICIONAR IMAGEM 2: Imagem do Quarto Egípcio ou da Mesa de Interação -->
  <!-- Exemplo: <img src="imagens/lucid-origin_Crie_um_fundo_em_pixel_art_de_um_quarto_inspirado_no_Egito_Antigo._A_cena_deve_t-0 (1).jpg" alt="Cena do Quarto Egípcio" width="700"> -->

  <h2>Acessibilidade</h2>
  <p>Para garantir uma experiência inclusiva, o jogo conta com opções configuráveis no menu de acessibilidade[cite: 1]:</p>
  <ul>
    <li><b>Filtros para Daltonismo:</b> Ajustes de paleta de cores para facilitar a identificação visual de elementos do jogo.</li>
    <li><b>Suporte e Ajustes para Tourette:</b> Mecânicas e configurações adaptadas para redução de estímulos visuais agressivos ou comandos involuntários.</li>
  </ul>

  <!-- ONDE ADICIONAR IMAGEM 3: Menu de Configurações e Acessibilidade -->
  <!-- Exemplo: <img src="imagens/config-removebg-preview.png" alt="Menu de Configurações" width="700"> -->

  <h2>Equipe e Desenvolvimento</h2>
  <ul>
    <li><b>Arthur David</b> - Programação, Lógica do Jogo e Implementação dos Recursos de Acessibilidade.</li>
    <li><b>Sofia Gabriele</b> - Arte, Design de Sprites/Cenários e Acessibilidade Visual[cite: 1].</li>
  </ul>

</body>
</html>
