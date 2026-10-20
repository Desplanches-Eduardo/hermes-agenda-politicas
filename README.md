# hermes-agenda-politicas

![HTML5](https://img.shields.io/badge/HTML5-6366f1?style=flat-square&labelColor=1e293b&logo=html5&logoColor=white) ![GitHub Pages](https://img.shields.io/badge/GitHub_Pages-6366f1?style=flat-square&labelColor=1e293b&logo=githubpages&logoColor=white)

Páginas públicas do Hermes Agenda, o assistente pessoal que eu uso no meu computador: a página de
informações do app, a Política de Privacidade e os Termos de Serviço.

O repositório existe por exigência, não por vontade: o Google só libera o acesso às APIs de uma
conta que usa escopos sensíveis (Gmail, Drive, Agenda e Planilhas) se o app tiver política de
privacidade e termos de uso publicados em URL pública. É a URL que eu informo no cadastro do
projeto no Google Cloud.

Está no ar em https://desplanches-eduardo.github.io/hermes-agenda-politicas/.

## Como mexer

HTML puro, um arquivo por página — `index.html`, `privacidade.html` e `termos.html` — com o CSS
dentro do `<style>` de cada uma e sem build. Para conferir, abra o arquivo no navegador. Para
publicar, commit e push: o GitHub Pages serve a branch `main` direto, então o que estiver
commitado é o que está no ar.

## Decisões

As páginas não têm script, analytics nem rastreador, e a política diz isso com essas palavras. O
motivo é o app ser de um usuário só, rodando na máquina do próprio titular da conta: não existe
dado de terceiro para coletar, e prometer tratamento de dado que não passa por aqui seria
documento enfeitado.

## O que não tem

Não tem formulário, blog nem área logada — as três páginas são texto e link. A data de
atualização no rodapé é escrita à mão em cada arquivo, então mudar um texto sem mexer nela deixa
a página se dizendo mais velha do que é.
