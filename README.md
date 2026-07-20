# SGP Lenfox — Piloto de publicación web (REQ-17)

Piloto de las Fases 6-7 del plan SP-06-07 (Migración a Supabase y Publicación como App
Web): valida el circuito completo — supabase-js real + Supabase Auth + Row Level Security
+ despliegue en GitHub Pages — usando REQ-17 (Panel de Administración) como caso de prueba
antes de acometer REQ-10.

No es la app de producción: usa email/contraseña de Supabase Auth (no la SSO Azure/Entra ID
prevista para producción) y GitHub Pages en vez de Cloudflare Pages + dominio corporativo.
