## Preview

[NPM](https://www.npmjs.com/package/@pleahmacaka/logger)

### Installation
`bun add @pleahmacaka/logger`  
`npm install @pleahmacaka/logger`

### Example Code

```ts
import { Level, Logger } from "@pleahmacaka/logger"

Logger.log(Level.INFO, "Believe in yourself.")
Logger.warn("Seize the day.")
Logger.critical("Life is a journey.")
```

### Output logs

```
[2023-05-02 18:14:27] :: [INFO] :: Believe in yourself.
[2023-05-02 18:14:27] :: [WARN] :: Seize the day.
[2023-05-02 18:14:27] :: [CRITICAL] :: Life is a journey.
```

The prefix is colored by level and the content is printed in white.
