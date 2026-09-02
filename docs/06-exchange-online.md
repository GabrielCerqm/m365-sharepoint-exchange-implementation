# 06 — Exchange Online

## Implantação

O Exchange Online foi utilizado como serviço de e-mail corporativo. Foram provisionadas caixas de usuário e o domínio personalizado foi associado à operação de e-mail.

## Objetos configurados

- Caixas do tipo usuário.
- Endereços alternativos associados a caixas existentes.
- Lista de distribuição para comunicação funcional.

O inventário de aliases, suas caixas correspondentes, os membros e o proprietário da lista permanecem em documentação privada. No escopo técnico, a lista de distribuição foi registrada separadamente de aliases e caixas compartilhadas.

## Objetos não configurados

- Caixas compartilhadas.
- Permissão “Enviar como”.
- Permissão “Enviar em nome de”.
- Encaminhamentos administrativos.

## Domínios

O domínio personalizado foi validado e utilizado para comunicação corporativa. O domínio técnico criado automaticamente pelo Microsoft 365 permaneceu como componente do tenant, sem uso como domínio corporativo principal.

A ausência de chaves DKIM próprias no domínio técnico automático não foi tratada como falha do domínio personalizado.

## Histórico de mensagens

O histórico mantido no provedor anterior não foi migrado. A decisão ocorreu porque esses dados não foram considerados relevantes para o novo ambiente. Assim, a entrega é descrita como implantação e transição do serviço, não como migração de conteúdo IMAP ou PST.

## Validação e privacidade

Não foram acessadas caixas de colaboradores para realizar testes interativos. O estado das caixas foi verificado administrativamente e o ambiente foi informado como operacional pelo responsável.

Não há evidência suficiente para afirmar configuração individual de Outlook desktop ou dispositivos móveis.
