# angular cli

## generate action
```
ng generate action Name --creators --group --api
```

## generate component (and export)
```
cd path/to/module
ng generate component name --export
```

## generate effect
```
ng generate effect Name --creators --group --root --module app.module.ts --api false
```
## generate interface
```
ng generate interface models/name
```

## generate module
```
ng generate module name
```

## generate module (lazy loaded)
```
ng generate module name --route "path/to/component" --module app.module
```

## generate reducer
```
ng generate reducer Name --creators --group --reducers reducers/index.ts --api false
```

## generate action
```
ng generate action Name --creators --flat --group --api
```

## generate selector
```
ng generate selector name --flat --group
```

## generate service
```
ng generate service services/name
```
