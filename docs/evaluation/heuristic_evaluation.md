# Avaliação heurística

## Objetivo

Identificar problemas de usabilidade associados ao Site SEI

## Escopo da Avaliação

A avaliação de heurísticas será aplicada em todo o site para as funcionalidades que envolvem a UnB, para assim termos uma visão completa dos problemas de usabilidade que envolvem o SEI.

## Método

Serão usadas 10 heuristicas de Nielsen sendo elas:
||
|:----|
|Visibilidade do estado do sistema|
|Correspondência entre o sistema e o mundo real|
|Controle e liberdade do usuário|
|Consistência e padronização|
|Prevenção de erros|
|Reconhecimento em vez de memorização|
|Flexibilidade e eficiência de uso|
|Estética e Design minimalistas|
|Recuperação de erros|
|Ajuda e Documentação |

Após a análise levando em conta essas heurísticas será gerado uma tabela com as seguintes informações:
||
|:---|
|Descrição|
|Local onde ocorre|
|Severidade do problema|
|Diretriz(es) violada(s)|
|Impacto |
|Sugestões de solução|

## Resultado

|Nº | Descrição | Local | Gravidade | Diretriz | Impacto | Solução |
|:- | :-------- |:----- | :-------- | :--------| :------ | :------ |
| 1 | Usuários externos que desejam fazer login não possuem opção de cadastro| Página de Login | Alta | Correspondência entre o sistema e o mundo real | Impossibilidade de uso | Criação de um botão de cadastro para usuários externos |
| 2 |Não há qualquer botão ou modal que ajude a proceder com o login| Página de Login | Alta | Ajuda e Documentação | Atrapalha o uso uma vez que é necessário acessar outro site para ter acesso a documentação | Trazer documentação para o próprio site|
| 3 | Os usuários com deficiência visual não são aptados a utilizar o site pois mesmo com a assitência de voz, existem íconess que não possuem legendas. Portanto não sendo possível a leitura pelo assistente e a utilização daquele recurso | Todo o site | Alta | Flexibilidade e eficiência de uso | Impossibilidade de uso | Adicionar legendas a todos os íconess |
| 4 | O link do menu não segue o padrão de está acima do menu, criando a sensação que existe um segundo menu ao clicar no link | Página Inicial | Baixa | Consistência e padronização | Confusão ao usar o site pela primeira vez | Mudar o local do link para acima do menu e transformá-lo para botão | 
| 5 | ícone de usuário é clicavel mas não dispara função ao clica-lo| Em todo o site | Baixa | Consistência e padronização |  Confusão ao usar o site pela primeira vez | Transformar as informações exibidas ao manter o cursor sobre o ícone em informações fixas e visíveis no cabeçalho do site |
| 6 | O ícone de saída do site não possui legenda, possibilitando um logout do usuário sem que o mesmo queira sair do sistema | Todo o site | Alta | Flexibilidade e eficiência de uso |  Confusão ao usar o site | Colocar legenda no botão de saída |
| 7 | Ao clicar no botão de saída não há confirmação da ação | Todo o site  | Alta | Prevenção de erros | Possibilidade de execução de ação indesejada | Colocar um modal de confirmação de saída |
| 8 | O ícone do site é clicável mas não executa nenhuma ação | Em todo o site | Baixa | Consistência e padronização | Confusão ao usar o site pois é intuitivo que ao clicar no ícone do site você seja redirecionado a página inicial | Deixa o ícone não clicavel ou fazer o redirecionamento para página inicial ao clicar |
| 9 | Ao executar uma mudança de senha não existe uma confirmação do desejo de alterá-la | Página 'Alterar Senha'| Alta | Prevenção de erros | Impossibilidade de uso, pois a senha pode ser alterada para uma a qual não foi gravada pelo usuário | Colocar modal de confirmação de alteração de senha |
| 10 | Ao clicar em cancelar na página de 'Alterar Senha' o usuário não é redirecionado para a página inicial | Página 'Alterar Senha' | Baixa | Consistência e padronização | Baixo impacto de uso |  Redirecionar usuário para a página inicial ao clicar em cancelar |
| 11 | Ao alterar a senha não há como visualizar a senha nova que foi digitada, impossibilitando assim o usuário confirmar se as senhas foram digitadas corretamente | Página 'Alterar Senha' | Média | Prevenção de erros  | Alterar a senha para uma não esperada | Adicionar botão que retire a máscara da senha permitindo assim aque o usuário confirme que as senhas digitadas |
| 12 | O site entra em manutenção a meia noite todos os dias | Em todo o site | Alta | Flexibilidade e eficiência de uso | Impossibilita o uso do site após a meia noite | Tornar o site disponível 24 horas, 7 dias por semana |

## Históricos de versões

|    Data    | Versão |             Descrição             |          Autor(es)           |
| :--------: | :----: | :-------------------------------: | :--------------------------: |
| 10/09/2020 |  0.1   | Criação do boilerplate do arquivo | Hugo Sobral e Leonardo Gomes |
| 13/09/2020 |  1.0   | Avaliação heurística | João Lucas Zarbiélli |

