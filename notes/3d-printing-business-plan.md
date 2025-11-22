# 3D Printing Business Plan

## Budget & Purchasing Notes

- The budget is an estimate; buying the base P1S printer and adding the AMS later can save about $220.

## Timeline & Purchasing Plan (Detailed)

### 1. Black Friday (Nov 28, 2025)
- **Action**: Purchase P1S AMS 2 Pro Combo (or base P1S if X1C unavailable).
- **Order**: Filament colours and essential tools.
- **Prep**: Clear a workspace in the garage.

### 2. Dec 1 – 10
- **Tasks**:
    - Unbox and assemble printer.
    - Install AMS.
    - Run first-layer calibration; print and refine Pokémon test models.
    - Calibrate colours.
    - Install ventilation fan and set up dry storage.
    - Start developing Replit app (basic UI and STL generator).

### 3. Dec 11 – 18
- **Tasks**:
    - Finish Replit app features (colour previews, order logging).
    - Create branding and listings; photograph test prints.
    - Order any missing supplies (e.g., packaging).
    - Prepare Etsy shop policies and pricing.

### 4. Dec 19 – Jan 4
- **Pause**: Family vacation – no production.
- **Continue**: Monitor messages and gather feedback from test prints.

### 5. Jan 5 – 11
- **Tasks**:
    - Return and final calibrations.
    - Upload product listings to Etsy; start taking orders.
    - Integrate Google Sheets P&L calculator; begin first fulfilments.

### 6. Rest of January
- **Iterate**:
    - Iterate on designs, track costs and profits, and adjust pricing.
    - Collect customer feedback and plan new products.

---

## Integration Plan for GitHub Repository

1. **Add a notes folder** to the repository to separate high‑level planning documents from app code. Store architecture docs or business plans in `/docs` or `/notes`.

2. **Commit the business plan file**:
    - Download prepared plan file.
    - Rename to something descriptive like `3d-printing-business-plan.md` and add to the new `notes` folder.
    - Commit addition on a new branch (e.g., `notes/add-business-plan`) and open a pull request for review.

3. **App-Development README update**:
    - After merging, update `app-development/README.md` with:
      ```
      See [../notes/3d-printing-business-plan.md](../notes/3d-printing-business-plan.md) for the overall business plan.
      ```

4. **Document an upkeep process**:
    - Create `notes/upkeep.md` detailing collaboration (branching, PRs, commit messages, issue tracking).
    - Include naming conventions for notes (e.g., `notes/filament-suppliers.md`, `notes/sales-analysis-Q1.md`).

5. **Ongoing maintenance**:
    - When prompted, update Markdown as needed; copy changes, commit, and push.
    - All contributors (human or AI) should follow branch‑and‑PR procedure to avoid conflicts.
    - Periodically review the notes folder to archive/delete outdated materials, and link new insights from the main plan.

---

With this structure, the repository will become both the codebase and living documentation for the business. Team members and AIs can find and update relevant notes without interfering with app code.