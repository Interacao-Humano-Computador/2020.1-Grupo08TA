# Avaliação heurística

## Objetivo

Identificar problemas de usabilidade associados ao Site SEI

## Escopo da Avaliação

A avaliação de heurísticas sera aplicada em todo o site, para assim termos uma visão completa dos problemas de usabilidade que envolvem o SEI.

## Método

Serão usadas 10 heuristicas de Nielsen sendo elas:
* Visibilidade do estado do sistema
* Correspondência entre o sistema e o mundo real
* Controle e liberdade do usuário
* Consistência e padronização
* Prevenção de erros
* Reconhecimento em vez de memorização
* Flexibilidade e eficiência de uso
* Estética e Design minimalistas
* Recuperação de erros
* Ajuda e Documentação 

Após a análise levando em conta essas heurísticas será gerado uma tabela com as seguintes informações:
* problemas encontrados
* local onde ocorre;
* descrição do problema;
* diretriz(es) violada(s);
* severidade do problema;
* sugestões de solução.

## Resultado

|Nº | Descrição | Local | Gravidade | Diretriz | Frequência | Impacto | Persistencia | Solução |
|:- | :-------- |:----- | :-------- | :--------| :----------| :------ | :----------- | :------ |
| 1 | Usuários externos que desejam fazer login não possuem opção de cadastro| Página de Login | Alta | ? | Comum | Impossibilidade de uso | ? | Criação de um botão de cadastro para usuários externos |
| 2 |Não há qualquer botão ou modal que ajude a proceder com o login| Página de Login | Alta | Ajuda e Documentação | Comum | Atrapalha o uso uma vez que é necessário acessar outro site para ter acesso a documentação | Em todo o site | Trazer documentação para o próprio site|
||||||||||



## Históricos de versões

|    Data    | Versão |             Descrição             |          Autor(es)           |
| :--------: | :----: | :-------------------------------: | :--------------------------: |
| 10/09/2020 |  1.0   | Criação do boilerplate do arquivo | Hugo Sobral e Leonardo Gomes |
| 13/09/2020 |  2.0   | Avaliação heurística | João Lucas Zarbiélli |