# End-to-End 3D Learning workshop website

GitHub Pages publishes this repository from `main` at <https://e2e3d.github.io/>.

- `index.html` redirects to the current edition, `cvpr2027/`, preserving the query string and fragment.
- `cvpr2027/` contains the current workshop page. Unconfirmed program details remain marked as forthcoming.
- `archive/` lists past editions.
- `archive/cvpr2026/` preserves the 2026 homepage, poster session, and Rising Star Award pages.
- `iccv2025/` retains its existing archive URL.
- Root `poster.html` and `rising_star.html` redirect to their 2026 archive pages so existing links keep working.
- `data/` holds shared assets. Do not remove assets used by historical editions.

To preview locally, run `python3 -m http.server 8000` from the repository root and open <http://localhost:8000/>. No build step is required.
