# 05 — Identidade e acesso

## Modelo de identidade

As contas de usuário foram provisionadas no Microsoft 365 e receberam licenciamento compatível com os serviços web de e-mail e colaboração. O domínio técnico criado automaticamente pelo Microsoft 365 não foi adotado como identidade corporativa de comunicação.

## Controle de acesso

O SharePoint foi organizado utilizando grupos associados a funções. A representação anonimizada do modelo adotado é:

| Elemento genérico | Papel |
|---|---|
| Grupo de Segurança A | Acesso a uma biblioteca funcional |
| Grupo de Segurança B | Acesso a outra biblioteca funcional |
| Grupo de Segurança C | Acesso a conteúdo compartilhado internamente |
| Grupo de proprietários | Administração do site |

A tabela não representa nomes, quantidades ou relações reais do ambiente.

O responsável declarou que concessões diretas a usuários não foram utilizadas como modelo de permissão. Detalhes de permissões exclusivas e exceções internas foram deliberadamente excluídos.

## Administração

Uma identidade administrativa dedicada foi associada à propriedade do site. A documentação pública não registra endereço, nome, quantidade de administradores ou associação a funções do tenant.

## Padrões de Segurança

Os Padrões de Segurança do Microsoft Entra ID foram confirmados como habilitados. Essa configuração fornece uma linha de base de proteção para identidades no licenciamento disponível.

Não foram documentadas políticas personalizadas de Acesso Condicional ou Identity Protection, pois não há evidência de que tenham sido implementadas.

## MFA

O método observado na validação administrativa foi:

1. autenticação com senha;
2. solicitação no Microsoft Authenticator;
3. correspondência numérica para aprovação.

O teste foi realizado somente na conta administrativa autorizada. Não foram acessadas contas de colaboradores. Portanto, a documentação diferencia a configuração organizacional habilitada da validação interativa individual.

## Controles observados

- Administração por grupos.
- Identidade administrativa dedicada.
- MFA para acesso administrativo.
- Não utilização de credenciais de terceiros em testes.
- Registro das limitações de validação.
- Ausência de inventários reais no repositório.
