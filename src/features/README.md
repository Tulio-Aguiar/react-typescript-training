Feature-based modules. Each feature is self-contained:

```
features/
└── auth/
    ├── components/   # UI scoped to this feature
    ├── hooks/        # Hooks scoped to this feature
    ├── services/     # API calls for this feature
    ├── store/        # Local state (Zustand slice)
    ├── types/        # TypeScript types for this feature
    └── utils/        # Helpers scoped to this feature
```

Only include the subfolders your feature actually needs.
