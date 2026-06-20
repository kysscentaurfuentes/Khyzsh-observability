# Package Structure

src/

├── logger/
│   ├── logger.ts
│   ├── colors.ts
│   └── rotation.ts
│
├── metrics/
│   ├── counter.ts
│   ├── gauge.ts
│   └── registry.ts
│
├── security/
│   └── securityLogger.ts
│
├── audit/
│   └── auditLogger.ts
│
├── alerts/
│   ├── discord.ts
│   ├── telegram.ts
│   └── email.ts
│
├── health/
│   └── healthCheck.ts
│
└── index.ts