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
  - lab-confocal-images   → confocal / 2-photon microscopy
  - sfn-2024              → SfN Annual Meeting Chicago 2024
  - lab-life              → everyday lab life
  - fens-2024-rome        → FENS Forum Rome 2024

Cover image per gallery (optional):
  imageUrl: "galleries/lab-confocal-images/cover.jpg"
  Use icon-gallery.svg as placeholder: "icons/ui/icon-gallery.svg"

