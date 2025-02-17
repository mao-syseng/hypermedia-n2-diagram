# hypermedia-n2-diagram

## Setting up a clojure project
- create deps.edn file
```
{:paths ["src"]
 :deps {}}
```
tells clojure to look for code inside src, empty dependencies.

- create main.clj inside /src
```
(ns main)
(defn -main []
  (println "Hello, World!"))
```

- ctrl + P -> jack-in -> deps.edn = this will start repl and connect