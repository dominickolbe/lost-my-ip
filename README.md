<p align="center">
  <p align="center">:raised_hands: :raised_hands: :raised_hands:</p>
  <h3 align="center">Lost My IP</h3>
  <p align="center">Get User Location based on the IP<p>
</p>

---

## Getting Started

### Prerequisites

This project is created and tested with the following setup:

- macOS Ventura Version 13.5
- node v18.16.0
- npm v9.6.5
- yarn v1.22.19

---

## supabase

Install the Supabase CLI with Homebrew

```bash
brew install supabase/tap/supabase
```

Update the Supabase CLI

```bash
brew install supabase/tap/supabase
```

If you have any Supabase containers running locally, remember to restart them after upgrading to use the new features.

```bash
npx supabase stop --no-backup
npx supabase start
```

Initialize Supabase inside your project using the command

```bash
supabase init
```

Link to your Remote Project using the command

```bash
supabase link --project-ref your-project-ref
```

Create an Edge Function

```bash
supabase functions new hello-world
```

Deploy a specific function

```bash
supabase functions deploy hello-world
```

Deploy all functions

```bash
supabase functions deploy
```

---

## LICENSE

Copyright © 2023 [Dominic Kolbe](https://dominickolbe.dk) :de:
