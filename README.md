# turnos-cron-trigger

Repositorio público que solo contiene un workflow de GitHub Actions. Su único
propósito es disparar, cada 30 minutos, dos endpoints HTTP públicos de la app
`productividad-turnos` (hosteada en Vercel) para ejecutar sus tareas de cron
(recordatorios y cierre de mes).

No contiene código de la aplicación ni datos. La autenticación hacia los
endpoints se hace con el secreto `CRON_SECRET` configurado como GitHub Secret
en este repo (no está en el código).

Este repo es público únicamente para aprovechar los minutos ilimitados de
GitHub Actions en repos públicos, ya que el repo principal es privado y el
plan gratuito de Actions tiene un límite mensual de minutos.
