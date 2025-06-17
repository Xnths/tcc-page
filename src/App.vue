<template>
  <section></section>
  <section>
    <h1>Proposta de trabalho</h1>
    <h2>Introdução</h2>
    <p>
      Na contemporaneidade, os produtos digitais interativos saturam o cotidiano
      de toda demografia global. Em particular, as aplicações móveis contribuem
      para o conforto, aprendizado e recreação dos usuários. A tecnologia chega
      até a extrapolar o mundo virtual e se mesclar no mundo material. QR Codes,
      por exemplo, auxiliam na comunicação digital. Basta apontar a câmera para
      que o dispositivo interaja com a realidade e direcione o usuário para o
      mundo virtual.
    </p>
    <p>
      Essa mescla se tornou mais nítida com o avanço das técnicas de visão
      computacional. Forçosamente, surgiram aplicativos centrados nessa
      tecnologia. Temos, então, objetos do mundo virtual que interagem com o
      mundo físico e vice-versa. No British Museum, por exemplo, há
      possibilidade de alugar um tablet com um aplicativo personalizado
      instalado no dispositivo. Nele os visitantes podem obter mais informações
      sobre elas ao usar a câmera do dispositivo.
    </p>
    <p>
      Não precisa se distanciar da realidade nacional. A professora Giselle
      Beiguelman da Faculdade de Arquitetura e Urbanismo (FAU - USP) realizou o
      projeto demonumentaRA. Análogo, ao museu britânico, utilizou-se realidade
      aumentada para mesclar o físico e o virtual. Porém, o propósito foi
      diferente. Ao invés de objetos físicos serem incrementados, a professora
      propôs trazer monumentos arquitetônicos para serem postos no campus da
      Universidade. Então, na praça do relógio foram instaladas placas indicando
      a “existência” deles. Ao transeunte desavisado não se observa nada.
      Necessitava-se que o observador instalasse o aplicativo desenvolvido pela
      FAU, a fim de ver os objetos. Pela câmera viam-se os modelos como se
      estivessem no espaço físico realmente.
    </p>
    <p>
      Inserido nesse contexto, integra-se essa mesma tecnologia na educação. A
      Matemateca, como um pequeno Museu matemático, planeja usufruir da
      realidade aumentada. As peças interativas já servem o propósito de
      materializar as abstrações matemáticas para seus visitantes não
      acadêmicos. No entanto, com AR será possível realizar muitos outros
      avanços para corroborar nessa iniciativa. Ampliam-se, com isso, as opções
      de design, propondo novas formas de interagir e aprender.
    </p>
    <h2>Proposta de trabalho</h2>
    <h3>Contexto</h3>
    <p>
      No Instituto de Matemática e Estatística, desde 2003, constrói-se um
      acervo de objetos interativos. Durante anos, professores, alunos e
      artesãos contribuíram complementando esse pequeno museu com tabuleiros
      lúdicos, formas geométricas e demonstrações de conceitos matemáticos,
      cujos mistérios velados em equações, filosofias e abstrações se desnudam
      na frente dos visitantes. Embora o projeto disponha de monitores
      voluntários, os quais mediam as visitas, inviabiliza-se sua presença
      permanente. De fato, dispor de alguém durante todo o período em que a
      Matemateca está montada no instituto não é possível, pois ficam-se dias ou
      até meses sem previsão de sua retirada do saguão do Bloco B.
    </p>
    <p>
      Por isso, há a necessidade de alternativas para a mediação. Pensando
      nisso, o professor Eduardo Colli consolidou um projeto para integrar AR
      (Augmented Reality) nas peças. Junto ao Lab3D começou-se o desenvolvimento
      de um aplicativo utilizando Unity com Vuforia. Essa opção mais simples
      para ser desenvolvida por pessoas que não são da computação pareceu uma
      primeira alternativa. No entanto, o fluxo de desenvolvimento com essa
      ferramenta não consegue se sustentar para se tornar um aplicativo móvel
      com entrega contínua (CI/CD).
    </p>
    <p>
      Deseja-se, portanto, adotar métodos de desenvolvimento mais rigorosos.
      Aplicando conceitos de visão computacional e adotando boas práticas de
      desenvolvimento de software em larga escala, esse presente trabalho tem
      por objetivo colaborar com o projeto da Matemateca, contribuindo para que
      a computação sirva o propósito social de integração à comunidade externa à
      Universidade de São Paulo.
    </p>
    <h3>Cronograma</h3>
    <p>
      Inicialmente, deseja-se aproveitar o que já foi definido anteriormente.
      Logo, começaremos a estudar as limitações da tecnologia de forma que ela
      seja acessível ao público geral. Isso significa que queremos
      disponibilizar ao final desse projeto um aplicativo que possa ser
      utilizado pelos smartphones comuns sem exclusão de nenhum usuário por
      funcionalidade baseado em sistema operacional ou sensores.
    </p>
    <p>
      Depois, queremos definir cenas a serem implementadas. As decisões de
      design contarão com a colaboração da equipe do Lab 3D e orientação do
      professor Eduardo Colli. Embora não seja o foco, iremos nos ocupar em
      seguir boas práticas de usabilidade. Isso significa que teremos o cuidado
      de refinar qualquer ideia proposta antes de prosseguir para a
      implementação. Por fim, é fundamental seguir as metodologias ágeis.
      Portanto, teremos sprints que ficarão documentadas no site do TCC.
    </p>
  </section>
</template>

<style scoped>
p,
h1,
h2,
h3 {
  text-align: justify;
  overflow-wrap: break-word;
  hyphens: auto;
}

.text {
  text-align: left;
}

.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
