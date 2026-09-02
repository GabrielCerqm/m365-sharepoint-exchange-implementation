# 02 — Cenário inicial

## Situação observada

A organização utilizava um provedor externo para e-mail e não dispunha de um repositório corporativo estruturado para colaboração documental. O novo ambiente deveria atender uma equipe reduzida sem tornar a administração de acessos dependente de permissões concedidas manualmente a cada usuário.

## Necessidades

- E-mail corporativo integrado ao Microsoft 365.
- Domínio personalizado validado.
- Identidades e licenças administradas centralmente.
- Armazenamento em nuvem organizado por função de trabalho.
- Separação lógica entre conjuntos de documentos.
- Autenticação multifator.
- Administração contínua após a implantação.

## Restrições

- Ambiente real e sujeito a impacto operacional.
- Histórico de e-mail anterior sem necessidade de migração.
- Ausência de acervo documental inicial para migração.
- Impossibilidade de acessar contas de colaboradores para testes interativos.
- Dependências de DNS legado não totalmente inventariadas.
- Divulgação externa restrita à versão anonimizada autorizada, sem identificação ou associação ao ambiente do cliente.

## Delimitação

O projeto não deve ser descrito como migração completa de dados. A atividade comprovada foi a implantação de novos serviços e a transição do roteamento de e-mail, mantendo o histórico anterior fora do escopo.
