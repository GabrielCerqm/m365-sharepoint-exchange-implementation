# Política de segurança do repositório

## Finalidade

Este repositório contém apenas documentação pública ou preparada para futura publicação. Ele não deve ser utilizado como repositório de configuração, inventário, backup ou evidência bruta de ambientes reais.

## Conteúdo proibido

Não envie ao Git:

- senhas, tokens, cookies, códigos MFA ou chaves de recuperação;
- certificados, chaves privadas, secrets ou arquivos de ambiente;
- Tenant IDs, Client IDs, Object IDs ou identificadores equivalentes;
- nomes, e-mails, telefones ou outros dados pessoais;
- domínios, IPs, hostnames ou URLs reais do cliente;
- exportações de usuários, caixas, grupos, licenças ou auditoria;
- arquivos PST, backups, dumps, logs ou relatórios administrativos;
- registros DNS reais;
- matrizes reais de permissões;
- capturas administrativas sem anonimização;
- documentos originais do cliente.

## Evidências

Evidências devem ser avaliadas individualmente. Recortar uma imagem ou cobrir parte do conteúdo não garante anonimização adequada. Sempre considere barra de endereço, conta autenticada, tenant, URLs, avatares, horários, nomes ao fundo e metadados.

Quando uma imagem não for indispensável, substitua-a por texto ou diagrama genérico.

## Resposta a exposição acidental

Se um segredo ou dado real for enviado ao repositório:

1. Mantenha ou torne o repositório privado.
2. Revogue imediatamente o segredo ou credencial.
3. Avalie o impacto e comunique o responsável pelo ambiente.
4. Remova o dado do conteúdo atual.
5. Limpe o histórico do Git com ferramenta apropriada.
6. Force a atualização remota somente após revisão e autorização.
7. Considere o dado comprometido mesmo depois da remoção visual.

Apagar o arquivo no commit mais recente não remove o conteúdo do histórico.

## Comunicação de problema

Não abra uma issue pública contendo o dado encontrado. Entre em contato privadamente com o proprietário do repositório e descreva somente o necessário para localizar e corrigir a exposição.

## Separação documental

A documentação privada deve utilizar armazenamento controlado, permissões restritas e política de retenção. Ela não deve ser mantida em branches, releases, issues, pull requests ou artefatos deste repositório.
