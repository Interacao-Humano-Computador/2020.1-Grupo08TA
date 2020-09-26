# Análise de tarefas

##  Conceito 

Processo de analisar e articular a tarefa que os usuários buscam ou devem fazer através do uso do produto.

Análise de como uma tarefa é exercida, compreendendo de uma descrição detalhada tanto de atividades físicas como mentais, duração da tarefa, frequência da tarefa, alocação da tarefa, complexidade da tarefa, condições ambientais, vestimenta e equipamento necessários, e todo outro fator envolvido ou exigido por uma ou mais pessoas para realizar uma dada tarefa.

Uma análise de tarefa divide uma tarefa difícil em seus componentes, que são seus conhecimentos procedimentais e afirmativos.

Descrição minuciosa daquilo que uma pessoa competente faz ou deve fazer quando executa uma tarefa.

Pode ser usada com vários objetivos, tais como projetar, avaliar, automatizar, tendo então, diversos níveis de abstração.

Corriqueiro nas áreas de treinamento, seleção de pessoal, design instrucional, IHC etc

O seis itens que definem os princípios da análise são:

* Visibilidade
* Retorno
* Restrições
* Mapeamento
* Consistência
* Fornecimento

### Visibilidade 

O expectativa deste princípio é manter as funções visíveis e facilitar a localização do controle certo para a tarefa com agilidade. Se utiliza um termo nesse tópico que segue a sigla: "WYSIWYG" - What You See Is What You Get, que siguinifica algo como “o que você vê é o que você tem”. Salientando portanto a importância de mostrar todas as funções para o usuário.

Com esse aspecto pretendemos melhorar a distribuição de botões e icones da página que são contra-intuitivos, por exemplo o botão do menu que não fica próximo ao menu. É necessário tambem mudar os icones e por labels a eles para deixá-los mais signficativos. Sobre o layout completo do site é necessário atualiza-lo e coloca-lo de forma mais moderna em confirmidade com os layouts de sites modernos.

### Retorno

Nesse princípio é levantada a importancia de existir retornos do sistema as ações do usuário para assim tirar qualquer incerteza do estado do sistema que pode existir ao usuário executar uma ação. A falta de um bom retorno ao usuário pode gerar erros no sistema, uma vez que pode ser requisitada a mesma ação várias vezes gerando uma lentidão ou quando a falta de retorno de uma ação a qual não foi executada de forma incorreta deixando assim o usuário achando que ação foi concluida com sucesso. 

Com essse princípio em mente foram analisadas as respostas do site, que performou bem, quase todas as ações do usuário no site que necessitam de retorno o possuem, porem é necessário deixar os retornos mais intuitivos e explicativos. Todos os retornos são feitos atraves de alert e portanto necessário a interação do usuário para fechar o alert, mesmo quando é uma mensagem de sucesso deixando assim cansativo o uso do site quando utilizado por muito tempo o que é o caso de algumas pessoas. Com essa perspectiva o grupo pretende melhorar a exposição dos retornos, deixando claro atrves de cores intuitivas se as ações foram realizadas com sucesso ou não, e retirar a necessidade de interagir com todos os retornos e melhorar o aspecto estético.

### Restrições

São formas de delimitar a ação do usuário garantindo que, em meio a uma vasta quantidade de opções, ele escolha a correta para continuar a atividade. Os beneficios que isso garante são evitar diversos erros.
Como o site tem poucas opções fica bem evidenciado as opções corretas, atraves do menu e de boas descrições para as abas. O sistema tambem não permite fazer ações que o usuário não pode, tirando do escopo essas ações, porem existem dois pequenos detalhes no site que induzem o usuário ao erro, o primeiro é o icone de usuário na parte superior direita que é clicável, levando o usuário a crer que seria redirecionado a uma página de edição de perfil que é o comum aos sites e na veradade o icone não dispara ação nenhuma. O segundo é o icone do site que se encontra na parte superior esquerda do site, que tambem é clicável porem não executa ação alguma, o que vai contra o fluxo normal de um site que ao clicar no icone do site é redirecionado a página inicial. Portante são os dois pontos que o grupo pretende atacar nesse princípio.

### Mapeamento

Mapeamento se diz em relção a manipulação dos controles serem adequadas, de um jeito que o usuário consiga entender o que uma coisa faz. Muito utilizado para descrever essas ações de um jeito simples é por simbolos universais, como uma seta pode indicar para voltar para a página anterior em um local óbvio.

Nesse ponto o site possuem poucas coisa que necessitam de mudança, a grande maioria dos botões possuem legendas ou placeholders e icones significativos, ficando portanto atacar esses poucos pontos de mudança.

### Consistência

Consistência tem como objetivo padronizar certas tarefas. Como por exemplo um teclado de banco que tem o mesmo formato e cores adequadas para as mesmas funcionalidades. A inconcistência pode trazer confusão para o usuário que esta navegando, dando uma sensação de perdido.
Nesse sentido o site todo possui uma padronização, porem ela é contra-intuitiva uma vez que não há diferenciação de cores e tamanhos para elementos diferentes tornando a experiência do usuário mais difícil do que poderia ser caso fosse adotada uma padronização intuitiva. O grupo pretende deixar a padronização do site mais intuitiva para que o uso se torne mais flúido.


### Fornecimento

Trata das propriedades percebidas de um objeto que determinam como ele pode ser usado. Só olhando, o usuário sabe o que fazer, pois utiliza o mínimo de esforço. A partir das características do objeto, o usuário, mesmo sem o conhecer, cria uma idéia da funcionalidade do mesmo. O processo é óbvio e não precisa ser aprendido.
O site possui alguns problemas de fornecimento que deixam dúbias as funcionalidades de alguns campos, como por exemplo os campos de data que possuem tanto um input quanto um calendário onde a data pode ser selecionada, deixando assim em dúvida o usuário qual forma utilizar para entrar com a data. Outro exemplo desses problemas são as repetições de botões iguais na parte de cima e de baixo da página que geram confusão ao usuário uma vez que não fica claro qual grupo de botões deve ser utilizado e se existe alguma diferença em usar um o outro conjunto, deixando assim indeterminado o uso dos mesmos.
O grupo pretende retirar esses obejtos que geram dubiedade de uso e deixar exposto através de icones intuitivos o uso de cada objeto do sistema.

## Históricos de versões

|    Data    | Versão |             Descrição             |          Autor(es)           |
| :--------: | :----: | :-------------------------------: | :--------------------------: |
| 10/09/2020 |  0.1   | Criação do boilerplate do arquivo | Hugo Sobral e Leonardo Gomes |
| 26/09/2020 |  1.0   | Adição do conteudo do documento   | João Lucas Zarbiélli         |