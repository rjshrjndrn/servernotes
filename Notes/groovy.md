This is the tips I acquired for groovy
---

Default value for a variable
```groovy
def val = environment ?: 'staging'
```

In groovysh, by default you won't be able to see variable values. For this please enable 

```groovy
:set interpreterMode true
```

[ref](https://stackoverflow.com/questions/52131115/strange-behavior-using-def-in-groovys-repl-groovysh)
