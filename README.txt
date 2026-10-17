USCN BRANDS WEBSITE
Host: https://brands.uscn.uk/

Upload the contents of this folder to the subdomain web root.
No build step required. Each HTML file contains its own CSS.
The host must serve directory index.html files for trailing-slash URLs.

PAGES
/                         Homepage / brand directory
/axis/                    Axis profile and review list
/axis/post/q1659/              AXIS Q1659 review
/axis/post/p5635-e-mk-ii/       AXIS P5635-E Mk II review
/about/                   About USCN and review approach
/sitemap/                 Human-readable site map

SEARCH FILES
sitemap.xml               Absolute clean URLs on brands.uscn.uk
robots.txt                References the XML sitemap

All canonical and sitemap page URLs end in / without index.html.
Homepage navigation links may retain index.html as requested.
Subpage navigation links use directory paths ending in /.
The PTZ article contains no references to purchase history.
No deployment has been performed.

When replacing an older upload, remove obsolete brand directories
and assets from the host if they still exist there.

ROUTING UPDATE
/axis/index.html is the brand page and contains the links to both posts.
/axis/post/q1659/index.html is the Q1659 article.
/axis/post/p5635-e-mk-ii/index.html is the PTZ article.
All directories and URL paths use lowercase.
/axis/post/ is a normal article listing page with no automatic redirect.

When uploading this replacement, remove the obsolete /axis/q1659/ and
/axis/p5635-e-mk-ii/ directories. Ensure /axis/index.html is overwritten
with the brand index from this ZIP. If /axis/ still serves an old article,
check host redirects, default-document settings and cached content.

NAVIGATION FIX
All internal navigation uses explicit paths from the subdomain root.
No page contains an automatic redirect. Replace /axis/index.html with
the brand page from this package. Clear any hosting/CDN cache if an old
redirect remains. Server-side redirects are not configured by this ZIP.
