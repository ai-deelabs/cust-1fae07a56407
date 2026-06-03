Build a landing page as the single file `v3.html`.

Brand:
DeeLabs Tour is a travel company that specializes in curated travel experiences, targeting clients looking for exploration and adventure. The desired website style is formal, easy to understand, and focuses on clear navigation, showcasing stunning imagery and essential information about travel packages in an inviting manner.

This is variant 3 of 3.
Express the brand's style through layout, whitespace, typography,
visual rhythm, and photo treatment — not just color. Avoid cliché
color associations (gold for luxury, blue for trust, green for health).

Set `<html lang="en">`. Add icons with `<i data-lucide="icon-name"></i>`.

Images — search with different keywords per section:
`bash /home/runner/work/web-builder-control/web-builder-control/core/tools/search-images.sh "keyword" [count]`
Use returned URLs in `<img>` with `?w=WIDTH&h=HEIGHT&fit=crop`.
Fallback: `https://picsum.photos/seed/{keyword}/{width}/{height}`.
