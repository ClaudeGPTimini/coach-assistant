# Coach-assistant next task (paste into Antigravity agent, model 3.8 high)

Repo: C:\Users\rmage\Documents\GitHub\coach-assistant
Live: https://claudegptimini.github.io/coach-assistant/
Current tip: master @ a0c8c2b (already on GitHub — no local-only backup found)

## Product goals
1. Google Login
2. Roles:
   - Head coach: full access + manage permissions
   - Assistant coach: view practice/game plans; optional toggle (set by head coach) to allow editing plans
   - Parents: view-only of CURRENT on-field positions (not planned/future lineups)
3. Feature overhaul consistent with those roles (do not break live-game swap/timer flows)

## Working rules
- Work in this folder only; keep a clean git history (small commits)
- Pull/status first; do not force-push
- Prefer incremental PR-ready commits on a feature branch (e.g. feature/roles-google-auth)
- After meaningful progress, summarize what changed and what still needs Rodney

Start by inspecting index.html architecture (auth, state, Firebase), then propose a short implementation plan and begin with Google auth + role model scaffolding unless blocked.
