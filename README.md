my-book/
│
├── docs/                       # Markdown-only book (GitHub Pages)
│   ├── intro.md
│   ├── chapter-1.md
│   └── ...
│
├── docusaurus/                 # Full Docusaurus site
│   ├── docusaurus.config.js
│   ├── sidebars.js
│   ├── package.json
│   ├── src/
│   └── static/
│
├── nextjs/                     # Next.js + MDX version of the book
│   ├── app/
│   ├── mdx-content/
│   ├── package.json
│   ├── next.config.js
│   └── ...
│
├── speckit/                    # Speckit Plus generated files
│   ├── .speckit/
│   ├── spec/
│   ├── plan/
│   ├── constitution/
│   └── output/
│
├── scripts/
│   ├── publish-docusaurus.sh
│   ├── publish-markdown.sh
│   ├── publish-nextjs.sh
│   └── publish-all.sh
│
├── .github/
│   └── workflows/
│       ├── deploy-docusaurus.yml
│       ├── deploy-markdown.yml
│       └── deploy-nextjs.yml
│
├── README.md
└── LICENSE
