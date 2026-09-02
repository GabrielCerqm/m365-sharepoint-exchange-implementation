# 13 — Análise técnica do projeto

## Precisão do escopo

O projeto reforçou a distinção entre implantação, transição de serviço e migração de dados. O ambiente recebeu novos serviços, mas os históricos de e-mail e documentos permaneceram fora do escopo.

## Administração por grupos

A associação das funções a grupos reduziu a dependência de permissões individuais e tornou a estrutura de acesso mais compreensível. As exceções reais permaneceram na documentação privada.

## DNS em produção

A presença de registros legados sem dependências integralmente inventariadas levou à decisão de preservá-los. A continuidade do ambiente teve prioridade sobre uma limpeza sem garantia de reversão.

## Validação responsável

A comprovação técnica foi obtida por estados administrativos, consultas DNS e uma conta administrativa autorizada. Não houve necessidade de acessar contas ou conteúdo dos colaboradores.

## Segurança de identidade

Os Padrões de Segurança forneceram a linha de base compatível com o licenciamento disponível. O projeto não atribui ao ambiente controles avançados que não foram comprovados.

## Evidência e confidencialidade

As capturas administrativas exigiram tratamento além de simples recorte. A versão de portfólio combinou imagens anonimizadas, tabelas e diagramas para demonstrar o trabalho sem reproduzir o ambiente.

## Segurança de e-mail

SPF, DKIM e DMARC foram tratados como controles complementares. A política inicial observada foi documentada sem ser apresentada como proteção absoluta.