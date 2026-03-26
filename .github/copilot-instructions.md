# Copilot Workspace Instructions

## Mandatory Development Checklist
Before finalizing **any** change:
- [ ] `dotnet format SocOps/SocOps.csproj --verify-no-changes` — no lint violations
- [ ] `dotnet build SocOps/SocOps.csproj` — zero errors or warnings
- [ ] `dotnet test` — all tests pass (skip if no test project exists yet)

## Overview
**Soc Ops** — Blazor WebAssembly social bingo app (.NET 10). Build: `dotnet build SocOps/SocOps.csproj`. Run: `dotnet run --project SocOps/SocOps.csproj` (port 5166). See `README.md` and `workshop/*.md`.

## Project Layout
| Path | Purpose |
|------|---------|
| `SocOps/Components/` | UI components (`BingoBoard`, `BingoSquare`, modal/screens) |
| `SocOps/Services/` | State (`BingoGameService`) and logic (`BingoLogicService`) |
| `SocOps/Models/` | `GameState`, `BingoSquareData`, etc. |
| `SocOps/Data/` | Static questions |
| `SocOps/wwwroot/css/app.css` | Tailwind-like utility classes |

## Conventions
- C# naming: PascalCase for types/public members, camelCase for locals.
- `BingoGameService` owns all state; components subscribe to `OnStateChanged`.
- Business logic belongs in `Services/`, not in `.razor` markup.
- Reuse utility classes from `app.css`; add new ones there following existing patterns. See `.github/instructions/css-utilities.instructions.md` and `.github/instructions/frontend-design.instructions.md`.
- Never edit `SocOps/bin/` or `SocOps/obj/`.
