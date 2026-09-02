# 10 — Testes e validações

## Base de comprovação

A documentação considerou como concluídas somente as verificações sustentadas por estado administrativo, evidência técnica ou declaração do responsável pelo ambiente. Atividades sem registro permaneceram classificadas como não confirmadas.

## Matriz de validação do projeto

| Verificação | Estado | Método ou evidência | Limitação |
|---|---|---|---|
| Domínio personalizado aceito pelo Microsoft 365 | Confirmado | Estado administrativo | Identificador real omitido |
| Registros principais de e-mail | Confirmado | Integridade exibida no centro administrativo | Valores reais omitidos |
| Resolução de DMARC | Confirmado | Consulta DNS | Política exata omitida |
| DKIM no domínio personalizado | Confirmado | Estado válido e habilitado | Seletores omitidos |
| Caixas de usuário provisionadas | Confirmado | Inventário administrativo privado | Não houve acesso às caixas |
| Lista de distribuição funcional | Confirmado | Estado administrativo e declaração do responsável | Membros e endereço omitidos |
| Site de equipe privado | Confirmado | Estado administrativo | URL e nome omitidos |
| Grupos de segurança existentes | Confirmado | Inventário administrativo privado | Estrutura real omitida |
| Permissões por grupos | Confirmado | Inspeção administrativa | Matriz real omitida |
| Versionamento nas bibliotecas | Confirmado | Amostra visual e declaração do responsável | Uma captura representa a configuração padronizada |
| Padrões de Segurança | Confirmado | Estado no Microsoft Entra ID | Políticas detalhadas não exportadas |
| MFA administrativo | Confirmado | Login autorizado com Microsoft Authenticator | Somente a conta administrativa foi testada |
| MFA individual dos colaboradores | Não validado interativamente | Restrição de privacidade | Credenciais de terceiros não foram utilizadas |
| Envio e recebimento em cada caixa | Não confirmado formalmente | Ambiente informado como operacional | Sem acesso individual às caixas |
| Acesso negativo por todas as funções | Não confirmado formalmente | Configuração inspecionada | Sem teste com cada perfil |
| Secure Score atualizado | Não confirmado | Evidência atualizada válida não disponível | Valor não incorporado |

## Validação de MFA

O teste autorizado confirmou o fluxo de senha seguido pelo Microsoft Authenticator com correspondência numérica. A captura publicada preserva apenas a etapa técnica relevante; conta, URL e código temporário foram removidos.

## Limites dos testes

Não foram realizados logins nas contas dos colaboradores, leitura ou envio de mensagens em nome de terceiros, alterações de permissões para produzir evidências, remoção de registros DNS legados ou mudança da política DMARC com finalidade documental.

Esses limites refletem a decisão de validar o ambiente sem interferir na produção e sem utilizar credenciais ou dados de terceiros.