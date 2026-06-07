# Princípios de Privacidade

OpenSource for Humans deve ser privado por padrão e seguro desde a concepção.

## Regras principais

1. A busca por ajuda deve funcionar sem login.
2. A plataforma não deve exigir nome, CPF, documento, endereço completo ou telefone para busca básica.
3. Neste primeiro momento, dados pessoais de pessoas que buscam ajuda e visitantes em geral não devem ser armazenados do lado do servidor.
4. Localização deve ser aproximada sempre que possível.
5. Dados pessoais devem ter finalidade explícita.
6. Dados sensíveis devem ser evitados.
7. Dados devem ser retidos pelo menor tempo necessário.
8. Analytics devem ser agregados, anonimizados e não invasivos.
9. Compartilhamento com terceiros deve ser mínimo, documentado e justificado.
10. Pessoas devem conseguir pedir acesso, correção e eliminação de dados.
11. Decisões automatizadas sensíveis devem ter revisão humana.

## Privacidade por padrão

Funcionalidades novas devem começar com a menor coleta possível.

Exemplo: para buscar ajuda perto, a plataforma deve aceitar cidade ou bairro em vez de exigir GPS preciso.

## Proibição inicial de armazenamento server-side

Durante a primeira fase do projeto, a plataforma não deve armazenar do lado do servidor dados pessoais de pessoas que buscam ajuda ou visitantes em geral.

Isso inclui:

- nomes;
- CPF, RG ou documentos de identidade;
- telefones privados;
- endereços residenciais exatos;
- coordenadas GPS precisas;
- histórico individual de busca;
- respostas individuais de elegibilidade;
- cliques individuais em contato;
- endereços IP identificáveis em logs da aplicação;
- replay de sessão ou rastreamento comportamental associado a uma pessoa.

Se estatísticas forem necessárias, elas devem ser geradas a partir de dados anonimizados e agregados antes do armazenamento.

O sistema pode contar eventos como buscas por categoria, demanda por cidade, cliques em resultados e denúncias, mas não deve manter dados que identifiquem ou individualizem uma pessoa.

Esta regra se aplica a pessoas que buscam ajuda e visitantes em geral. Dados de contas de organizações são tratados separadamente e devem seguir base legal documentada, finalidade limitada e controle de acesso rigoroso.

## Privacidade desde a concepção

Toda mudança relevante deve responder:

- quais dados são coletados;
- por que são necessários;
- qual base legal permite o tratamento;
- por quanto tempo serão mantidos;
- quem terá acesso;
- se o armazenamento no servidor pode ser evitado completamente;
- se estatísticas podem ser produzidas apenas com dados anonimizados e agregados;
- como a pessoa pode exercer direitos;
- que dano pode ocorrer se houver vazamento;
- como reduzir esse dano.

## Pessoas vulneráveis

O projeto deve tratar como alto risco qualquer fluxo que envolva pessoas em situação de rua, migrantes, refugiados, crianças, adolescentes, vítimas de violência, saúde mental, insegurança alimentar ou emergência.
