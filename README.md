# Agende-Form — Cadastro de Profissionais

Formulário de cadastro de profissionais de saúde para a **Stimulus Clínica Multidisciplinar**, integrado à plataforma **Agende.ee**.

## Como usar

1. Abra `index.html` e altere o endpoint do FormSubmit:
   ```
   const FORM_ENDPOINT = 'https://formsubmit.co/ajax/SEUEMAIL@stimulus.com.br';
   ```
   Substitua `SEUEMAIL@stimulus.com.br` pelo e-mail que receberá os cadastros.

2. Na **primeira submissão**, o FormSubmit enviará um e-mail de confirmação — clique no link para ativar o endpoint.

## Deploy no GitHub Pages

O site é publicado automaticamente via **GitHub Pages** na branch `main`.
URL: `https://tonyroberto.github.io/agende-form/`
