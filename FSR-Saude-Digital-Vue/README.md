# FSR Saúde Digital — 11º RC Mec

MVP acadêmico da **Plataforma Digital Integrada de Agendamento e Atendimento em Saúde Militar**, evoluído a partir dos trabalhos do Projeto Integrador I.

## Tecnologias
- HTML5 semântico
- CSS3 responsivo
- Vue.js 3 (framework front-end, carregado localmente)
- JavaScript ES2022
- Visual Studio Code
- Git/GitHub

## Estrutura
- `index.html` — estrutura semântica e template da interface
- `app.js` — estado reativo e regras de interação com Vue.js
- `styles.css` — estilos e responsividade
- `vue.global.js` — biblioteca Vue 3 local

## Execução
Abra `index.html` em um navegador moderno. Para usar servidor local:

```bash
python3 -m http.server 8000
```

Depois acesse `http://localhost:8000`.

## Funcionalidades demonstrativas
- Dashboard
- Agendamento de consultas
- Meus atendimentos e cancelamento
- Histórico
- Dependentes
- Serviços
- Unidades
- Notificações
- Suporte/FAQ
- Perfil
- Requisitos do projeto
- Informações e limitações da solução

## Decisões técnicas
Foi adotado o Vue.js 3 para gerenciamento reativo do estado, renderização condicional, listas dinâmicas, formulários com `v-model` e tratamento de eventos. A organização do HTML privilegia elementos semânticos e controles com rótulos associados. O CSS utiliza Grid, Flexbox, media queries e unidades relativas para adaptação a computador, tablet e celular.

## Limitações
Esta é uma implementação acadêmica/MVP. Não existe integração real com o 11º RC Mec, Formação Sanitária Regimental, FUSEX, prontuário eletrônico, banco institucional ou autenticação oficial. Os dados exibidos são demonstrativos.
