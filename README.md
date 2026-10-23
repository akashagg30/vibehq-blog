# AI Tools & Software Reviews - Content Package

Generated: August 23, 2026
**Last completed / verified: 2026-09-20 (automated cron run)**

Location: `~/akash/content/ai-tools/`

## Article Summary

| # | Filename | Topic | Body words |
|---|----------|-------|-----------|
| 1 | 01-best-ai-writing-tools-2026.md | Best AI Writing Tools | 1,421 |
| 2 | 02-ai-image-generators-compared.md | AI Image Generators Compared | 1,662 |
| 3 | 03-ai-video-editing-tools.md | AI Video Editing Tools | 1,652 |
| 4 | 04-ai-chatbots-business.md | AI Chatbots for Business | 1,486 |
| 5 | 05-ai-design-tools.md | AI Design Tools | 1,517 |
| 6 | 06-ai-coding-assistants.md | AI Coding Assistants | 1,786 |
| 7 | 07-ai-seo-tools.md | AI SEO Tools | 1,619 |
| 8 | 08-ai-productivity-tools.md | AI Productivity Tools | 1,626 |
| 9 | 09-ai-music-creation-tools.md | AI Music Creation Tools | 1,897 |
| 10 | 10-ai-voice-cloning-tools.md | AI Voice Cloning Tools | 1,246 |

**Total: 10 articles | 15,912 body words** (excludes YAML frontmatter)

## Structural completeness — measured, not aspirational

Verified by script on 2026-09-20 (per-file, heading and prose matched independently):

| Article | Body words | Comparison table | FAQ section | Verdict / conclusion |
|---|---|---|---|---|
| 01 best-ai-writing-tools | 1,421 | ✅ | ✅ | ✅ |
| 02 ai-image-generators | 1,662 | ✅ | ✅ | ✅ |
| 03 ai-video-editing | 1,652 | ✅ | ✅ | ✅ |
| 04 ai-chatbots-business | 1,486 | ✅ | ✅ | ✅ |
| 05 ai-design-tools | 1,517 | ✅ | ✅ | ✅ |
| 06 ai-coding-assistants | 1,786 | ✅ | ✅ | ✅ |
| 07 ai-seo-tools | 1,619 | ✅ | ✅ | ✅ |
| 08 ai-productivity-tools | 1,626 | ✅ | ✅ | ✅ |
| 09 ai-music-creation-tools | 1,897 | ✅ | ✅ | ✅ |
| 10 ai-voice-cloning-tools | 1,246 | ✅ | ✅ | ✅ |

All 10 articles have:
- ✅ SEO-optimised H1 containing the primary keyword
- ✅ `meta_description` in YAML frontmatter (10 of 10)
- ✅ Introduction with Indian market context (INR pricing, local examples)
- ✅ 2026 reference points
- ✅ Comparison table, FAQ section, and a verdict/conclusion close
- ✅ No truncated sections — every article ends on a complete sentence

## Known gaps (do **not** claim otherwise in marketing copy)

- ❌ **0 external links across all 10 articles** — no affiliate links, no product links.
  This blocks affiliate revenue entirely and needs affiliate accounts.
- ⚠️ **0 internal links inside the `.md` sources** — the cluster now exists in the generated HTML
  (3 relative "Related reading" links per page, built 2026-09-20), so the sources stay clean and
  links cannot be born broken regardless of the publish path.
- ❌ **0 images / featured images.**
- ❌ Length now 1,246–1,897 words; still at/just below the
  1,800–2,500 band competitive "best X tools 2026" SERP terms typically require.
- ❌ Unpublished **on `vibehq.in`** — `https://vibehq.in/blog` still returns 404 (domain is
  Porkbun-parked). **The site itself IS published** on Render since 2026-10-23 16:05 IST:
  `https://vibehq-blog.onrender.com/` → 200, byte-identical to `site/`.

## Completion log

**2026-09-20 (cron run).** Structural audit found the package was not as complete as
previously reported: **7 of 10 articles were truncated mid-sentence** (02, 03, 04, 05, 06, 07,
09) — the tail of each generation had been cut off by an output-length limit, leaving broken
FINAL sentences and missing FAQ/verdict sections. Also found: article 10 carried a
**false affiliate disclosure** ("this article contains affiliate links") when the package
contains zero links of any kind, and article 08 had a leftover editor artifact
("(Word count: approximately 1,500)").

Fixed in this run, no model calls and no external services:

- Completed the truncated tail of all 7 affected articles; every article now ends on a
  complete sentence.
- Added the missing FAQ sections (03, 05, 06) and verdict/close sections (02, 03, 05, 06).
- Added the missing comparison table to 09 and a decision matrix to 05.
- Corrected article 10's disclosure to a truthful statement.
- Removed the artifact from 08.
- Body word count rose from ~12,714 to 15,912.

Reproducible script: `~/akash/company/scripts/fix-content-articles.py`

## Indian Market Coverage

- INR pricing alongside USD
- Indian companies and startups mentioned
- Local language support discussed
- Indian success stories and examples
- Regional market context

## Usage Recommendations

1. **SEO Optimisation**: Add alt text to any images
2. **Internal Linking**: Link between related articles (after the URL scheme is fixed)
3. **Affiliate Links**: Add relevant affiliate CTAs (needs affiliate accounts)
4. **Social Sharing**: Create snippets from each article
5. **Email Marketing**: Use as newsletter content

## Content Quality

- Natural keyword density (1-2%)
- Mobile-friendly formatting
- Scannable structure with headers
- Professional yet accessible tone
- Updated for 2026 market conditions

## Deployable static site — **built and LIVE** (built 2026-09-20; deployed 2026-10-23)

`site/` in this directory is a **generated, self-contained static site** for the 10 articles.
It is now **committed** (force-added in `00e8ea3`; it was previously listed in
`.git/info/exclude`) because Render builds from the repo and needs it present. Regenerate it any
time:

```bash
~/.venvs/blog/bin/python ~/akash/company/scripts/build-blog-site.py --base-url https://<host>/<path>
~/.venvs/blog/bin/python ~/akash/company/scripts/verify-blog-site.py   # 0 = all checks pass
~/.venvs/blog/bin/python -m http.server 8099 --bind 127.0.0.1          # preview from site/
```

Contents: `index.html`, 10 article pages, `sitemap.xml`, `feed.xml` (RSS), `robots.txt`, `style.css`
(no external CDN assets). Each page has title/meta description/canonical/OG tags, Article JSON-LD,
and a **"Related reading" block with 3 relative internal links** — the topical cluster that was
previously deferred. All internal links are relative, so the site works at **any** base path
(`/`, `/blog`, a subdomain); only canonical/OG/sitemap URLs depend on `--base-url`.

Verified 2026-09-20: `verify-blog-site.py` passes (links resolve, no leaked markdown, FAQ +
verdict + comparison table on every page, 30 internal link edges, sitemap 11 URLs, feed 10 items),
and all pages served 200 over a local HTTP server.

**Blocker on going live:** ~~publishing needs approval (proposal D2a)~~ **approval given and
executed 2026-10-23** — see below. The remaining gap is the **domain**: `vibehq.in` is
Porkbun-parked (`pixie.porkbun.com`, 207.207.210.x) and does **not** point at the Render
workspace, so the live site is on an `*.onrender.com` URL. Repointing DNS is Akash's registrar
login (L3), not an agent task.

**LIVE (2026-10-23 16:05 IST).** Render **static site** `vibehq-blog`
(`srv-dbdjd52vcj2c73fvr770`, dashboard `…/static/srv-dbdjd52vcj2c73fvr770`), repo
`github.com/akashagg30/vibehq-blog`, branch `main`, **publishPath `site`**, auto-deploy on
commit. Deploy `dep-dbdjgnrncjis73adsqa0` → `live`. Reached at
**https://vibehq-blog.onrender.com/**. Verified from outside: root + article pages + `sitemap.xml`
+ `feed.xml` + `robots.txt` + `style.css` all **200** and **byte-identical to `site/`**; an
unknown path returns `404.html` with status **404**. First build **failed** (`Publish directory
site does not exist`) because `site/` was gitignored — fixed by force-adding the 17 built files
in commit `00e8ea3`.

**Revenue is still ₹0**: the 10 articles carry **0 external links** (no affiliate/CTA URLs), so a
live URL changes distribution, not monetisation. Monetisation needs affiliate accounts or a
product to sell — neither exists.

## Next Steps

- [x] Add `meta_description` frontmatter to all articles (done 2026-09-12)
- [x] Complete truncated articles; add missing FAQ/verdict/table sections (done 2026-09-20)
- [x] Remove false affiliate disclosure from article 10 (done 2026-09-20)
- [ ] **Add affiliate links** (blocks all revenue — needs affiliate accounts)
- [ ] Add featured images to each article
- [x] Set up internal linking structure — every generated page carries 3 relative "Related reading" links (2026-09-20)
- [ ] Create social media snippets
- [ ] Schedule publication dates
- [ ] Deploy the built `site/` to a working host (still 404 at `vibehq.in/blog`; needs D2a approval + a host that serves the domain)
