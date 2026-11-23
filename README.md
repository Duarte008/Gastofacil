# men$al — PWA

PWA mobile-first de controlo financeiro pessoal.

## Funcionalidades
- Dashboard de saldo, receitas e despesas
- Registo de gasto em poucos toques
- Gasto rápido por texto
- Receitas
- Categorias personalizadas
- Contas/carteiras e saldos calculados pelos lançamentos
- Cartões de crédito com fatura separada
- Orçamento mensal e alertas visuais
- Despesas recorrentes mensais com geração automática
- Histórico, edição e exclusão
- Pesquisa
- Análises por categoria e previsão mensal
- Assistente financeiro local baseado nos dados do dispositivo
- Entrada por voz quando suportada pelo navegador
- Captura de recibo preparada para OCR
- Exportação CSV e backup JSON
- Relatório imprimível / PDF através do diálogo de impressão
- Modo escuro
- Service Worker + manifest para instalação como PWA
- Dados persistentes em localStorage

## Teste rápido
1. Abra `index.html` num servidor web.
2. No telemóvel, use HTTPS para permitir a instalação PWA e recursos de voz quando suportados.
3. Registe gastos e feche/reabra o navegador: os dados permanecem no dispositivo.

## Produção
A versão atual é local-first. Para sincronização multi-dispositivo, autenticação, backup cloud, OCR real e IA avançada, ligue um backend (por exemplo, Supabase) mantendo a mesma camada de interface.

