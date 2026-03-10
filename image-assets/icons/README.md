# Icons  —  currentColor SVGs (dark + light mode compatible)

All icons use currentColor. Style via CSS:

  .icon { width: 20px; height: 20px; color: var(--accent); }
  /* Dark mode: color inherits from parent */
  /* Light mode: same — no changes needed */

## Social icons  (icons/social/)

| File                    | Usage                        |
|-------------------------|------------------------------|
| icon-github.svg         | GitHub profile link          |
| icon-linkedin.svg       | LinkedIn profile link        |
| icon-bluesky.svg        | Bluesky profile link         |
| icon-twitter.svg        | Twitter / X profile link     |
| icon-orcid.svg          | ORCID researcher ID          |
| icon-email.svg          | Contact email link           |

## UI icons  (icons/ui/)

| File                    | Replaces emoji  | Usage                     |
|-------------------------|-----------------|---------------------------|
| icon-gallery.svg        | 🖼️ / 📸        | Gallery section header    |
| icon-post.svg           | 📄 / 📝        | Blog / publications list  |
| icon-location.svg       | 📍              | Location tag              |
| icon-publication.svg    | 📑              | Paper / preprint card     |
| icon-microscope.svg     | 🔬              | Nanoscopy / imaging       |
| icon-flask.svg          | ⚗️             | Lab / experimental        |
| icon-brain.svg          | 🧠              | Neuroscience sections     |
| icon-external.svg       | 🔗              | External link arrow       |

## Inline usage example (HTML)

  <img src="icons/ui/icon-location.svg" class="icon" alt="" aria-hidden="true">

## JS usage example (CONFIG)

  CONFIG.social = [
    { icon: "/image-assets/icons/social/icon-github.svg",   label: "GitHub",   url: "..." },
    { icon: "/image-assets/icons/social/icon-linkedin.svg", label: "LinkedIn", url: "..." },
    { icon: "/image-assets/icons/social/icon-bluesky.svg",  label: "Bluesky",  url: "..." },
    { icon: "/image-assets/icons/social/icon-twitter.svg",  label: "Twitter",  url: "..." },
    { icon: "/image-assets/icons/social/icon-orcid.svg",    label: "ORCID",    url: "..." },
    { icon: "/image-assets/icons/social/icon-email.svg",    label: "Email",    url: "..." },
  ]

