# Khyzsh Observability API Design

## Logger

```ts
import { logger } from "@khyzsh/observability";

logger.server("Backend started");
logger.auth("User logged in");
logger.error("Database connection failed");
```

---

## Metrics

```ts
import { metrics } from "@khyzsh/observability";

metrics.counter(
  "user_login_total"
);

metrics.increment(
  "user_login_total"
);
```

---

## Security

```ts
import { security } from "@khyzsh/observability";

security.log(
  "MULTIPLE_FAILED_LOGINS",
  {
    ip: "192.168.1.5",
    username: "admin"
  },
  "WARNING"
);
```

---

## Audit

```ts
import { audit } from "@khyzsh/observability";

audit.log({
  userId: 1,
  action: "DELETE_USER",
  targetId: "123"
});
```

---

## Health

```ts
import { health } from "@khyzsh/observability";

health.registerCheck(
  "database",
  async () => true
);
```

---

## Alerts

```ts
import { alerts } from "@khyzsh/observability";

alerts.discord(...);

alerts.telegram(...);

alerts.email(...);
```