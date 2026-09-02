# 14 — Evidências visuais

## Conjunto publicado

O portfólio combina documentação textual, diagramas anonimizados e nove capturas tratadas. As imagens registram interfaces e verificações efetivamente utilizadas no projeto, sem reproduzir identificadores ou valores do ambiente.

## Fontes privadas utilizadas

A reconstrução técnica considerou telas de domínio e DNS, inventários administrativos, configurações do Exchange Online, sites e bibliotecas do SharePoint, páginas de permissões, versionamento, Padrões de Segurança, MFA, DKIM, DMARC e avaliação de postura.

Os arquivos originais permaneceram fora do repositório porque continham dados pessoais, domínio, URLs, identificadores, valores DNS, estrutura interna, postura de segurança ou metadados.

## Galeria de evidências

### Licenciamento do serviço

![Licenciamento anonimizado](../assets/evidence/licenciamento-business-basic-anonimizado.jpg)

A captura comprova a administração do produto utilizado. Quantidades, datas, usuários e endereços foram removidos.

### Site de equipe

![Site de equipe anonimizado](../assets/evidence/sharepoint-site-equipe-anonimizado.jpg)

A captura registra o tipo de site implantado. Nome, URL, armazenamento, administração e atividade foram removidos.

### Administração por grupos

![Grupos de segurança anonimizados](../assets/evidence/grupos-seguranca-anonimizado.jpg)

A captura registra o uso de grupos de segurança. Nomes, quantidades, endereços, datas e relações de acesso foram removidos ou substituídos por rótulos genéricos.

### Versionamento documental

![Versionamento anonimizado](../assets/evidence/sharepoint-versionamento-anonimizado.jpg)

A captura comprova o versionamento configurado. Nomes de bibliotecas e parâmetros numéricos sensíveis foram omitidos.

### Padrões de Segurança

![Padrões de Segurança anonimizados](../assets/evidence/entra-padroes-seguranca-anonimizado.jpg)

A captura registra o controle habilitado no Microsoft Entra ID. Organização, tenant e conta autenticada foram removidos.

### Fluxo de MFA

![MFA anonimizado](../assets/evidence/mfa-authenticator-anonimizado.jpg)

A captura registra a aprovação pelo Microsoft Authenticator durante o teste da conta administrativa. A conta e o desafio numérico foram removidos.

### Validação de registros DNS

![DNS anonimizado](../assets/evidence/dns-exchange-anonimizado.jpg)

A captura registra os tipos de registro e os indicadores de integridade. Domínio, provedor, nomes, destinos, valores e TTL foram removidos.

### DKIM

![DKIM anonimizado](../assets/evidence/dkim-anonimizado.jpg)

A captura comprova o domínio personalizado em estado válido e habilitado. Os domínios e dados auxiliares foram removidos.

### Consulta DMARC

![Consulta DMARC anonimizada](../assets/evidence/dmarc-consulta-anonimizado.jpg)

A captura registra o uso do `Resolve-DnsName` e a resposta TXT. Domínio, resolvedor, TTL e política foram removidos.

## Relação entre atividade e evidência

| Atividade documentada | Evidência apresentada |
|---|---|
| Arquitetura do ambiente | Diagrama Mermaid anonimizado |
| Organização documental | Diagrama com bibliotecas genéricas |
| Fluxo de e-mail | Diagrama conceitual |
| Segurança de identidade | Capturas tratadas e estado dos controles |
| Configuração de DNS | Capturas tratadas, sem valores reais |
| Testes | Matriz de validação com limitações |
| Permissões | Descrição do modelo por grupos |

## Evidências não incorporadas

Ficaram fora do repositório as capturas com listas de usuários, caixas, aliases, documentos, membros de listas, proprietários do site, permissões exclusivas, compartilhamento externo detalhado, pontuação de postura e painel original do provedor DNS.

A exclusão desses arquivos não reduz o escopo técnico documentado; ela preserva a confidencialidade e impede a associação do portfólio ao ambiente real.