# Dishdocs
```
project-root/
├── src/
│   ├── modules/
│   │   ├── recipes/
│   │   │   ├── controllers/
│   │   │   │   └── recipes.controller.ts
│   │   │   ├── services/
│   │   │   │   └── recipes.service.ts
│   │   │   ├── repositories/
│   │   │   │   └── recipes.repository.ts (opcjonalnie)
│   │   │   ├── entities/
│   │   │   │   └── recipe.entity.ts
│   │   │   ├── dto/
│   │   │   │   ├── create-recipe.dto.ts
│   │   │   │   └── update-recipe.dto.ts
│   │   │   └── recipes.module.ts
│   │   ├── users/
│   │   │   ├── controllers/
│   │   │   │   └── users.controller.ts
│   │   │   ├── services/
│   │   │   │   └── users.service.ts
│   │   │   ├── repositories/
│   │   │   │   └── users.repository.ts (opcjonalnie)
│   │   │   ├── entities/
│   │   │   │   └── user.entity.ts
│   │   │   ├── dto/
│   │   │   │   ├── create-user.dto.ts
│   │   │   │   └── update-user.dto.ts
│   │   │   └── users.module.ts
│   │   ├── auth/
│   │   │   ├── controllers/
│   │   │   │   └── auth.controller.ts
│   │   │   ├── services/
│   │   │   │   └── auth.service.ts
│   │   │   ├── strategies/
│   │   │   │   ├── jwt.strategy.ts
│   │   │   │   └── local.strategy.ts
│   │   │   ├── guards/
│   │   │   │   └── jwt-auth.guard.ts
│   │   │   └── auth.module.ts
│   ├── common/
│   │   ├── filters/
│   │   ├── interceptors/
│   │   ├── pipes/
│   │   └── decorators/
│   ├── app.module.ts
│   ├── main.ts
├── test/
├── package.json
├── tsconfig.json
└── README.md
```