# Configuração do Supabase

1. Crie um projeto no Supabase (região South America/São Paulo, se disponível).
2. Abra **SQL Editor** e execute todo o conteúdo de `supabase/schema.sql`.
3. Em **Database → Replication**, confirme que `public.messages` está habilitada para Realtime.
4. Em **Project Settings → API**, copie a Project URL e a chave pública (anon/publishable).
5. Copie `.env.example` para `.env` e preencha:
   - `EXPO_PUBLIC_SUPABASE_URL`
   - `EXPO_PUBLIC_SUPABASE_KEY`
6. Reinicie o Expo com `npx expo start -c`.

Nunca coloque a `service_role` key no aplicativo. O app deve usar somente a chave pública,
com a segurança garantida pelas políticas RLS do banco.
