# AdonisJS Camel-Case Naming Strategy Example
______

This repository includes an example of how to change the default serialization naming strategy for AdonisJS from `snake_case` to `camelCase`.

### Watch & Read Lesson Here
https://jagr.co/lessons/how-to-serialize-all-adonisjs-lucid-models-properties-as-camel-case

### Watch Lesson on YouTube
https://www.youtube.com/watch?v=OAzvVHnsU8M

------

You can find the naming strategy at `App/Strategies/CamelCaseNamingStrategy.ts`.

It's being applied to all models via our `AppBaseModel` at `App/Models/AppBaseModel.ts`.
