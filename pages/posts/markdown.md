---
title: Comandos GIT Utilizados nesse projeto.
date: 2023/07/29
description: Entendendo os principais comandos e Git Flow.
tag: Web Development
author: Luan Araujo
---

# Comando Git Essenciais & Git Flow

## Principais Comandos Git:
###

1. `git init`: Inicializa um novo repositório Git no diretório atual.

2. `git clone [URL]`: Clona um repositório existente para o seu computador.

3. `git add [arquivo]`: Adiciona as alterações do arquivo para a área de preparação (staging).

4. `git commit -m "mensagem"`: Grava as alterações adicionadas na área de preparação no histórico do repositório.

5. `git push`: Envia as alterações do repositório local para o repositório remoto.

6. `git pull`: Obtém as alterações do repositório remoto para o repositório local e as mescla com o seu código.

## Git Flow

O Git Flow é uma metodologia de controle de versão que fornece um fluxo de trabalho estruturado para gerenciar branches e releases em projetos de software. Ele define as branches `main` e `develop` como pilares do desenvolvimento, e estabelece processos claros para novas funcionalidades, correções de bugs e lançamentos.

Principais Branches do Git Flow:

- `main`: Contém o código estável, pronto para ser implantado em produção.
- `develop`: Branch de desenvolvimento onde novas funcionalidades são integradas e testadas.

Branches Adicionais:

- `feature`: Para o desenvolvimento de novas funcionalidades.
- `hotfix`: Para correções rápidas de bugs em produção.
- `release`: Para preparar e testar lançamentos.

O Git Flow promove uma colaboração organizada e mantém o código estável ao longo do ciclo de desenvolvimento. É uma abordagem popular entre equipes de desenvolvimento que valorizam uma estratégia sólida de controle de versão.

## Links

- [Next.js](https://nextjs.org)
- [Nextra](https://nextra.vercel.app/)
- [Git Docs](https://git-scm.com/docs/git/pt_BR)