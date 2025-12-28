/anonymous-mailbox
├── /apps
│   ├── /frontend          # Vite + React (UI/UX teammate)
│   │   ├── /src
│   │   │   ├── /components
│   │   │   ├── /hooks
│   │   │   ├── /pages
│   │   │   └── api.js      # Axios/Fetch config to talk to backend
│   │   └── vite.config.js
│   │
│   └── /backend           # Express.js + Node.js (Backend teammate)
│       ├── /src
│       │   ├── /controllers # Logic for routes
│       │   ├── /routes      # Endpoint definitions
│       │   └── index.js     # Entry point
│       └── vercel.json      # Vercel backend config
│
├── /prisma                # YOUR DOMAIN (Database)
│   ├── schema.prisma      # Single source of truth for models
│   └── migrations/        # History of DB changes
│
├── /tests                 # YOUR DOMAIN (QA)
│   ├── integration/
│   └── e2e/
│
├── .env                   # DB URLs and Secrets (Shared)
├── package.json           # Root workspace config
└── README.md