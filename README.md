# SGP-Lenfox — Piloto de publicación web

Piloto de las Fases 6-7 del plan SP-06-07 (Migración a Supabase y Publicación como App
Web): supabase-js real + Supabase Auth + Row Level Security + despliegue en GitHub Pages.

- `/` — Backlog Manager (REQ-10): Mis Tareas, Mis Proyectos, Cronograma, Vacaciones del equipo.
- `/admin/` — Panel de Administración (REQ-17): Usuarios, Proyectos, Time-Line, Vacaciones, Sprints.

Ambas apps comparten el mismo proyecto de Supabase y la misma sesión de Auth (mismo dominio de
GitHub Pages). Las personas marcadas como Administrador ven un conmutador entre ambas al hacer
clic en el avatar de la cabecera.

No es la app de producción: usa email/contraseña de Supabase Auth (no la SSO Azure/Entra ID
prevista para producción) y GitHub Pages en vez de Cloudflare Pages + dominio corporativo.
