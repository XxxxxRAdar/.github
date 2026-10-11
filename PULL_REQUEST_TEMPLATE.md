## Wat verandert er
<!-- Eén alinea. Welke Radar of welk package, en waarom. -->

## Scope
- [ ] `apps/tenderradar`
- [ ] `apps/subsidieradar`
- [ ] `packages/*` (welke:)
- [ ] docs of tooling

## Controle
- [ ] `npm run typecheck && npm run test && npm run lint` groen
- [ ] Nieuwe migratie? Getest op lokale Supabase en opgenomen in `apps/<radar>/supabase/migrations`
- [ ] Nieuwe env-sleutel? Toegevoegd aan `.env.example` en in Vercel gezet
- [ ] Geen secrets in de diff
