# Running Clojure tests

```
lein do clean, test
```

# Running ClojureScript tests

```
lein javac
lein doo node test-build once
```

# Running benchmarks
## All benchmarks
```
scripts/run-benchmarks
```
## Individual benchmark(s)
Specify the benchmark names as command line args.  They will likely each need quoted because they contain spaces.
Order is ignored.
```
scripts/run-benchmarks "prepend to a vector" "filter a sequence" 
```

