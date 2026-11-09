PORTFOLIO FOLDER

index.html   Your whole site.
assets/      One image per screen. The page finds each one by its file name.

Upload this whole folder's contents to your GitHub repository
(index.html and the assets folder). Vercel redeploys automatically.

TO SWAP IN A REAL SCREEN
1. Export the frame from Figma as PNG at 2x, 16:10 shape (e.g. 1280x800).
2. Convert at squoosh.app: WebP, about 1600px wide.
3. Rename it to the same name as the placeholder (e.g. syncs.webp).
4. In GitHub: open the assets folder > Add file > Upload files > Commit changes.

Names are case-sensitive: syncs.webp works, Syncs.webp or syncs.png does not.

SCREEN NAMES BY PROJECT
01 Three products, one spine   picker, detail, index, activity, before3
02 Unified API                 dashboard, connect, accounts, quickstart
03 Logs, syncs & alerts        syncs (also uses activity, accounts)
04 KFin DIGIX                  digix
05 SuperBeings                 review

Each placeholder image has a small "PLACEHOLDER · name.webp" tag in the
bottom-right corner so you can see which file is which on the live site.

LINKS
LinkedIn and résumé links go in the CONFIG block near the bottom of
index.html (linkedin: "...", resume: "..."). Their buttons stay hidden
until you fill them in.
