<script setup>
import QueroContratarButton from './components/QueroContratarButton.vue'
import Card from './components/Card.vue'
import ContactBar from './components/ContactBar.vue'
import Card2 from './components/Card2.vue'
import BottomBar from './components/BottomBar.vue'
import EnterpriseLogoHorizontalDark from './assets/logo-horizontal-dark.png'
import DroneIcon from './assets/icon_drone.png'
import ProjetoIcon from './assets/icon_projeto.png'
import ManutencaoIcon from './assets/icon_manutencao.png'
import CertificadoIcon from './assets/icon_certificado.png'
import PredioIcon from './assets/icon_predios.png'
import CasaIcon from './assets/icon_casa.png'
import JudicialIcon from './assets/icon_judicial.png'
import ConstrucaoIcon from './assets/icon_construcao.png'
import LaudoIcon from './assets/icon_laudo.png'
import VerificadoIcon from './assets/icon_verificado.png'
import MarcadorIcon from './assets/icon_marcador.png'
import TecnologiaIcon from './assets/icon_tecnologia.png'
import VizinhancaIcon from './assets/icon_vizinhanca.png'
import SatisfacaoIcon from './assets/icon_satisfacao.png'
import WhatsappIcon from './components/icons/WhatsAppIcon.vue'
</script>

<template>
  <ContactBar email="contato@edificcontrutora.com" telephone="(41) 98751-7945" instagram="/edific.construtora"/>

  <div class="first-page-container">
      <img :src="EnterpriseLogoHorizontalDark" alt="logo">
      <div class="first-page-text-container">
        <span class="first-page-title">PERÍCIAS, AVALIAÇÕES E DIAGNÓSTICOS DAS EDIFICAÇÕES</span>
        <span class="first-page-subtitle">Seu Parceiro para Obras e Avaliações Imobiliárias.</span>
      </div>
      <QueroContratarButton class="first-page-button"/>
  </div>

  <div class="second-page-container">
    <h2>Serviços da Engenharia Diagnóstica</h2>
    <Card class="second-page-first-card" scopeMessage="" :image="VizinhancaIcon" title="Avaliação de Imóveis:" subtitle="Na Avaliação de Imóveis, determinamos o valor de mercado de uma propriedade com base em critérios técnicos. Essencial para negociações, compra, venda, aluguel e financiamentos, garante uma avaliação justa e precisa do valor do imóvel."/>
    <div class="second-page-cards-container">
      <Card scopeMessage="" :image="ConstrucaoIcon" title="Reformas e Construção:" subtitle="Oferecemos serviços completos de reformas e construção, adaptados às suas necessidades. Realizamos desde pequenas reformas residenciais até grandes projetos comerciais, com foco na qualidade, segurança e eficiência. Acompanhamos todas as etapas da obra, assegurando prazo e orçamento estabelecidos."/>
      <Card scopeMessage="" :image="ProjetoIcon" title="Projetos de Engenharia Civil:" subtitle="Desenvolvemos projetos de engenharia civil com precisão técnica e inovação. Nossa equipe elabora projetos estruturais, hidráulicos, elétricos e de infraestrutura, integrando soluções sustentáveis. Oferecemos suporte completo desde a concepção até a execução, garantindo funcionalidade, estética e segurança."/>
      <Card scopeMessage="" :image="LaudoIcon" title="Laudo Pericial:" subtitle="Elaboramos laudos periciais técnicos detalhados para avaliar condições de imóveis e construções. Identificamos patologias construtivas, analisamos estruturas e verificamos conformidade com normas. Atuamos em processos judiciais e extrajudiciais, fornecendo relatórios precisos e imparciais para resolução de disputas e decisões fundamentadas."/>
      <Card scopeMessage="" :image="PredioIcon" title="Inspeção Predial:" subtitle="Na Inspeção Predial, avaliamos as condições gerais de um edifício, incluindo instalações elétricas, hidráulicas, sistemas de segurança, revestimentos e áreas comuns. Identificamos problemas e necessidades de manutenção para garantir funcionalidade, segurança e preservação do patrimônio."/>
      <Card scopeMessage="" :image="DroneIcon" title="Inspeção com Drones:" subtitle="A Inspeção de Drones usa drones para inspecionar áreas de difícil acesso ou grandes extensões, capturando imagens e dados precisos. Isso permite uma análise detalhada e segura, ideal para monitoramento e inspeções em setores como construção, agronegócio e infraestrutura."/>
      <Card scopeMessage="" :image="CertificadoIcon" title="Vistoria Cautelar de Vizinhança:" subtitle="A Vistoria Cautelar de Vizinhança inspeciona e documenta as condições das propriedades vizinhas antes de uma obra, prevenindo conflitos e identificando danos prévios para assegurar a responsabilidade por eventuais danos durante a construção."/>
      <Card scopeMessage="" :image="ManutencaoIcon" title="Gerenciamento de Obras:" subtitle="Oferecemos gerenciamento de obras para garantir que seu projeto seja concluído no prazo e dentro do orçamento. Coordenamos todas as fases da construção, supervisionando cronogramas. Garantimos a resolução rápida de problemas e mantemos tudo alinhado aos objetivos do cliente, assegurando uma execução eficiente."/>
      <Card scopeMessage="" :image="CasaIcon" title="Laudo de Vistoria de Recebimento e Entrega de Imóveis:" subtitle="O Laudo de Vistoria de Recebimento e Entrega de Imóveis documenta as condições de um imóvel ao ser entregue ou recebido, registrando seu estado de conservação e identificando defeitos ou pendências. Garante transparência e segurança nas transações imobiliárias, prevenindo disputas."/>
      <Card scopeMessage="" :image="JudicialIcon" title="Assistência Técnica em Ações Judiciais:" subtitle="Na Assistência Técnica em Ações Judiciais, oferecemos suporte especializado em questões imobiliárias, elaborando laudos periciais, vistorias e pareceres técnicos para servir como provas em disputas legais, garantindo uma avaliação imparcial e fundamentada para resolver conflitos judiciais."/>
    </div>
  </div>

  <div class="third-page-container">
    <div class="third-page-text-container">
      <h2>EDIFIC CONSTRUTORA</h2>
      <p>Realizamos o diagnóstico em edificações buscando garantir a sua integridade e atribuindo soluções aos problemas construtivos, sejam estes originados na fase de projetos, durante a execução da obra, por carência de manutenção, em função de vícios construtivos, ou ainda, em razão de sinistros.</p>
      <p>Com objetivo de ser referência no mercado da perícia técnica e diagnóstica, a Edific Construtora visa priorizar a segurança, a durabilidade e habitabilidade das edificações, além de, atentar a saúde e o bem estar de seus usuários.</p>
      <p>Possuímos equipes especializadas, buscamos todas as a  tualizações tecnológicas, além de seguir com rigor as normas da associação brasileira de normas técnicas (ABNT).</p>
    </div>
    <QueroContratarButton class="third-page-button"/>
  </div>

  <div class="fourth-page-container">
    <h2>PORQUE ESCOLHER EDIFIC</h2>
    <div class="fourth-page-cards-container">
      <Card2 title="Atendimento Personalizado" :image="VerificadoIcon" description="Atendimento personalizado, focado nas necessidades específicas de cada cliente."/>
      <Card2 title="Amplo Conhecimento Técnico" :image="MarcadorIcon" description="Equipe com vasta experiência em projetos complexos, assegurando soluções eficazes e inovadoras."/>
 
      <Card2 title="Tecnologia de Ponta" :image="TecnologiaIcon" description="Uso de tecnologias da atualidade em diagnósticos e soluções, proporcionando maior precisão e eficiência."/>
      <Card2 title="Satisfação do Cliente Garantida" :image="SatisfacaoIcon" description="Alta taxa de satisfação dos clientes, comprovada por inúmeros depoimentos e casos de sucesso."/>
    </div>    
    <!-- <QueroContratarButton class="fourth-page-button"/> -->
  </div>

  <div class="fifth-page-container">
    <WhatsappIcon class="fifth-page-icon"/>
    
    <h1>Precisa contratar nossos serviços?</h1>
    <h2>Entre em contato no botão abaixo que iremos te ajudar.</h2>

    <QueroContratarButton/>
  </div>

  <div class="sixth-page-container">
    <BottomBar :enterpriseLogo="EnterpriseLogoHorizontalDark" whatsapp="(41) 98751-7945" email="contato@edificcontrutora.com" instagram="@tabengenharia"/>
  </div>
</template>

<style scoped>
.first-page-container{
  z-index: 1;
  display: flex;
  flex-direction: column;
  height: 670px;
  justify-content: center;
  align-items: center;
  position: relative;
  background-image: url('./assets/first-page-background.fw.webp');
  background-repeat: no-repeat;
  background-size: cover;
}
.first-page-container > img{
  max-width: 400px;
  position: absolute;
  top: 0;
  margin-top: 80px;
}
.first-page-text-container{
  max-width: 850px;
  display: flex;
  flex-direction: column;
  padding: 0px 20px;
}
.first-page-title{
  font-size: 40px;
  font-weight: 600;
  color: #fff;
  text-transform: uppercase;
  line-height: 1;
  margin-bottom: 10px;
  text-align: center;
}
.first-page-subtitle{
  text-align: justify;
  color: #fff;
  font-size: 17px;
  text-align: center;
}
.first-page-button{
  position: absolute;
  bottom: 0;
  margin-bottom: 140px;
}
@media (max-width: 760px) {
  .first-page-container{
    height: fit-content;
  }
  .first-page-title{
    font-size: 32px;
    line-height: 1.2em;
  }
  .first-page-container > img{
    margin-top: 0;
    position: initial;
    margin-bottom: 14px;
    max-width: 400px;
    width: 80vw;
    margin-top: 40px;
  }
  .first-page-button{
    position: initial;
    margin-bottom: 0;
    margin-top: 36px;
    margin-bottom: 50px;
  }
}
/* ----------------------------------------------- */
.second-page-container{
  display: flex;
  flex-direction: column;
  align-items: center;
  padding: 60px 20px;
  text-align: center;
}
.second-page-container > h2{
  color: #282828;
  font-size: 35px;
  font-weight: 600;
  margin-bottom: 36px;
}
.second-page-first-card{
  max-width: 700px;
  margin-bottom: 26px;
  height: 260px;
}
.second-page-cards-container{
  display: grid;
  gap: 26px;
  grid-template-columns: repeat(3, 1fr);
}
@media (max-width: 1165px) {
  .second-page-cards-container{
    grid-template-columns: repeat(1, 1fr);
    gap: 20px;
  }
  .second-page-cards-container > div{
    max-width: 700px;
    height: fit-content;
    padding-bottom: 124px;
  }
  .second-page-first-card{
    margin-bottom: 20px;
    max-width: 700px;
    height: fit-content;
    padding-bottom: 124px;
  }
  .second-page-container{
    padding: 60px 0px;
  }
}
/* ----------------------------------------------- */
.third-page-container{
  display: flex;
  flex-direction: column;
  align-items: center;
  padding: 60px 0px;
  background-image: url('./assets/curitiba-do-alto-guilherme-pupo-2.fw.webp');
  background-repeat: no-repeat;
  background-size: cover;
  color: #fff;
}
.third-page-text-container{
  max-width: 680px;
  padding: 50px 20px;
  padding-bottom: 30px;
  padding-top: 0;
  
}
.third-page-text-container > h2{
  font-size: 45px;
  font-weight: 600;
  line-height: 46px;
  margin-bottom: 20px;
  text-align: center;
}
.third-page-text-container > p{
  text-align: justify;
  font-size: 17px;
  margin-top: 10px;
}
@media (max-width: 547px) {
  .third-page-text-container > h2{
    font-size: 35px;
    text-align: center;
  }
}
/* ----------------------------------------------- */
.fourth-page-container{
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  padding: 60px 0px;
  color: #282828;
  background-color: #f2f2f2;
  text-align: center;
}
.fourth-page-container > h2{
  font-size: 40px;
  font-weight: 600;
  padding: 0px 16px;
  padding-bottom: 26px;
}
.fourth-page-cards-container{
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  max-width: fit-content;
  gap: 16px;
  padding: 0px 10px;
}

.fourth-page-button{
  margin-top: 38px;
}

@media (max-width: 1060px) {
  .fourth-page-cards-container{
    grid-template-columns: repeat(1, 1fr);
    width: fit-content;
    gap: 15px;
  }
}
@media (max-width: 420px) {
  .fourth-page-cards-container{
    gap: 20px;
  }
}
/* ----------------------------------------------- */
.fifth-page-container{
  min-height: 430px;
  color: white;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  text-align: center;
  padding: 36px 0px;
  background-image: url('./assets/landscape-city-cityscape-lake-water-nature-847001-wallhere.com.fw.webp');
  background-repeat: no-repeat;
  background-size: cover;
}
.fifth-page-icon{
  height: 100px;
  margin-bottom: 26px;
  fill: white;
}
.fifth-page-container > h1{
  font-size: 35px;
  font-weight: 600;
  line-height: 40px;
  margin-bottom: 12px;
  padding: 0px 20px;

}
.fifth-page-container > h2{
  font-size: 20px;
  font-weight: 500;
  line-height: 26px;
  margin-bottom: 26px;
  padding: 0px 20px;
}

</style>
