# Checklist reutilizável — Exchange e segurança de e-mail

> Modelo genérico. Não representa integralmente o que foi executado neste projeto.

## Exchange Online

- [ ] Definir caixas de usuário e caixas compartilhadas.
- [ ] Registrar aliases em inventário privado.
- [ ] Definir listas e grupos de distribuição.
- [ ] Revisar remetentes externos permitidos.
- [ ] Revisar delegações de envio.
- [ ] Revisar encaminhamentos.
- [ ] Definir política de retenção aplicável.

## DNS e autenticação

- [ ] Registrar TTL e estado anterior.
- [ ] Validar domínio por método autorizado.
- [ ] Configurar roteamento para o Exchange Online.
- [ ] Configurar SPF sem múltiplos registros conflitantes.
- [ ] Configurar descoberta automática.
- [ ] Publicar seletores DKIM.
- [ ] Habilitar DKIM no domínio personalizado.
- [ ] Publicar DMARC em política inicial apropriada.
- [ ] Planejar evolução segura da política DMARC.
- [ ] Validar resolução em mais de um resolvedor.
- [ ] Testar envio e recebimento autorizado.
- [ ] Registrar plano de reversão.
