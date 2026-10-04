# Siamlekbot — to do

Not published: `_config.yml` tells GitHub Pages to leave this file out of siamlekbot.com.
The repo itself is public on GitHub, so keep secrets, prices and client details out of here.

## SEO and structured data (planned 4 Oct 2026, not started)

- [ ] **Header tags:** canonical link to `https://siamlekbot.com/`, Open Graph and Twitter
      card tags (title, description, image), favicon (lotus mark).
- [ ] **Share image:** 1200×630, the hero collage with the SiamlekBot logo, in `img/`.
- [ ] **JSON-LD:** `Organization` (name, url, logo, email, sameAs) + `WebSite` (site name),
      optionally an `ItemList` of the four products. No `LocalBusiness` unless a Google
      Business Profile (service-area) is set up, since it expects an address.
- [ ] **`robots.txt`** (allow all, point to sitemap) and **`sitemap.xml`**.
- [ ] **Google Search Console:** add siamlekbot.com, verify (DNS TXT or meta tag), submit the
      sitemap. Then import into Bing Webmaster Tools.
- [ ] **Later, for wider searches:** one page per case study (`/work/thai-kitchen`, etc.).
- [ ] **Backlinks:** a small "Site by SiamlekBot" credit on public, indexed pages (e.g. the
      RealPattayaBars footer, the public Thai Kitchen footer). The Thai Kitchen *admin* credit
      gives no SEO value because admin pages are noindex.

## Parked

- [ ] **BarberBot back online** (Matt: "not yet"). When it is, swap its "Ask for a demo"
      button for a live link and change "Demo on request" to "Live". Steps are in
      barberbot-web's `handoff.md.txt`.
