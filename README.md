# Driver Profit

Isiklik telefoniäpp sõidutöö (Bolt, Forus, Uber, transfeerid) tegeliku teenistuse jälgimiseks pärast kütust, renti ja muid kulusid.

- Äpp: https://m8lder.github.io/driver-profit/
- Andmed: Supabase (projekt DriverTaxi), iga kasutaja näeb ainult oma kirjeid (RLS).
- AI (nädala ülevaade, häälsisestus, tšeki lugemine): Supabase Edge Function `dp-ai`, mis hoiab Anthropicu võtit serveris.

Selles repos pole salajasi võtmeid. `SB_KEY` on Supabase'i avalik (publishable) võti, mis on mõeldud brauserisse.
