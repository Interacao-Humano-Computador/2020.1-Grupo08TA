  <h2>SEI</h2>
  <p align="justify">&emsp;&emsp;O Sistema Eletrônico de Informações (SEI) é um sistema de produção e gestão de documentos e processos eletrônicos desenvolvido pelo Tribunal Regional Federal da 4ª Região (TRF4) e cedido gratuitamente à administração pública. </p>
  <p align="justify">&emsp;&emsp;O SEI foi escolhido como a solução de processo eletrônico no âmbito do projeto Processo Eletrônico Nacional (PEN) – iniciativa conjunta de órgãos e entidades de diversas esferas da administração pública, com o intuito de construir uma infraestrutura pública de processos e documentos administrativos eletrônicos, e têm sido implantado em vários órgãos e entidades das mais variadas esferas administrativas. </p>

  <h3>Sobre o projeto</h3>

  <p align="justify"> &emsp;&emsp;Este repositório foi criado para a disciplina de Interação Humano Computador da Universidade de Brasília com o objetivo de confeccionar toda a documentação requisitada pelo curso. </p>
  <p align="justify"> &emsp;&emsp;O objeto de estudo escolhido pelo grupo foi o website SEI. </p>

  <h3>Membros da equipe</h3>

  <div class="members">
    <a href="https://github.com/kisobral">
    <div class="member" >
      <img src="./assets/images/members/Hugo.jpeg" alt="Hugo" >
      <p >
        Hugo Sobral</br>18/0018604
      </p>
    </div>
    </a>
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
    display: grid; 
    grid-template-columns: auto auto auto;
    margin-top: 20px;
  }
  .member img{
    position: relative;
    height: 200px;
    width: 200px;
    opacity: 1;
    border-style: solid;
    border-radius: 100px;
    border-width: 1px; 
    border-color: rgba(0,0,0,0.3);
    z-index: 3;
    transition: opacity 0.5s !important;
  }
  .member img:hover{
    opacity: 0.5;
    z-index: 1;
  }
  
 .member{
   margin: 20px;
   display: flex;
   justify-content: center;
  }
 
 .member p{
    position: absolute;
    transform: translate(0, 70px);
    z-index: 2;
    font-weight: bold;
    font-family: Montserrat;
  }

  .member p:hover{
      cursor: default;
  }

  h2, p {
    font-family: Montserrat !important;
    font-weight: 500;
  }

  h3 {
    font-family: Montserrat !important;
    font-weight: bold;
  }
</style>
