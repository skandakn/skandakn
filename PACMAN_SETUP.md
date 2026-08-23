# One-time setup for the Pac-Man contribution graph

The README already has the Pac-Man image embedded — it just needs this Action running once in your `skandakn/skandakn` repo to generate the file it points to.

1. In your `skandakn/skandakn` repo, create the folder path `.github/workflows/` if it doesn't exist.
2. Add the file **pacman.yml** (provided) into `.github/workflows/pacman.yml`.
3. Go to **Settings → Actions → General → Workflow permissions** → select **Read and write permissions** → Save.
   (Without this, the Action can't push the generated SVG back to your repo.)
4. Go to the **Actions** tab → select **Generate Pac-Man Contribution Graph** → click **Run workflow**.
5. Wait ~1 minute. It will create a new `output` branch containing the SVG.
6. Refresh your profile page — Pac-Man should now be eating your contribution graph.

After this, it re-runs automatically every 24 hours to stay current with new contributions.
