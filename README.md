<div align="center">

# Luiz Fernando

**Engenheiro de Software Backend · Python / FastAPI**

Construo sistemas multiempresa para operações industriais — conformidade trabalhista,<br>
controle de materiais e gestão de pessoas em campo — do modelo de dados ao deploy.

[Instagram](https://instagram.com/luuiz.dev) · Belo Horizonte, MG · Engenharia de Software @ UniCesumar

</div>

---

## Resumo

Desenvolvo software para empresas prestadoras de serviço do setor industrial, onde erro de sistema
vira passivo trabalhista ou material parado em obra. Meu foco é backend: APIs bem modeladas,
isolamento de dados entre empresas clientes, trilhas de auditoria e integração com as obrigações
legais brasileiras (Portaria MTP 671/2021, eSocial, LGPD).

Os sistemas abaixo foram construídos para clientes reais e estão em uso ou em homologação.

## Trabalhos selecionados

### .GRAMO — Ponto eletrônico corporativo (REP-P)
[`repositório`](https://github.com/luizfernandoantonio345-webs/.Gramo)

Registro de ponto para trabalhadores de campo distribuídos em múltiplas obras, em conformidade
com a Portaria MTP nº 671/2021.

- Registro com geolocalização por obra e operação offline, sincronizando ao reconectar
- Central de RH com 2FA, fila de exceções, assinatura digital de espelho de ponto e auditoria
- Geração dos arquivos legais **AFD** e **AEJ** e integração com folha / eSocial
- Arquitetura em três camadas de acesso — colaborador, empresa cliente e operador da plataforma —
  com o operador **sem acesso a dados operacionais** das empresas
- Em processo de registro como programa de computador no INPI

### GWI — Gestão de Materiais e Almoxarifado
[`backend`](https://github.com/luizfernandoantonio345-webs/gwi-materiais-backend) · [`frontend`](https://github.com/luizfernandoantonio345-webs/gwi-frontend) · [`demo`](https://gwi-frontend.vercel.app)

Módulo da plataforma GWI que substitui um fluxo manual de almoxarifado de obra.

- Entrada de estoque, controle de consumíveis e posição de estoque em tempo real
- Cálculo de necessidade de compra e fluxo de compras com notificações
- API REST em FastAPI · PostgreSQL · frontend em React

### Pedido digital com Pix — rede de açaiterias
[`repositório`](https://github.com/luizfernandoantonio345-webs/acai-da-patricia) · [`demo`](https://a-a-da-patr-cia.vercel.app)

Cliente pede pelo QR code da mesa, paga via Pix e o pedido chega na cozinha sem intermediário.

- Painel de cozinha em tempo real via **WebSocket**
- Estrutura multiloja (multi-tenant) para expansão da rede
- FastAPI · PostgreSQL · TypeScript

### Automação CAD — tubulação industrial
[`repositório`](https://github.com/luizfernandoantonio345-webs/Automacao-CAD)

Automação de tarefas repetitivas em projetos de piping industrial, em Python.

## Em desenvolvimento

**WorkFlow RH** — SaaS B2B de gestão de pessoas para terceirizadas industriais: coleta de dados,
distribuição de documentos, jornada e conformidade (eSocial S-1.3, NR-1 riscos psicossociais, LGPD).
Arquitetura de segurança em camadas: Argon2id, refresh tokens rotativos, RBAC com isolamento de
tenant na camada de ORM, criptografia de campos pessoais e log de auditoria imutável.
<sub>FastAPI · PostgreSQL · Redis · Celery · React · React Native</sub>

**JARVIS** — assistente de IA executado localmente, com arquitetura multiagente
(Planner / Executor / Critic / Memory), inferência via Ollama e um módulo de segurança com
análise estática (SAST), threat intelligence e mapeamento MITRE ATT&CK.
<sub>FastAPI · React · TypeScript · Ollama</sub>

## Como eu trabalho

- **Modelagem antes de código.** O esquema de dados e as fronteiras entre tenants são decididos primeiro;
  o resto do sistema segue deles.
- **Segurança é requisito, não fase.** Autenticação, autorização e auditoria entram na primeira sprint.
- **A regra de negócio vem da lei.** Em sistemas trabalhistas, a portaria é a especificação.
- **Entrega completa.** Documentação técnica, testes automatizados, containers e pipeline de deploy.

## Stack

| | |
|---|---|
| **Linguagens** | Python · TypeScript · SQL |
| **Backend** | FastAPI · SQLAlchemy · Celery · WebSockets · APIs REST |
| **Dados** | PostgreSQL · Redis |
| **Segurança** | JWT com rotação de refresh token · RBAC · 2FA · Argon2id · multi-tenancy |
| **Frontend** | React · React Native |
| **Infra** | Docker · GitHub Actions · Vercel |

## Estudando agora

Segurança de aplicações (PortSwigger Web Security Academy), estruturas de dados e algoritmos, e inglês técnico.
