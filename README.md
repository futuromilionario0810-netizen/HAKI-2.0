# HAKI 2.0 — Evolução & Produtividade

Aplicativo PWA mobile-first para evolução pessoal e prospecção diária.

## Publicação
Envie todos os arquivos e a pasta `icons/` para a raiz do repositório GitHub conectado ao Vercel. O deploy é automático.

## Funcionalidades
- Duas abas: Evolução e Produtividade.
- Atributos personalizados com regras de +1 e -1; edição cria nova versão a partir do dia da alteração.
- Canais de prospecção permanentes; contagem diária reinicia naturalmente a cada data, mantendo histórico.
- Meta diária configurável (padrão: 100), classificação do dia, reuniões agendadas, recorde pessoal, média dos últimos 7 dias e total mensal.
- Calendário de produtividade e histórico.
- Backup JSON.
- PWA instalável e funcionamento offline após o primeiro carregamento.

## Dados e privacidade
Os dados ficam no armazenamento local do navegador/aparelho (`localStorage`). Não existe sincronização automática entre dispositivos. Exporte backups regularmente antes de limpar os dados do navegador ou trocar de aparelho.

## Atualização
A versão do service worker foi atualizada para `haki-app-v2` para solicitar os novos arquivos após publicação.
