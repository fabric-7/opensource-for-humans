# Segurança

Segurança no OpenSource for Humans é uma questão técnica e humana. Uma falha pode expor pessoas vulneráveis, organizações ou voluntários.

## Reporte vulnerabilidades

Se encontrar uma vulnerabilidade, não abra issue pública com detalhes exploráveis.

Use um canal privado definido pela equipe mantenedora. Enquanto esse canal não existir, reporte diretamente aos mantenedores do projeto.

## Escopo sensível

São considerados sensíveis:

- exposição de dados pessoais;
- falhas de autenticação;
- acesso indevido ao painel admin;
- alteração não autorizada de serviços;
- injeção de links maliciosos;
- scraping abusivo;
- vazamento de logs;
- prompts ou logs de IA com dados pessoais;
- falhas que facilitem golpe ou falsa organização.

## Resposta a incidentes

Ao confirmar um incidente:

1. Conter o problema.
2. Preservar evidências.
3. Avaliar dados e pessoas afetadas.
4. Corrigir a causa.
5. Comunicar titulares e autoridades quando necessário.
6. Publicar resumo pós-incidente quando for seguro.

## Desenvolvimento seguro

Mudanças críticas devem considerar:

- validação de entrada;
- controle de acesso;
- logs sem dados sensíveis;
- rate limit;
- revisão de dependências;
- backups;
- auditoria;
- proteção contra spam e golpe.
