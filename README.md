# GamePermits v2

2-oji GamePermits versija su Supabase duomenų baze ir QR kodais.

## Leidimai
Žvejybos leidimas; Medžioklės leidimas; Statybos leidimas; Verslinės žvejybos leidimas; Pavojingų medžiagų pervežimas.

## Regionai
Klaipėdos regionas; Vilniaus regionas; Kauno regionas.

## Paleidimas
1. Supabase susikurk projektą.
2. Supabase SQL Editor paleisk `supabase/schema.sql`.
3. Supabase Settings → API pasiimk Project URL ir anon/public key.
4. Sukurk `.env.local` pagal `.env.example`.
5. Paleisk `npm install`, tada `npm run dev`.
6. Vercel įkeliant projektą Environment Variables įrašyk `VITE_SUPABASE_URL` ir `VITE_SUPABASE_ANON_KEY`.

Ši versija skirta žaidimui. Vieša INSERT politika leidžia lankytojams kurti virtualius leidimus. Vėliau galima pridėti prisijungimą ir administratoriaus patvirtinimą.
