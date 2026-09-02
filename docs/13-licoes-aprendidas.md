# 13 — Lições aprendidas

## Precisão do escopo

Implantação, transição e migração de dados são atividades diferentes. Documentar corretamente essa distinção evita superestimar a entrega e torna as limitações compreensíveis.

## Administração por grupos

Associar funções a grupos reduz o esforço de manutenção e favorece revisões de acesso. Ainda assim, exceções e associações devem ser auditadas periodicamente em documentação privada.

## DNS em produção

Um registro aparentemente antigo pode atender uma dependência não documentada. A ausência de certeza não deve ser resolvida por exclusão imediata. Inventário, backup, aprovação, janela de mudança e rollback são partes da solução técnica.

## Validação responsável

Comprovar um serviço não exige acessar dados pessoais de terceiros. Estados administrativos, contas de teste e testes autorizados devem ser priorizados.

## Segurança de identidade

Uma linha de base nativa oferece proteção inicial, mas não substitui governança contínua, revisão de privilégios e licenciamento adequado para necessidades avançadas.

## Evidência e confidencialidade

Capturas administrativas contêm mais informações do que o elemento que se deseja provar. Texto, tabelas genéricas e diagramas são frequentemente evidências de portfólio mais seguras do que imagens reais.

## Segurança de e-mail

SPF, DKIM e DMARC são controles complementares. A existência dos registros deve ser acompanhada por revisão e maturação controlada, sem representar a configuração inicial como proteção absoluta.
