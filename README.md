# Stage Designer — CFC Production

Lay out lights and LED panels on CFC's stages (Auditorium, Shed) in 2D. It checks for over-allocated stock, DMX address clashes and truss loads.

- Front end: `index.html` (one static file, served by GitHub Pages).
- Back end: Supabase project `cfc-timesheets`, schema `stage`. All access goes through the `public.stage_api` RPC.
- Login: the crew's timesheet link and PIN. Access is managed in `stage.members`.

Coordinates are in metres. x runs left (−) to right (+) as seen from the audience, y runs upstage (+), and z is height above the room floor.
