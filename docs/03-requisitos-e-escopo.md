# 03 — Requisitos e escopo

## Requisitos funcionais

| Área | Requisito |
|---|---|
| Identidade | Administrar usuários em um diretório corporativo centralizado |
| Licenciamento | Atribuir licenças compatíveis com e-mail e colaboração web |
| E-mail | Disponibilizar caixas corporativas no Exchange Online |
| Comunicação | Permitir endereço funcional para distribuição de mensagens |
| Documentos | Criar um site de equipe privado e bibliotecas funcionais |
| Acesso | Associar permissões a grupos baseados em função |
| Segurança | Exigir autenticação multifator por mecanismo nativo disponível |
| Domínio | Validar propriedade e configurar roteamento e autenticação de e-mail |
| Operação | Permitir administração e suporte posteriores à implantação |

## Escopo executado

- Preparação administrativa do tenant.
- Validação de domínio personalizado.
- Provisionamento de identidades, licenças e caixas de usuário.
- Configuração de aliases sem exposição de seus mapeamentos.
- Criação de lista de distribuição funcional.
- Configuração dos registros necessários ao Exchange Online.
- Criação do site de equipe e das bibliotecas funcionais.
- Criação e associação de grupos de segurança.
- Padronização do versionamento das bibliotecas.
- Habilitação dos Padrões de Segurança.
- Validação de MFA em conta administrativa autorizada.
- Configuração e validação de SPF, DKIM e DMARC.
- Revisão da postura por ferramenta nativa do Microsoft 365.
- Suporte administrativo contínuo.

## Itens não executados

- Migração do histórico do provedor de e-mail anterior.
- Migração de arquivos para o SharePoint.
- Criação de caixas compartilhadas.
- Delegações de envio em caixas.
- Encaminhamentos de e-mail.
- Configuração de dispositivos móveis.
- Treinamento formal.

## Itens não confirmados

- Configuração individual do Outlook para desktop.
- Implantação específica do OneDrive para usuários.
- Teste formal de envio e recebimento em cada caixa.
- Teste negativo de acesso com todas as funções.
- Valor atualizado do Secure Score.
