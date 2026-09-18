# BIZFLOW — production foundation

Real Next.js + Supabase foundation for BIZFLOW. Includes auth, business isolation with RLS, sales, expenses, inventory, invoice records, dashboard totals, and a server-only M-PESA integration boundary.

## Setup
1. Run `supabase/schema.sql` in the Supabase SQL Editor.
2. Add `NEXT_PUBLIC_SUPABASE_URL` and `NEXT_PUBLIC_SUPABASE_ANON_KEY` to Vercel.
3. Deploy from GitHub.
4. Add Daraja credentials only as server environment variables when the BIZFLOW collection account and callback are provisioned.

Never commit `.env` or secrets to GitHub.
