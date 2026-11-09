PORTFOLIO FOLDER

index.html   Your whole site.
assets/      One image per screen. The page finds each one by its file name.

Vercel redeploys automatically every time something changes on the main branch.

TO SWAP IN A REAL SCREEN
1. Export the frame from Figma as PNG at 2x, 16:10 shape (e.g. 1280x800).
2. Convert at squoosh.app: WebP, about 1600px wide.
3. Rename it to the same name as the placeholder (e.g. dashboard.webp).
4. In GitHub: open the assets folder > Add file > Upload files > Commit changes.

Names are case-sensitive: dashboard.webp works, Dashboard.webp or dashboard.png does not.
Before uploading, check every screen for real customer names, emails or IDs.

SCREEN NAMES BY PROJECT
01 Three products, one spine   picker, detail, index, activity, before3
02 Unified API                 dashboard, connect, accounts, quickstart
03 Data Syncs                  real screens already in place (syncs-*.webp)
04 KFin DIGIX                  digix
05 SuperBeings                 review

Each placeholder image has a small "PLACEHOLDER · name.webp" tag in the
bottom-right corner so you can see which file is which on the live site.

DRAFT MODE
In the CONFIG block near the bottom of index.html, draft: true shows dashed
"TO ADD" boxes for what each case study still needs. Keep it false on the live site.

LINKS
LinkedIn and résumé links go in the same CONFIG block (linkedin: "...", resume: "...").
Their buttons stay hidden until you fill them in.
