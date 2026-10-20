# Orbit IA — MVP v0.1

Agência de tráfego pago com IA, com evolução planejada para uma plataforma SaaS.

## Acesse
- `index.html`: site comercial
- `painel.html`: painel de demonstração

Site público após configurar GitHub Pages: `https://daeg0n.github.io/orbit/`
Painel após configurar GitHub Pages: `https://daeg0n.github.io/orbit/painel.html`

## O que funciona
- Página comercial responsiva com serviços, planos e formulário que prepara/copia uma solicitação (não envia mensagens)
- Painel de demonstração
- Cadastro e exclusão de clientes
- Registro e exclusão de campanhas **planejadas**
- Pipeline comercial com cadastro e exclusão
- Gerador de plano de campanha baseado em regras e briefing
- Salvamento local usando `localStorage`

## Limites e transparência
Não há login, backend, banco de dados remoto, geração real via LLM, integração com Meta Ads/Google Ads, publicação de campanhas ou envio de formulário para servidor. Dados e valores de exemplo não representam campanhas reais. **Não insira dados pessoais ou sigilosos** na demo; os dados ficam acessíveis a usuários do mesmo perfil do navegador.

## Publicação via GitHub Pages
Abra **Settings > Pages > Build and deployment > Deploy from a branch**, selecione `main` e `/ (root)`, depois salve. Confirme que o site entrou no ar. Essa configuração não é alterada pelo MVP.

## Próxima fase
1. Supabase Auth e PostgreSQL com RLS por organização
2. Ambiente administrativo autenticado e backend para formulários
3. Integração opcional com LLM via servidor, mantendo chaves fora do cliente
4. Integrações oficiais com Meta Marketing API e Google Ads API, observando permissões
5. Relatórios reais com controle de acesso, auditoria e consentimento
6. Pipeline de vendas e aquisição dos primeiros clientes

> MVP demonstrativo. Não deve ser tratado como sistema de produção.
