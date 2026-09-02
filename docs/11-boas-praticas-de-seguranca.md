# 11 — Controles e postura de segurança

## Controles implementados

- Padrões de Segurança habilitados no Microsoft Entra ID.
- MFA administrativo com Microsoft Authenticator.
- Controle de acesso documental orientado a grupos.
- Site de equipe privado.
- Versionamento habilitado nas bibliotecas.
- SPF, DKIM e DMARC configurados no domínio corporativo.
- Separação entre evidências privadas e documentação de portfólio.
- Validação sem acesso às caixas dos colaboradores.
- Preservação de configurações de produção com dependências incertas.

## Restrições identificadas

A linha de base disponível não foi apresentada como equivalente a uma arquitetura avançada de identidade. Não houve evidência de políticas personalizadas de Acesso Condicional, Identity Protection ou revisão automatizada de privilégios.

A validação interativa de MFA ficou restrita à conta administrativa. O modelo de permissões foi inspecionado administrativamente, mas não foram executados testes negativos com todos os perfis funcionais.

## Menor privilégio

A administração por grupos reduziu concessões individuais e organizou o acesso por função. A documentação não afirma conformidade integral com menor privilégio porque as associações, exceções e revisões periódicas não foram auditadas de forma completa.

## Secure Score

O Microsoft Secure Score foi utilizado como referência para avaliação da postura. A pontuação não foi apresentada como certificação ou garantia de segurança, e nenhuma recomendação foi considerada implementada sem evidência direta e licenciamento compatível.