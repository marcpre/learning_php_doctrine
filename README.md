# learning_php_doctrine

## Tutorial

(Starter Tutorial)[https://www.doctrine-project.org/projects/doctrine-orm/en/current/tutorials/getting-started.html]

## Commands

### Generate Getter/Setter

`vendor/bin/doctrine orm:generate-entities .`

### Recreate DB

```
vendor/bin/doctrine orm:schema-tool:drop --force
vendor/bin/doctrine orm:schema-tool:create
```
