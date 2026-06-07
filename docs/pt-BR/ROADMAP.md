# Roadmap

Este roadmap organiza o desenvolvimento do OpenSource for Humans em fases, épicos e tarefas menores para distribuição entre contribuidores no GitHub.

Ele deve ser usado como base para criar milestones, issues, discussions, RFCs e projetos no GitHub. O objetivo não é apenas listar funcionalidades, mas orientar uma comunidade open source a construir o produto sem violar a missão, a privacidade, a segurança, a governança e as políticas de dados do projeto.

## Regra central

Pessoas que precisam de ajuda nunca serão o produto.

No estágio inicial, a plataforma não deve armazenar do lado do servidor dados pessoais de pessoas que buscam ajuda ou visitantes em geral. Se estatísticas forem necessárias, elas devem ser anonimizadas e agregadas antes do armazenamento.

## Como usar este roadmap no GitHub

## Milestones

Cada fase deste documento deve virar uma milestone:

- `phase-0-foundation`
- `phase-1-local-mvp`
- `phase-2-public-launch`
- `phase-3-organizations`
- `phase-4-safe-ai`
- `phase-5-local-chapters`
- `phase-6-ecosystem`

## Épicos

Cada seção marcada como épico pode virar uma issue principal com checklist ou uma discussion fixada.

Formato sugerido:

`[Epic] Phase 1 - Service search and listing`

## Issues

Cada tarefa marcada como issue candidata deve virar uma issue pequena, com escopo claro e critério de aceite.

Formato sugerido:

`[area/frontend] Build mobile search form`

## Labels sugeridas

Tipo:

- `type/feature`
- `type/bug`
- `type/docs`
- `type/research`
- `type/design`
- `type/data`
- `type/security`
- `type/privacy`
- `type/governance`
- `type/rfc`

Área:

- `area/frontend`
- `area/backend`
- `area/admin`
- `area/docs`
- `area/product`
- `area/data-model`
- `area/data-quality`
- `area/accessibility`
- `area/i18n`
- `area/search`
- `area/devops`
- `area/security`
- `area/privacy`
- `area/ai`
- `area/governance`
- `area/community`
- `area/local-chapters`
- `area/funding`

Prioridade:

- `priority/p0-critical`
- `priority/p1-high`
- `priority/p2-medium`
- `priority/p3-low`

Esforço:

- `effort/xs`
- `effort/s`
- `effort/m`
- `effort/l`
- `effort/xl`

Contribuição:

- `good-first-issue`
- `help-wanted`
- `needs-maintainer`
- `needs-data-review`
- `needs-legal-review`
- `needs-design-review`
- `needs-security-review`
- `blocked`

## Definição de pronto

Uma issue está pronta para ser trabalhada quando tiver:

- objetivo claro;
- contexto suficiente;
- arquivos ou áreas afetadas;
- critérios de aceite;
- riscos de privacidade, segurança ou impacto social;
- dependências conhecidas;
- labels corretas;
- tamanho pequeno o suficiente para uma pessoa contribuir.

## Definição de concluído

Uma issue só deve ser considerada concluída quando:

- os critérios de aceite forem cumpridos;
- testes ou validações manuais forem documentados;
- documentação relevante for atualizada;
- nenhum dado pessoal desnecessário for introduzido;
- regras de LGPD + GDPR/RGPD forem respeitadas;
- fluxos sensíveis tiverem revisão humana quando necessário;
- mudanças de interface forem verificadas em mobile;
- mudanças de dados tiverem fonte e status de verificação;
- mudanças críticas tiverem revisão de mantenedor.

## Papéis de contribuição

## Contribuidor técnico

Trabalha em frontend, backend, infraestrutura, testes, segurança, acessibilidade, automações e ferramentas internas.

## Contribuidor de dados

Mapeia serviços, revisa fontes, identifica duplicados, confirma status, melhora taxonomia e reporta inconsistências.

## Contribuidor de design

Cria fluxos, protótipos, textos de interface, acessibilidade, mobile-first e experiências simples para pessoas com baixo letramento digital.

## Contribuidor de documentação

Melhora guias, políticas, traduções, exemplos, templates, decisões e materiais para capítulos locais.

## Mantenedor técnico

Revisa arquitetura, segurança, qualidade de código, deploy, testes e decisões técnicas.

## Mantenedor de dados

Revisa dados publicados, fontes, denúncias, alterações e filas de verificação.

## Conselho comunitário

Decide mudanças críticas de missão, privacidade, financiamento, IA sensível, abertura de dados e parcerias estratégicas.

## Princípios não negociáveis

Toda fase do roadmap deve respeitar:

- busca de ajuda sem login obrigatório;
- nenhuma cobrança para quem busca ajuda;
- nenhuma venda de dados pessoais;
- nenhuma prioridade paga em resultados essenciais;
- sem armazenamento server-side de dados pessoais de usuários no estágio inicial;
- estatísticas apenas anonimizadas e agregadas;
- dados sensíveis evitados por padrão;
- localização aproximada sempre que possível;
- LGPD brasileira e GDPR/RGPD europeu aplicados juntos, prevalecendo a regra mais protetiva;
- dados de serviços com fonte, status e última verificação;
- sugestões da comunidade, scraping ou IA sempre revisados por humanos antes de publicação;
- IA como apoio, não autoridade final;
- linguagem probabilística em elegibilidade;
- acessibilidade e mobile-first;
- transparência em decisões relevantes.

## Fase 0: Fundação

Milestone: `phase-0-foundation`

Objetivo: preparar o projeto para receber contribuidores com segurança, clareza, governança e escopo inicial.

Resultado esperado: uma comunidade consegue abrir issues, entender a missão, contribuir sem expor pessoas vulneráveis e trabalhar em um MVP local com regras claras.

Critérios de saída:

- documentação principal publicada em inglês e português;
- licença definida;
- templates de issue e pull request criados;
- labels e milestones configuradas;
- cidade inicial escolhida;
- categorias iniciais escolhidas;
- modelo de dados inicial aprovado;
- política de privacidade operacional aplicada ao MVP;
- processo de revisão de dados definido;
- backlog inicial criado no GitHub.

## Épico 0.1: Organização do repositório

Objetivo: deixar o repositório compreensível para novos contribuidores.

Issues candidatas:

- Criar estrutura inicial de pastas do projeto.
- Criar `LICENSE`.
- Criar `CODEOWNERS`.
- Criar `.github/ISSUE_TEMPLATE/bug_report.md`.
- Criar `.github/ISSUE_TEMPLATE/feature_request.md`.
- Criar `.github/ISSUE_TEMPLATE/data_submission.md`.
- Criar `.github/ISSUE_TEMPLATE/data_correction.md`.
- Criar `.github/ISSUE_TEMPLATE/rfc.md`.
- Criar `.github/PULL_REQUEST_TEMPLATE.md`.
- Criar `SECURITY.md` com canal privado definitivo.
- Criar arquivo `MAINTAINERS.md`.
- Criar arquivo `DECISIONS.md` ou pasta `docs/decisions`.

Critérios de aceite:

- novos contribuidores conseguem entender onde abrir cada tipo de issue;
- PRs pedem explicitamente avaliação de privacidade, segurança e impacto social;
- issues de dados pedem fonte e data de verificação;
- nenhuma instrução incentiva publicação de dados pessoais.

Labels sugeridas: `type/docs`, `area/community`, `priority/p1-high`, `good-first-issue`.

## Épico 0.2: Governança e processo comunitário

Objetivo: transformar a governança documentada em processo operacional.

Issues candidatas:

- Definir processo para aceitar novos mantenedores.
- Definir processo para remover permissões em caso de violação.
- Criar modelo de RFC.
- Criar modelo de ata pública para decisões relevantes.
- Criar fluxo para decisões que exigem conselho comunitário.
- Criar lista inicial de áreas de responsabilidade.
- Criar guia de mediação de conflitos.
- Criar política de tradução e sincronização entre `docs/en` e `docs/pt-BR`.
- Definir idioma canônico das decisões.
- Criar processo para declarar conflito de interesse.

Critérios de aceite:

- mudanças críticas têm caminho de aprovação claro;
- decisões sensíveis não dependem de uma única pessoa;
- capítulos locais sabem o que podem adaptar e o que não podem enfraquecer.

Labels sugeridas: `type/governance`, `area/community`, `priority/p1-high`.

## Épico 0.3: Licença e proteção contra captura

Objetivo: escolher licenças compatíveis com open source, dados abertos e proteção da missão.

Issues candidatas:

- Pesquisar licença para código.
- Pesquisar licença para documentação.
- Pesquisar licença para schemas e taxonomia.
- Pesquisar licença para dados institucionais publicados.
- Criar RFC de licenciamento.
- Revisar riscos de captura privada do trabalho comunitário.
- Documentar limites para uso comercial aceitável.

Critérios de aceite:

- licença do código está definida;
- licença da documentação está definida;
- política de dados abertos não permite publicação de dados pessoais;
- decisão está documentada e revisável.

Labels sugeridas: `type/rfc`, `type/governance`, `area/funding`, `needs-legal-review`.

## Épico 0.4: Escopo inicial do MVP

Objetivo: impedir que o projeto tente construir uma plataforma global antes de validar valor local.

Decisão recomendada:

- cidade inicial: São Paulo;
- categorias iniciais: alimentação, abrigo, documentação, saúde mental, emprego e imigrantes;
- meta inicial: 200 serviços reais;
- produto inicial: web app mobile-first com busca, lista e página de serviço;
- usuários iniciais: pessoas buscando ajuda básica e intermediários que ajudam essas pessoas.

Issues candidatas:

- Confirmar cidade inicial.
- Confirmar categorias iniciais.
- Definir critérios para incluir ou excluir serviços.
- Criar taxonomia inicial de categorias.
- Criar lista de fontes públicas prioritárias.
- Criar plano de entrevistas com usuários.
- Criar plano de entrevistas com organizações.
- Criar métrica principal do MVP.

Critérios de aceite:

- há um escopo pequeno e executável;
- categorias têm definições claras;
- MVP não inclui chat, doações financeiras, IA autônoma ou app mobile nativo;
- métrica principal está definida.

Labels sugeridas: `type/research`, `area/product`, `area/data-quality`, `priority/p1-high`.

## Épico 0.5: Privacidade operacional do MVP

Objetivo: aplicar desde o início a regra de não armazenar dados pessoais de usuários no servidor.

Issues candidatas:

- Criar checklist de revisão de privacidade para PRs.
- Criar matriz de dados coletados, finalidade, base legal e retenção.
- Definir política de logs sem dados identificáveis.
- Definir regra para truncar, remover ou anonimizar IPs.
- Definir configuração de analytics apenas agregada.
- Definir proibição de session replay.
- Definir proibição de histórico individual de busca no servidor.
- Definir proibição de respostas individuais de elegibilidade no servidor.
- Definir exceções técnicas permitidas e prazo máximo de retenção.
- Criar processo para avaliação de impacto de proteção de dados.

Critérios de aceite:

- qualquer issue técnica sabe o que não pode armazenar;
- analytics só permite métricas agregadas;
- logs não mantêm identificadores de usuários;
- exceções exigem justificativa e revisão.

Labels sugeridas: `type/privacy`, `area/privacy`, `area/security`, `priority/p0-critical`.

## Fase 1: MVP local

Milestone: `phase-1-local-mvp`

Objetivo: lançar uma primeira versão funcional, local, simples e confiável, com busca anônima e dados verificados.

Resultado esperado: uma pessoa consegue entrar no site pelo celular, buscar ajuda por necessidade e cidade, abrir um serviço, entender como pedir ajuda e compartilhar a informação.

Critérios de saída:

- web app mobile-first publicado em ambiente de teste;
- catálogo com 200 serviços reais;
- busca por texto, categoria e cidade;
- página de serviço com fonte e última verificação;
- formulário para sugerir serviço;
- formulário para reportar erro;
- painel administrativo mínimo;
- nenhum dado pessoal de usuários finais armazenado no servidor;
- métricas agregadas básicas disponíveis;
- documentação de operação do MVP.

## Épico 1.1: Modelo de dados inicial

Objetivo: criar o modelo mínimo para organizações, serviços, locais, contatos, categorias, reports e verificação.

Entidades iniciais:

- `Organization`
- `Service`
- `Location`
- `Contact`
- `Category`
- `EligibilityNote`
- `UserReport`
- `VerificationLog`
- `DataSource`

Issues candidatas:

- Definir schema de `Organization`.
- Definir schema de `Service`.
- Definir schema de `Location`.
- Definir schema de `Contact`.
- Definir schema de `Category`.
- Definir schema de `UserReport`.
- Definir schema de `VerificationLog`.
- Definir enum de status do serviço.
- Definir enum de níveis de confiança.
- Definir campos obrigatórios para publicação.
- Definir campos proibidos.
- Criar seed de categorias iniciais.
- Criar validações para contatos oficiais.
- Criar documentação do modelo de dados.

Critérios de aceite:

- modelo permite busca e publicação sem dados pessoais de usuários finais;
- cada serviço tem fonte, status e última verificação;
- dados de pessoas atendidas não aparecem no schema público;
- modelo é compatível com evolução futura para HSDS/Open Referral.

Labels sugeridas: `area/data-model`, `area/backend`, `type/feature`, `priority/p1-high`.

## Épico 1.2: Backend e API pública mínima

Objetivo: criar API para leitura de serviços e recebimento seguro de sugestões e reports.

Endpoints mínimos:

- `GET /categories`
- `GET /services`
- `GET /services/:id`
- `GET /organizations/:id`
- `POST /service-suggestions`
- `POST /reports`
- `GET /health`

Issues candidatas:

- Criar estrutura inicial do backend.
- Criar conexão com banco.
- Criar migrations.
- Criar endpoint de categorias.
- Criar endpoint de listagem de serviços.
- Criar endpoint de detalhe de serviço.
- Criar filtros por categoria e cidade.
- Criar busca textual simples.
- Criar endpoint de sugestão de serviço.
- Criar endpoint de reportar erro.
- Adicionar rate limit em endpoints públicos.
- Adicionar validação de entrada.
- Adicionar sanitização de links e textos.
- Criar testes de API.
- Criar documentação OpenAPI.

Critérios de aceite:

- API não cria perfil de usuário final;
- endpoints públicos não exigem login;
- reports e sugestões não publicam automaticamente;
- logs não guardam dados identificáveis desnecessários;
- testes cobrem filtros e validações principais.

Labels sugeridas: `area/backend`, `area/security`, `area/privacy`, `type/feature`.

## Épico 1.3: Frontend público mobile-first

Objetivo: criar a experiência pública principal para encontrar ajuda.

Páginas mínimas:

- home;
- busca;
- detalhe do serviço;
- página da organização;
- sugerir serviço;
- reportar erro;
- sobre o projeto;
- privacidade.

Issues candidatas:

- Criar layout base mobile-first.
- Criar home com busca principal.
- Criar seletor de cidade.
- Criar filtros por categoria.
- Criar lista de resultados.
- Criar estado vazio para busca sem resultado.
- Criar página de detalhe do serviço.
- Criar bloco "Quem pode receber".
- Criar bloco "Como pedir ajuda".
- Criar bloco de documentos necessários.
- Criar bloco de contatos oficiais.
- Criar exibição de fonte e última verificação.
- Criar selo de status de confiança.
- Criar botão de compartilhar por WhatsApp.
- Criar botão de reportar erro.
- Criar formulário de sugestão de serviço.
- Criar página de privacidade em linguagem simples.
- Verificar acessibilidade por teclado.
- Verificar contraste.
- Verificar responsividade em celular.

Critérios de aceite:

- pessoa encontra serviço sem login;
- textos são simples e não prometem atendimento;
- resultado mostra status de verificação;
- layout funciona bem em celular;
- nenhum tracker invasivo é adicionado;
- formulários avisam para não enviar dados pessoais sensíveis.

Labels sugeridas: `area/frontend`, `area/accessibility`, `type/feature`, `priority/p1-high`.

## Épico 1.4: Painel administrativo mínimo

Objetivo: permitir revisão manual antes de publicação.

Funcionalidades mínimas:

- login de administradores;
- lista de serviços;
- criar serviço;
- editar serviço;
- revisar sugestões;
- revisar reports;
- marcar status;
- registrar verificação;
- ver histórico de alterações.

Issues candidatas:

- Criar autenticação para admin.
- Criar controle de acesso por papel.
- Criar listagem admin de serviços.
- Criar formulário admin de serviço.
- Criar fila de sugestões.
- Criar fila de reports.
- Criar ação de aprovar sugestão.
- Criar ação de rejeitar sugestão.
- Criar registro de verificação.
- Criar histórico de alterações.
- Criar filtros por status e cidade.
- Criar alerta para serviços antigos.
- Criar proteção contra links maliciosos.

Critérios de aceite:

- nenhum serviço sugerido aparece público sem revisão;
- alterações sensíveis ficam registradas;
- administradores não veem dados pessoais desnecessários;
- ações críticas exigem permissão adequada.

Labels sugeridas: `area/admin`, `area/data-quality`, `area/security`, `type/feature`.

## Épico 1.5: Operação inicial de dados

Objetivo: montar o primeiro catálogo confiável.

Issues candidatas:

- Criar planilha ou formato CSV padrão para importação.
- Criar guia para pesquisa de fontes.
- Criar checklist de verificação por telefone, site ou fonte oficial.
- Mapear serviços de alimentação em São Paulo.
- Mapear serviços de abrigo em São Paulo.
- Mapear serviços de documentação em São Paulo.
- Mapear serviços de saúde mental em São Paulo.
- Mapear serviços de emprego em São Paulo.
- Mapear serviços para imigrantes em São Paulo.
- Revisar duplicados.
- Revisar contatos oficiais.
- Revisar horários.
- Revisar critérios de atendimento.
- Marcar serviços sem confirmação como não verificados.
- Publicar lote inicial de 50 serviços.
- Publicar lote inicial de 100 serviços.
- Publicar lote inicial de 200 serviços.

Critérios de aceite:

- cada serviço tem fonte;
- cada serviço tem última verificação;
- serviços incertos são marcados como incertos;
- dados de pessoas atendidas não são coletados;
- serviços com risco de golpe não são publicados.

Labels sugeridas: `type/data`, `area/data-quality`, `needs-data-review`, `help-wanted`.

## Épico 1.6: Observabilidade sem rastrear usuários

Objetivo: medir saúde técnica e impacto inicial sem armazenar dados pessoais de usuários.

Métricas permitidas:

- total de buscas por categoria;
- total de buscas por cidade;
- total de resultados sem resposta;
- total de cliques agregados por serviço;
- total de reports por tipo;
- disponibilidade;
- latência;
- erros 4xx e 5xx;
- tempo de resposta da busca.

Issues candidatas:

- Definir eventos agregados permitidos.
- Criar camada de métricas sem user id.
- Configurar logs sem IP identificável.
- Configurar health checks.
- Criar dashboard técnico.
- Criar dashboard de impacto agregado.
- Criar alerta para erro 5xx.
- Criar alerta para falha de jobs.
- Documentar retenção de métricas.

Critérios de aceite:

- não existe identificação individual nos dashboards;
- métricas de produto são agregadas antes de armazenamento;
- logs operacionais minimizam identificadores;
- retenção está documentada.

Labels sugeridas: `area/devops`, `area/privacy`, `area/security`, `type/feature`.

## Fase 2: Lançamento público local

Milestone: `phase-2-public-launch`

Objetivo: abrir o MVP para usuários reais em uma cidade, com processo semanal de revisão e melhoria.

Resultado esperado: pessoas reais usam o produto, organizações começam a enviar correções, e a comunidade consegue medir busca com resultado, cliques agregados e lacunas de dados.

Critérios de saída:

- domínio público configurado;
- conteúdo básico de SEO local;
- processo semanal de revisão de dados;
- canal de suporte e reporte;
- acessibilidade validada;
- primeiros parceiros comunitários contatados;
- relatório público inicial de impacto agregado;
- backlog priorizado a partir de uso real.

## Épico 2.1: Preparação de lançamento

Issues candidatas:

- Definir domínio.
- Configurar ambiente de produção.
- Configurar backups.
- Configurar monitoramento.
- Configurar página de status.
- Revisar política de privacidade pública.
- Revisar termos de uso.
- Criar aviso contra golpes.
- Criar página "Sobre".
- Criar página "Como verificamos dados".
- Criar FAQ simples.
- Criar checklist de lançamento.

Critérios de aceite:

- ambiente está monitorado;
- privacidade pública é compreensível;
- usuários são avisados contra golpes;
- dados críticos têm revisão final antes do lançamento.

Labels sugeridas: `area/devops`, `area/docs`, `area/security`, `priority/p1-high`.

## Épico 2.2: SEO e páginas locais

Issues candidatas:

- Criar página de alimentação em São Paulo.
- Criar página de abrigo em São Paulo.
- Criar página de documentação em São Paulo.
- Criar página de saúde mental em São Paulo.
- Criar página de emprego em São Paulo.
- Criar página para imigrantes em São Paulo.
- Adicionar metadata por categoria.
- Adicionar sitemap.
- Adicionar robots.txt.
- Adicionar schema.org quando apropriado.
- Criar regra para data de atualização visível.

Critérios de aceite:

- páginas não prometem atendimento;
- páginas mostram atualização;
- conteúdo é simples e direto;
- SEO não cria páginas enganosas ou duplicadas.

Labels sugeridas: `area/frontend`, `area/docs`, `type/feature`, `priority/p2-medium`.

## Épico 2.3: Feedback e reports

Issues candidatas:

- Melhorar formulário de reportar erro.
- Criar categorias de report.
- Criar fila de prioridade para reports críticos.
- Criar confirmação visual de envio.
- Criar fluxo para ocultar serviço suspeito.
- Criar SLA interno para reports de golpe.
- Criar métrica agregada de reports resolvidos.
- Criar guia para responder reports.

Critérios de aceite:

- reports não expõem dados pessoais desnecessários;
- reports críticos chegam ao admin com prioridade;
- serviço suspeito pode ser ocultado rapidamente;
- resolução fica registrada.

Labels sugeridas: `area/admin`, `area/data-quality`, `area/security`, `type/feature`.

## Épico 2.4: Acessibilidade e inclusão

Issues candidatas:

- Revisar contraste de todas as páginas públicas.
- Testar navegação por teclado.
- Testar leitores de tela.
- Revisar textos em linguagem simples.
- Adicionar suporte a fonte maior.
- Garantir que mapa não seja obrigatório.
- Criar modo de baixo consumo de dados.
- Revisar experiência em celulares antigos.
- Revisar experiência para conexão lenta.

Critérios de aceite:

- busca funciona sem mapa;
- conteúdo principal é acessível por leitor de tela;
- botões e links têm nomes claros;
- páginas carregam bem em conexão limitada.

Labels sugeridas: `area/accessibility`, `area/frontend`, `type/design`, `priority/p1-high`.

## Épico 2.5: Rotina pública de qualidade de dados

Issues candidatas:

- Criar calendário semanal de revisão.
- Criar fila de serviços com verificação vencida.
- Criar rotina mensal de revisão por categoria.
- Criar rotina de checagem de links quebrados.
- Criar rotina de checagem de telefones inválidos.
- Criar relatório público de qualidade de dados.
- Criar treinamento básico para voluntários verificadores.

Critérios de aceite:

- dados antigos entram em fila;
- voluntários têm instruções claras;
- relatório mostra quantidade de serviços verificados, pendentes e reportados;
- qualidade de dados vira trabalho contínuo.

Labels sugeridas: `area/data-quality`, `type/data`, `help-wanted`.

## Fase 3: Organizações

Milestone: `phase-3-organizations`

Objetivo: permitir que organizações legítimas cadastrem e mantenham seus próprios serviços, com verificação institucional e moderação.

Resultado esperado: ONGs, igrejas, comunidades, empresas responsáveis e órgãos públicos conseguem atualizar dados sem publicar automaticamente informações perigosas ou falsas.

Critérios de saída:

- cadastro de organização;
- verificação institucional;
- painel da organização;
- equipe da organização;
- histórico de alterações;
- revisão de alterações sensíveis;
- dashboard agregado para organizações;
- regras de privacidade e retenção para contas institucionais.

## Épico 3.1: Cadastro e verificação institucional

Issues candidatas:

- Criar modelo de usuário de organização.
- Criar fluxo de cadastro de organização.
- Criar verificação de e-mail institucional.
- Criar verificação de domínio.
- Criar campos de documento institucional quando aplicável.
- Criar status de organização.
- Criar fila admin de verificação.
- Criar rejeição com motivo.
- Criar reenvio de dados.
- Criar política de retenção para documentos de verificação.

Critérios de aceite:

- organizações não publicam automaticamente;
- documentos sensíveis têm acesso restrito;
- dados de verificação têm retenção definida;
- status público da organização é claro.

Labels sugeridas: `area/backend`, `area/admin`, `area/privacy`, `type/feature`.

## Épico 3.2: Painel de organização

Issues candidatas:

- Criar login de organização.
- Criar recuperação de acesso.
- Criar dashboard de serviços.
- Criar formulário para editar serviço.
- Criar preview antes de enviar alteração.
- Criar fluxo de submissão para revisão.
- Criar histórico de alterações.
- Criar gerenciamento de equipe.
- Criar papéis dentro da organização.
- Criar aviso de revisão pendente.
- Criar painel de reports recebidos.

Critérios de aceite:

- alteração sensível pode exigir revisão humana;
- organização vê reports dos próprios serviços;
- histórico de alterações é auditável;
- permissões internas são respeitadas.

Labels sugeridas: `area/frontend`, `area/backend`, `area/admin`, `type/feature`.

## Épico 3.3: Métricas para organizações sem rastrear pessoas

Issues candidatas:

- Definir métricas permitidas para organizações.
- Criar visualização de visitas agregadas.
- Criar visualização de cliques agregados.
- Criar visualização de reports agregados.
- Criar exportação agregada.
- Criar aviso de privacidade sobre métricas.
- Bloquear drill-down para usuários individuais.

Critérios de aceite:

- organização nunca vê histórico individual de usuários;
- métricas são agregadas;
- nenhuma localização precisa de usuário é exibida;
- dashboard não permite reidentificação.

Labels sugeridas: `area/privacy`, `area/frontend`, `area/backend`, `priority/p0-critical`.

## Fase 4: IA segura

Milestone: `phase-4-safe-ai`

Objetivo: adicionar IA somente onde ela melhora clareza, busca, tradução, revisão e qualidade de dados, sem substituir responsabilidade humana.

Resultado esperado: IA ajuda pessoas e mantenedores, mas não promete direitos, não decide elegibilidade definitiva e não publica dados sem revisão.

Critérios de saída:

- avaliação de risco de IA;
- prompts revisados;
- logs sem dados pessoais sensíveis;
- revisão humana em conteúdo publicado;
- linguagem probabilística;
- rastreabilidade para revisores;
- desligamento de IA possível por configuração.

## Épico 4.1: Governança de IA

Issues candidatas:

- Criar RFC para primeira funcionalidade de IA.
- Criar checklist de risco de IA.
- Criar política de prompts sem dados pessoais.
- Criar política de logs de IA.
- Criar registro de decisões assistidas por IA.
- Criar mecanismo de revisão humana.
- Criar fallback sem IA.
- Criar aviso público quando conteúdo for assistido por IA.

Critérios de aceite:

- conselho comunitário aprova usos sensíveis;
- prompts não incluem dados pessoais desnecessários;
- IA pode ser auditada por revisores;
- IA pode ser desligada sem quebrar o produto.

Labels sugeridas: `area/ai`, `area/privacy`, `type/rfc`, `needs-security-review`.

## Épico 4.2: Busca semântica segura

Issues candidatas:

- Avaliar busca semântica sem dados pessoais.
- Criar indexação apenas de dados institucionais.
- Criar busca por sinônimos.
- Criar busca multilíngue.
- Criar teste para consultas comuns.
- Criar avaliação de resultados ruins.
- Criar bloqueio de consultas sensíveis nos logs.

Critérios de aceite:

- índice não contém dados pessoais de usuários;
- busca melhora resultados sem rastrear pessoas;
- consultas não ficam associadas a usuário individual.

Labels sugeridas: `area/ai`, `area/search`, `area/privacy`, `type/feature`.

## Épico 4.3: Resumos e traduções assistidas

Issues candidatas:

- Criar resumo simples para serviços.
- Criar tradução assistida para inglês.
- Criar tradução assistida para espanhol.
- Criar revisão humana obrigatória antes de publicar.
- Criar diffs para revisores.
- Criar glossário de termos sensíveis.
- Criar testes de linguagem proibida.

Critérios de aceite:

- resumo não altera regras do serviço;
- tradução não promete atendimento;
- revisão humana é obrigatória antes de publicação;
- termos como "garantido" e "aprovado" são bloqueados em contextos de elegibilidade.

Labels sugeridas: `area/ai`, `area/i18n`, `area/data-quality`, `type/feature`.

## Épico 4.4: Elegibilidade provável com cuidado

Issues candidatas:

- Criar RFC de elegibilidade provável.
- Definir perguntas permitidas sem armazenamento server-side.
- Definir processamento local quando possível.
- Definir textos de incerteza.
- Criar aviso "confirme com a organização responsável".
- Criar bloqueio contra aconselhamento jurídico ou médico definitivo.
- Criar revisão humana para regras sensíveis.
- Criar testes com casos limites.

Critérios de aceite:

- respostas não são armazenadas no servidor no estágio inicial;
- recomendação usa linguagem probabilística;
- não existe decisão final automatizada;
- fluxo explica limites de forma simples.

Labels sugeridas: `area/ai`, `area/privacy`, `area/frontend`, `priority/p0-critical`.

## Fase 5: Capítulos locais

Milestone: `phase-5-local-chapters`

Objetivo: permitir expansão por cidade, região e país sem perder qualidade, segurança e missão.

Resultado esperado: grupos locais conseguem mapear serviços, revisar dados e operar com autonomia limitada por padrões comuns.

Critérios de saída:

- guia de criação de capítulo;
- checklist de aprovação;
- kit de treinamento;
- modelo de governança local;
- métricas por capítulo;
- processo de suporte;
- processo para pausar capítulo em caso de risco.

## Épico 5.1: Kit de capítulo local

Issues candidatas:

- Criar guia "como abrir um capítulo local".
- Criar checklist de requisitos mínimos.
- Criar template de README local.
- Criar template de plano de cidade.
- Criar template de planilha de serviços.
- Criar guia de verificação de fontes.
- Criar guia de contato com organizações.
- Criar guia de segurança para voluntários.
- Criar política de comunicação pública.
- Criar kit de tradução local.

Critérios de aceite:

- capítulo sabe por onde começar;
- capítulo não pode enfraquecer privacidade, segurança, IA ou financiamento;
- processo exige pelo menos duas pessoas responsáveis.

Labels sugeridas: `area/local-chapters`, `type/docs`, `help-wanted`.

## Épico 5.2: Expansão para novas cidades

Issues candidatas:

- Selecionar segunda cidade.
- Mapear fontes públicas da segunda cidade.
- Definir categorias iniciais da segunda cidade.
- Recrutar dois responsáveis locais.
- Cadastrar 100 serviços iniciais.
- Revisar 100 serviços iniciais.
- Publicar páginas por cidade.
- Criar rotina de revisão local.
- Criar relatório de lacunas locais.

Critérios de aceite:

- cidade tem responsáveis locais;
- dados têm fonte e verificação;
- páginas deixam claro o status local;
- rotina de manutenção existe.

Labels sugeridas: `area/local-chapters`, `type/data`, `area/data-quality`.

## Épico 5.3: Governança federada

Issues candidatas:

- Criar modelo de permissões por capítulo.
- Criar processo para aprovar capítulo.
- Criar processo para pausar capítulo.
- Criar processo para transferir mantenedores locais.
- Criar relatório periódico por capítulo.
- Criar canal de suporte entre capítulos.
- Criar processo de auditoria de dados local.

Critérios de aceite:

- capítulos têm autonomia operacional;
- regras centrais continuam obrigatórias;
- risco local pode ser contido rapidamente.

Labels sugeridas: `area/governance`, `area/local-chapters`, `type/rfc`.

## Fase 6: Ecossistema

Milestone: `phase-6-ecosystem`

Objetivo: transformar o OpenSource for Humans em infraestrutura aberta para parceiros, governos, organizações e comunidades, sem vender dados pessoais nem capturar a missão.

Resultado esperado: API pública segura, integrações, relatórios de impacto agregados, ferramentas institucionais e sustentabilidade financeira responsável.

Critérios de saída:

- API pública documentada;
- termos de uso da API;
- rate limits;
- dados abertos seguros;
- relatórios públicos agregados;
- política de parcerias;
- política de financiamento aplicada;
- ferramentas institucionais sem prioridade paga em ajuda essencial.

## Épico 6.1: API pública segura

Issues candidatas:

- Criar RFC da API pública.
- Definir quais dados podem ser abertos.
- Definir quais dados nunca podem ser abertos.
- Criar autenticação para parceiros quando necessário.
- Criar rate limit.
- Criar documentação de API.
- Criar exemplos de uso.
- Criar termos de uso da API.
- Criar monitoramento de abuso.
- Criar processo para revogar acesso.

Critérios de aceite:

- API não expõe dados pessoais de usuários;
- dados institucionais têm licença e fonte;
- abuso pode ser bloqueado;
- parceiros entendem limites de uso.

Labels sugeridas: `area/backend`, `area/security`, `area/privacy`, `type/feature`.

## Épico 6.2: Relatórios de impacto

Issues candidatas:

- Definir métricas públicas permitidas.
- Criar relatório mensal agregado.
- Criar relatório por cidade.
- Criar relatório por categoria.
- Criar métricas de qualidade de dados.
- Criar métricas de reports resolvidos.
- Criar metodologia pública.
- Criar revisão de risco de reidentificação.

Critérios de aceite:

- relatórios não permitem reidentificação;
- metodologia é pública;
- dados são agregados;
- limitações são explicadas.

Labels sugeridas: `area/data-quality`, `area/privacy`, `area/community`, `type/docs`.

## Épico 6.3: Parcerias e sustentabilidade

Issues candidatas:

- Criar política de parcerias.
- Criar processo de avaliação de financiadores.
- Criar página pública de apoiadores.
- Criar declaração de conflitos de interesse.
- Criar modelo de parceria com governo.
- Criar modelo de parceria com ONG.
- Criar modelo de parceria com universidade.
- Criar modelo de parceria com empresa responsável.
- Criar limites para ferramentas pagas.
- Criar auditoria para prioridade de resultados.

Critérios de aceite:

- nenhum financiador controla governança;
- pagamento não aumenta confiança pública de uma organização;
- pessoas buscando ajuda continuam sem cobrança;
- conflitos de interesse são publicados.

Labels sugeridas: `area/funding`, `area/governance`, `type/docs`, `needs-legal-review`.

## Backlog inicial recomendado

Estas issues podem ser criadas primeiro para destravar o projeto.

## Prioridade P0

- `[privacy] Define no server-side user data storage checklist`
- `[privacy] Define anonymized aggregate analytics policy`
- `[security] Define private vulnerability reporting channel`
- `[data] Define minimum publishable service fields`
- `[data] Define prohibited personal data fields`
- `[governance] Create GitHub issue and PR templates`
- `[product] Confirm initial city and categories`
- `[data] Create initial service verification checklist`

## Prioridade P1

- `[frontend] Create mobile-first public search wireframe`
- `[frontend] Create service detail page wireframe`
- `[backend] Draft service catalog API contract`
- `[data-model] Draft Organization and Service schemas`
- `[admin] Define moderation queue workflow`
- `[docs] Create local chapter starter guide`
- `[accessibility] Create accessibility checklist`
- `[security] Create abuse and scam risk checklist`

## Prioridade P2

- `[data] Map first 50 food support services`
- `[data] Map first 50 shelter or emergency services`
- `[i18n] Define translation workflow`
- `[seo] Define local SEO page structure`
- `[devops] Choose MVP hosting approach`
- `[community] Define contributor onboarding flow`
- `[funding] Draft responsible funding principles page`

## Métricas por fase

## Fase 0

- número de documentos essenciais concluídos;
- número de templates criados;
- número de issues prontas;
- número de contribuidores iniciais;
- escopo inicial aprovado.

## Fase 1

- serviços cadastrados;
- serviços verificados;
- buscas agregadas por categoria;
- buscas sem resultado;
- cliques agregados em "como pedir ajuda";
- reports recebidos;
- reports resolvidos;
- tempo médio de resposta da busca;
- disponibilidade.

## Fase 2

- usuários agregados por cidade sem identificação individual;
- taxa de busca com resultado;
- taxa de clique em contato agregada;
- número de organizações contatadas;
- número de correções recebidas;
- idade média dos dados publicados;
- acessibilidade validada.

## Fase 3

- organizações verificadas;
- serviços gerenciados por organizações;
- alterações aprovadas;
- reports respondidos por organizações;
- tempo médio de atualização;
- dados institucionais com retenção definida.

## Fase 4

- sugestões de IA revisadas;
- duplicados detectados;
- traduções revisadas;
- resumos aprovados;
- incidentes ou rejeições por linguagem insegura;
- porcentagem de fluxos com fallback sem IA.

## Fase 5

- capítulos ativos;
- responsáveis locais;
- serviços por cidade;
- porcentagem de serviços verificados por capítulo;
- relatórios locais publicados;
- capítulos pausados por risco, se houver.

## Fase 6

- parceiros ativos;
- chamadas de API agregadas;
- incidentes de abuso bloqueados;
- relatórios de impacto publicados;
- financiamento público declarado;
- auditorias de prioridade de resultados.

## Gates de segurança, privacidade e missão

Antes de cada release pública, responder:

- Esta mudança armazena dados pessoais de usuários finais no servidor?
- Se sim, existe justificativa, base legal, retenção, revisão e alternativa sem armazenamento?
- Estatísticas são anonimizadas e agregadas antes do armazenamento?
- Algum fluxo exige login para encontrar ajuda?
- Algum serviço pago ganha prioridade em ajuda essencial?
- Alguma IA toma decisão definitiva?
- Alguma página promete atendimento, direito, aprovação ou resultado?
- Dados de serviço têm fonte e última verificação?
- Existe forma simples de reportar erro?
- Existe risco de golpe, abuso ou exposição de pessoas vulneráveis?
- A mudança funciona em celular?
- A mudança é compreensível para pessoas com baixo letramento digital?

Se uma resposta indicar risco alto, a release deve ser bloqueada até revisão de mantenedores ou do conselho comunitário.

## O que não construir no início

Evitar no MVP:

- chat em tempo real;
- app mobile nativo;
- doações financeiras dentro da plataforma;
- ranking público de organizações;
- marketplace complexo de voluntariado;
- IA autônoma;
- elegibilidade definitiva;
- login obrigatório para buscar ajuda;
- coleta de CPF, documento, telefone ou endereço de quem busca ajuda;
- histórico individual de busca;
- anúncios;
- prioridade paga;
- integrações bancárias;
- CRM completo para ONGs.

## Tamanho recomendado das issues

Issues boas para contribuição devem caber em:

- `effort/xs`: até 1 hora, documentação ou ajuste pequeno;
- `effort/s`: meio dia, componente simples ou pesquisa curta;
- `effort/m`: 1 a 2 dias, endpoint, tela ou fluxo pequeno;
- `effort/l`: vários dias, épico técnico menor;
- `effort/xl`: deve ser quebrada antes de alguém começar.

Regra prática:

> Se uma issue precisa de mais de uma pessoa trabalhando ao mesmo tempo, provavelmente ela deve virar épico e ser quebrada.

## Modelo curto de issue

```md
## Objetivo

## Contexto

## Escopo

## Fora de escopo

## Critérios de aceite

## Riscos de privacidade

## Riscos de segurança

## Riscos de impacto social

## Dependências

## Arquivos ou áreas prováveis
```

## Próximo passo recomendado

Criar a milestone `phase-0-foundation` e abrir as issues P0 do backlog inicial.

Depois disso, cada épico da Fase 0 deve ser transformado em uma issue principal, e cada item do checklist deve virar uma issue pequena com labels, responsável e critério de aceite.
