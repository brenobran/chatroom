# Entrega e validação

O guia ChatRoom descreve 15 etapas e espera 32 testes automatizados (20 do app e 12 do
banco), além de teste manual do Realtime com duas sessões simultâneas.

Checklist antes da entrega:
- [ ] Criar e configurar projeto no Supabase.
- [ ] Executar `supabase/schema.sql`.
- [ ] Preencher `.env` local (não enviar ao Git).
- [ ] `npm install` concluído.
- [ ] `npm run typecheck` sem erros.
- [ ] `npm test` com os testes aprovados.
- [ ] Testar cadastro, login, salas, envio e exclusão da própria mensagem.
- [ ] Testar presença e indicador de digitação em dois aparelhos/sessões.
- [ ] Publicar no GitHub com `.env` excluído.
