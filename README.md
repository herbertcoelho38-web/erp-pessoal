# ERP de Pessoas · Danlex

Controle de presença, batidas de ponto, absenteísmo, turnover, banco de horas, medidas disciplinares, férias e auditoria.

- Front-end: página única (`index.html`), publicada no Vercel.
- Banco e login: Supabase (tabela `public.erp_docs` com RLS por perfil: Master, Editor, Gestor de base).
- Login: e-mail e senha (Supabase Auth). Perfis e bases são definidos pelo Master na tela Usuários.
- Migração: no ERP antigo, Master usa "Backup completo (arquivo)"; aqui, "Restaurar backup".
