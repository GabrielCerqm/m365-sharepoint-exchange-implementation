# 11 — Boas práticas de segurança

## Práticas efetivamente adotadas

- Linha de base de segurança habilitada no Microsoft Entra ID.
- MFA administrativo com Microsoft Authenticator.
- Controle de acesso documental orientado a grupos.
- Site de equipe privado.
- Versionamento nas bibliotecas.
- SPF, DKIM e DMARC no domínio corporativo.
- Separação entre evidências privadas e documentação pública.
- Ausência de acesso às caixas dos colaboradores durante a validação.
- Preservação cautelosa de configurações de produção com dependências incertas.

## Recomendações futuras

Os itens abaixo são recomendações e não devem ser descritos como implementados:

- revisar periodicamente membros de grupos e proprietários;
- revisar compartilhamentos externos e convidados;
- utilizar conta administrativa separada da conta de uso cotidiano;
- manter mais de um método de recuperação administrativa controlado;
- revisar a postura do Microsoft Secure Score em ciclos definidos;
- avaliar licenciamento para controles adicionais de identidade, quando necessário;
- estabelecer processo formal de admissão, movimentação e desligamento;
- registrar alterações de DNS com aprovação e plano de reversão;
- revisar a política DMARC após período de observação e análise de impacto;
- testar restauração de documentos sem utilizar conteúdo real no portfólio;
- formalizar revisão periódica de permissões;
- manter inventário privado dos ativos e objetos administrativos.

## Menor privilégio

O uso de grupos simplifica a administração, mas não garante por si só o menor privilégio. Esse princípio exige revisão periódica das associações, dos níveis de permissão e das exceções existentes.

## Secure Score

O Microsoft Secure Score foi utilizado como referência de postura e priorização. Ele não deve ser apresentado como garantia de segurança, certificação ou comprovação isolada de que todas as recomendações foram implementadas manualmente.

Algumas ações podem ser reconhecidas por controles equivalentes ou configurações padrão. Por isso, a documentação não atribui políticas avançadas sem evidência direta e licenciamento compatível.
