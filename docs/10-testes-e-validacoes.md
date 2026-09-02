# 10 — Testes e validações

## Critério de documentação

Somente verificações sustentadas por declaração do responsável, estado administrativo ou evidência técnica são tratadas como concluídas. Testes não registrados permanecem como não confirmados.

## Matriz de validação do projeto

| Verificação | Estado | Método ou evidência | Limitação |
|---|---|---|---|
| Domínio personalizado aceito pelo Microsoft 365 | Confirmado | Estado administrativo | Identificador real omitido |
| Registros principais de e-mail | Confirmado | Integridade exibida no centro administrativo | Valores reais omitidos |
| Resolução de DMARC | Confirmado | Consulta DNS | Política exata omitida |
| DKIM no domínio personalizado | Confirmado | Estado válido e habilitado | Seletores omitidos |
| Caixas de usuário provisionadas | Confirmado | Inventário administrativo privado | Não houve acesso às caixas |
| Lista de distribuição funcional | Confirmado por declaração e configuração | Estado administrativo | Membros e endereço omitidos |
| Site de equipe privado | Confirmado | Estado administrativo | URL e nome omitidos |
| Grupos de segurança existentes | Confirmado | Inventário administrativo privado | Estrutura real omitida |
| Permissões por grupos | Confirmado | Inspeção administrativa | Matriz real omitida |
| Versionamento nas bibliotecas | Confirmado | Amostra visual e declaração do responsável | Um print representa a configuração padronizada |
| Padrões de Segurança | Confirmado | Estado no Microsoft Entra ID | Políticas detalhadas não exportadas |
| MFA administrativo | Confirmado | Login autorizado com Microsoft Authenticator | Somente a conta administrativa foi testada |
| MFA individual dos colaboradores | Não validado interativamente | Restrição de privacidade | Não foram utilizadas credenciais de terceiros |
| Envio e recebimento em cada caixa | Não confirmado formalmente | Ambiente informado como operacional | Sem acesso individual às caixas |
| Acesso negativo por todas as funções | Não confirmado formalmente | Configuração inspecionada | Sem teste com cada perfil |
| Secure Score atualizado | Não confirmado | Evidência atualizada válida não disponível | Valor não incorporado |

## Validação de MFA

O teste autorizado confirmou o fluxo de senha seguido por Microsoft Authenticator com correspondência numérica. A captura original contém conta, URL e código temporário e, portanto, não pertence ao repositório.

## Testes que não devem ser simulados retroativamente

- Login nas contas de colaboradores.
- Leitura ou envio de mensagens em nome de terceiros.
- Alterações de permissões apenas para produzir evidência.
- Remoção de registros DNS legados em produção.
- Mudança da política DMARC apenas para elevar pontuação.

## Validação futura recomendada

Qualquer validação adicional deve utilizar conta de teste autorizada, janela de mudança, critérios de sucesso e plano de reversão. Os resultados devem ser registrados sem dados identificáveis.
