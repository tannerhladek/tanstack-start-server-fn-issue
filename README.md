Reproduction repository demonstrating JS loading/hydration issues when server functions (createServerFn) are placed in utils/supabase files instead of route files in TanStack Start.

Steps to reproduce:
1. Move fetchUser Server function from app/routes/__root.tsx to app/utils/supabase.ts
2. Client-side JS fails to load properly
3. Affects hydration and client-side navigation
