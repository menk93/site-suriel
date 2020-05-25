<template>
  <v-container grid-list-xs>
    <v-layout row wrap justify-center align-center>
      <v-flex class="dashboard" xs12 sm6 md6 lg6 xl6>
        <h3 data-aos="fade-down" data-aos-duration="2000">Dashboards</h3>
        <p data-aos="fade-left" data-aos-duration="2000">
          <br />O
          <strong>Arquitask</strong> disponibiliza um painel gráfico que
          mostra métricas e
          <strong>indicadores</strong> importantes para
          facilitar de forma visual a compreensão das informações geradas.
          <br />
          <br />Possibilita o
          <strong>monitoramento</strong> de resultados para
          alcançar objetivos e metas traçadas, ajudando nas tomadas de
          decisões.
        </p>
        <ul>
          <li data-aos="fade-left" data-aos-duration="2000">
            Uma linha do tempo com os últimos 12 meses de orçamentos
            realizados indicando os picos de demanda.
          </li>
          <li data-aos="fade-left" data-aos-duration="2000">
            <strong>Indicadores</strong> de orçamentos gerados, que foram
            transformados em
            <strong>"projetos"</strong> e quantos foram
            perdidos.
          </li>
        </ul>
      </v-flex>
      <v-flex
        class="floatImg d-none d-sm-flex justify-center"
        data-aos="zoom-in"
        data-aos-duration="2000"
        xs12
        xl6
        lg6
        md6
        sm6
      >
        <!-- <img :src="require('@/assets/dashboard.jpg')" alt="tablet" /> -->
      </v-flex>
    </v-layout>
  </v-container>
</template>