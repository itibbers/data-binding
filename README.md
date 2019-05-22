# data-binding

Two way data binding like Vue.js.

This is my summary:
```
observe:
    get:
        first: add watcher
        default: return value
    set:
        set and notify watcher

compile:
    v-model:
        bind data updating events, set value
    {{}}:
        add watcher, get and compile view

watch:
    dep:
        subs: [watcher, ...]
        notify: notify watcher
    watcher:
        update: update view
```
