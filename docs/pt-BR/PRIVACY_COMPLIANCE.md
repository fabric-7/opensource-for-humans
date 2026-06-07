# Conformidade com LGPD e GDPR/RGPD

Este documento define o padrão mínimo de proteção de dados do OpenSource for Humans.

O projeto deve cumprir simultaneamente:

- LGPD brasileira: Lei Geral de Proteção de Dados Pessoais, Lei nº 13.709/2018.
- GDPR/RGPD europeu: General Data Protection Regulation, Regulamento (UE) 2016/679.

Quando houver diferença entre normas, interpretações ou práticas, deve prevalecer a regra que oferecer maior proteção à pessoa titular dos dados.

Este documento é uma política operacional do projeto e não substitui revisão jurídica profissional.

## Regra de proteção máxima

Se LGPD e GDPR/RGPD tratarem o mesmo tema de formas diferentes, o OpenSource for Humans deve aplicar o padrão mais protetivo em:

- minimização de dados;
- evitar armazenamento server-side de dados pessoais de usuários sempre que possível;
- transparência;
- consentimento;
- base legal;
- direitos do titular;
- segurança;
- retenção;
- portabilidade;
- eliminação;
- oposição;
- revisão de decisões automatizadas;
- proteção de dados sensíveis;
- proteção de crianças e adolescentes;
- transferências internacionais;
- resposta a incidentes;
- avaliação de impacto.

## Regra inicial de não armazenamento

Neste primeiro momento, dados pessoais de pessoas que buscam ajuda e visitantes em geral não devem ser armazenados do lado do servidor.

O produto deve ser desenhado para que o uso básico não deixe perfil de usuário, histórico de busca, registro de localização precisa, respostas de elegibilidade ou trilha de cliques em contato associados a uma pessoa no servidor.

Logs da aplicação e analytics devem ser configurados para evitar o armazenamento de dados identificáveis de usuários. Quando logs operacionais forem tecnicamente necessários, identificadores como endereços IP devem ser removidos, truncados, anonimizados ou retidos apenas pelo menor período crítico de segurança.

Se algum dado relacionado a usuários vier a ser necessário para estatísticas, ele deve ser anonimizado e agregado antes do armazenamento. As estatísticas armazenadas não devem permitir que o projeto, parceiros ou terceiros identifiquem, individualizem, rastreiem ou reidentifiquem uma pessoa.

Esta regra se aplica a pessoas que buscam ajuda e visitantes em geral. Dados de contas de organizações são tratados separadamente e exigem base legal documentada, finalidade limitada, controle de acesso rigoroso e limites de retenção.

## Bases legais

Cada tratamento de dado pessoal deve ter base legal documentada.

Exemplos de finalidades:

- permitir busca anônima por cidade ou bairro;
- permitir que organizações mantenham dados institucionais;
- receber denúncias de dados incorretos;
- prevenir fraude e abuso;
- medir uso apenas de forma anonimizada e agregada;
- enviar alertas opcionais quando a pessoa pedir.

Consentimento, quando usado, deve ser livre, informado, específico e revogável.

## Dados sensíveis

Dados sensíveis devem ser evitados por padrão.

Quando forem estritamente necessários, exigem:

- justificativa documentada;
- base legal adequada;
- proteção técnica reforçada;
- acesso restrito;
- retenção curta;
- avaliação de impacto;
- revisão humana.

## Direitos das pessoas

O projeto deve oferecer meios para solicitar:

- confirmação de tratamento;
- acesso;
- correção;
- anonimização;
- eliminação;
- portabilidade quando aplicável;
- informação sobre compartilhamento;
- revogação de consentimento;
- oposição;
- revisão de decisão automatizada quando aplicável.

## Crianças e adolescentes

O projeto deve evitar coletar dados de crianças e adolescentes.

Quando um serviço atender esse público, a página deve descrever o serviço sem identificar crianças ou adolescentes individualmente.

## IA e decisões automatizadas

IA não deve tomar decisões definitivas sobre elegibilidade, prioridade, direito a benefício, saúde, segurança, abrigo ou emergência.

Qualquer recomendação automatizada deve usar linguagem probabilística, como:

> Você pode ser elegível. Confirme com a organização responsável.

Fluxos sensíveis devem permitir revisão humana.

## Transferências internacionais

Antes de transferir dados pessoais entre países ou provedores internacionais, o projeto deve documentar:

- quais dados serão transferidos;
- para qual país;
- para qual fornecedor;
- com qual base legal;
- quais garantias contratuais e técnicas existem;
- como o titular pode exercer direitos.

## Retenção

Dados pessoais devem ter prazo de retenção definido.

Quando a finalidade terminar, os dados devem ser eliminados, anonimizados ou agregados.

## Incidentes

Incidentes de segurança devem ser avaliados rapidamente quanto a:

- tipo de dado afetado;
- número de pessoas afetadas;
- risco para pessoas vulneráveis;
- medidas de contenção;
- necessidade de comunicação a titulares;
- necessidade de comunicação a autoridades.

## Encarregado/DPO

O projeto deve nomear uma pessoa ou grupo responsável por proteção de dados quando operar publicamente com usuários reais.

Essa função deve servir como canal para titulares, comunidade, organizações e autoridades.

## Referências oficiais

- LGPD: https://www.gov.br/int/pt-br/acesso-a-informacao/lgpd
- GDPR/RGPD: https://www.edps.europa.eu/general-data-protection-regulation_en
