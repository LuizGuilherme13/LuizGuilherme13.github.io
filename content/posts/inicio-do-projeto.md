+++
date = '2026-08-25T11:43:46-03:00'
title = 'Início do Projeto'
summary = 'Um projeto para aplicar tudo que eu for aprendendo sobre programação e engenharia de software.'
author = 'Luiz'

tags = ['projeto', 'estudos']
categories = ['Projeto']

ShowToc = true
TocOpen = false
ShowReadingTime = true
ShowBreadCrumbs = true
ShowPostNavLinks = true
+++

## Motivação

Grande parte do meu aprendizado em programação acontece estudando conceitos isoladamente, lendo documentação, fazendo exercícios ou criando pequenos projetos para praticar algo específico.

Isso funciona, mas existe uma parte importante do desenvolvimento de software que é difícil de aprender dessa forma: entender como diferentes conceitos se comportam juntos dentro de um sistema real.

Autenticação, banco de dados, cache, concorrência, deploy, segurança, observabilidade e performance não existem isoladamente. Em algum momento, todas essas partes precisam coexistir, interagir e, eventualmente, apresentar problemas.

Por isso decidi criar um projeto que vai me acompanhar durante minha evolução como desenvolvedor.

## Os princípios do projeto

1. Começar pela solução mais simples possível.

2. Não adicionar tecnologia sem um problema concreto.

3. Toda mudança arquitetural deve ter uma justificativa.

4. Problemas devem ser reproduzíveis antes de serem corrigidos.

5. Mudanças importantes devem ser medidas.

6. Produção faz parte do ambiente de aprendizado.

7. O sistema pode quebrar. O objetivo é entender por que quebrou.

8. Complexidade é introduzida somente quando a complexidade anterior não resolve mais o problema.

## O Projeto

O projeto será uma aplicação web de troca de mensagens, inspirada em plataformas como o Discord. Inicialmente, quero focar apenas no básico: usuários, autenticação, canais e mensagens. Com o tempo, o sistema poderá evoluir para suportar outras funcionalidades, como:

- envio e compartilhamento de imagens;
- arquivos;
- presença de usuários;
- áudio;
- chamadas de voz;
- chamadas de vídeo;
- compartilhamento de tela.

Essas funcionalidades, porém, não representam uma promessa ou um roadmap rígido.

## A stack inicial

Para começar, escolhi uma stack bem simples:

- Go no backend;
- HTML, CSS e JavaScript no frontend;
- SQLite como banco de dados.

A ideia é usar essas tecnologias até onde fizer sentido.

Não quero começar adicionando frameworks, bancos de dados distribuídos, caches ou qualquer outra tecnologia apenas porque são ferramentas comuns em sistemas maiores. Quero primeiro encontrar os problemas e entender por que uma determinada solução seria necessária.

Quero colocar esse sistema no ar e acompanhar sua evolução. Ver problemas acontecendo, investigar as causas e buscar soluções.

Talvez o sistema fique lento. Talvez apareçam problemas de concorrência. Talvez alguma decisão que parecia boa no início deixe de fazer sentido.

E tudo bem.

A ideia é justamente aprender com isso.

Este projeto não tem como objetivo ter uma arquitetura perfeita desde o começo. A intenção é começar simples e deixar o sistema evoluir conforme surgirem novas necessidades e conforme eu evoluir como desenvolvedor.
