# Photo Galleries

Each subfolder = a gallery slug. Images loaded via GitHub API.

Set in CONFIG.github:
  CONFIG.github = {
    owner: "your-username",
    repo:  "your-repo",
    branch: "main",
    imagesFolder: "galleries"
  }

Gallery slugs:
  - lab-images   → confocal / 2-photon microscopy
  - lab-life              → everyday lab life
  - fens-2024-rome        → FENS Forum Vienna 2024

Cover image per gallery (optional):
  imageUrl: "/image-assets/galleries/lab-confocal-images/cover.jpg"
  Use icon-gallery.svg as placeholder: "/image-assets/icons/ui/icon-gallery.svg"

