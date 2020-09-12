  <img src="./assets/images/word_mark.png" alt="SEI">
  <h2>SEI</h2>
  <p align="justify">&emsp;&emsp;O Sistema Eletrônico de Informações (<a href="https://sei.df.gov.br/sip/login.php?sigla_orgao_sistema=GDF&sigla_sistema=SEI">SEI</a>) é um sistema de produção e gestão de documentos e processos eletrônicos desenvolvido pelo Tribunal Regional Federal da 4ª Região (TRF4) e cedido gratuitamente à administração pública. </p>
  <p align="justify">&emsp;&emsp;O SEI foi escolhido como a solução de processo eletrônico no âmbito do projeto Processo Eletrônico Nacional (PEN) – iniciativa conjunta de órgãos e entidades de diversas esferas da administração pública, com o intuito de construir uma infraestrutura pública de processos e documentos administrativos eletrônicos, e têm sido implantado em vários órgãos e entidades das mais variadas esferas administrativas. </p>

  <h3>Sobre o projeto</h3>

  <p align="justify"> &emsp;&emsp;Este repositório foi criado para a disciplina de Interação Humano Computador da Universidade de Brasília com o objetivo de confeccionar toda a documentação requisitada pelo curso. </p>
  <p align="justify"> &emsp;&emsp;O objeto de estudo escolhido pelo grupo foi o website <a href="https://sei.df.gov.br/sip/login.php?sigla_orgao_sistema=GDF&sigla_sistema=SEI">SEI</a>, ao qual serão executadas todas as técnicas dissertadas ao longo da disciplina para que este apresente uma boa interação com os usuários em suas funcionalidades. </p>

  <h3>Integrantes da equipe</h3>

  <div class="members">
    <div class="member" >
      <img src="./assets/images/members/Hugo.jpeg" alt="Hugo" >
      <p >
        Hugo Sobral</br>18/0018604
      </p>
    </div>
    <div class="member">
      <img src="./assets/images/members/Joao.jpg" alt="João">
      <p>João Zarbiélli</br>17/0146251<p>
    </div>
  </div>
  <div class="members line2">
    <div class="member">
      <img src="./assets/images/members/Leonardo.jpg" alt="Leonardo">
      <p>Leonardo Gomes</br>18/0021974<p>
    </div>
    <div class="member">
      <img src="./assets/images/members/Victor.jpg" alt="member name">
      <p>Victor Jorge</br>18/0055241<p>
    </div>
  </div>
</div>

<style>
  .members {
    display: flex;
    justify-content: space-around;
    margin-top: 20px;
  }
  .member img{
    position: relative;
    width: 200px;
    opacity: 1;
    border-style: solid;
    border-radius: 100px;
    border-width: 7px; 
    border-color: rgba(0,124,185);
    z-index: 3;
    transition: opacity 0.5s !important;
  }
  .member img:hover{
    opacity: 0.5;
    z-index: 1;
    border-color: rgba(242, 183, 5)
  }
  
 .member{
   margin: 10px;
   display: flex;
   justify-content: center;
   align-items: center;
  }
 
 .member p{
    font-size: 14px;
    position: absolute;
    z-index: 2;
    font-weight: bold;
  }

  .member p:hover{
      cursor: default;
  }

  h2, p {
    font-weight: 500;
  }

  h3 {
    font-weight: bold;
  }
</style>
