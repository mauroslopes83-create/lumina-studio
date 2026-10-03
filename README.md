# Lumina Studio — instalação

O Studio é um painel web administrativo para o projeto Lumina. Está pré-configurado para o projeto Supabase atual e usa a publishable key, que pode ser exposta num cliente web.

## Abrir

O Studio deve ser servido através de HTTPS (por exemplo, GitHub Pages ou outro hosting estático). Não é necessário servidor próprio.

## Entrar

1. Abrir o Studio.
2. Clicar em **Entrar como gestor**.
3. Usar o email e palavra-passe criados no Supabase Authentication.

## Publicar

Editar conteúdo → guardar → abrir **Publicar** → **Publicar para todas as instalações**.

A publicação altera o catálogo `production` no Supabase. As aplicações sincronizam o catálogo remoto; conteúdo suportado não exige novo APK.
