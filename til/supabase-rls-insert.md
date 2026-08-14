# Insert without select under RLS

With INSERT-only policies, avoid `.insert().select()` — the returning clause needs SELECT permission.
