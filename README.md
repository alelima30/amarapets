# Amara Pet's — site

Consultório veterinário, banho e tosa e pet shop em Itu/SP.
Site de página única, sem build e sem dependências: um único `index.html`
com fotos, logotipo, fontes e animações já embutidos. Funciona offline.

## Publicar no GitHub Pages

1. Crie um repositório no GitHub (ex. `amara-pets`).
2. Envie o conteúdo desta pasta (`index.html`) para a branch `main`.
3. No repositório: **Settings → Pages → Source: Deploy from a branch**,
   branch `main`, pasta `/ (root)`. Salve.
4. Em alguns minutos o site fica disponível em
   `https://SEU-USUARIO.github.io/amara-pets/`.

Pelo terminal:

    git init
    git add .
    git commit -m "Site Amara Pet's"
    git branch -M main
    git remote add origin https://github.com/SEU-USUARIO/amara-pets.git
    git push -u origin main

## Domínio próprio

Para usar um domínio (ex. `amarapets.com.br`), aponte o DNS para o GitHub Pages
e informe o domínio em **Settings → Pages → Custom domain**. O GitHub cria o
arquivo `CNAME` automaticamente.

## O que ainda falta preencher

- **Horários de funcionamento** — hoje o rodapé mostra "A confirmar".
- **Depoimentos** — os três textos são rascunhos e as assinaturas estão como
  "Nome do tutor". Substitua pelas palavras reais dos clientes antes de publicar.
- **Logotipo** — está em JPEG com fundo branco; um PNG com fundo transparente
  deixaria o cabeçalho e o rodapé mais limpos.

## Como editar

Abra o `index.html` em qualquer editor de texto e use a busca (Ctrl+F) para
localizar o trecho que quer trocar. Os textos estão em português, na ordem em
que aparecem na página.

Contatos usados no site:

- WhatsApp: `https://wa.me/5515998102654`
- Instagram: `https://instagram.com/amarapetcajuru`
- Endereço: Rua Bauru, 58 — Cidade Nova, Itu/SP, 13308-452
- Dra. Celia Amara — CRMV 67673
