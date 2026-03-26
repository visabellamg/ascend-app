\# Architecture Overview



Ascend is a React Native (Expo) mobile app backed by Supabase.



\## Stack

\- Frontend: React Native (Expo)

\- Backend: Supabase (Auth, Postgres, Storage, Edge Functions)

\- AI access: Supabase Edge Functions only



\## High-level flow

Mobile app → Supabase client → Edge Functions → AI provider



The mobile app never talks directly to AI providers.

