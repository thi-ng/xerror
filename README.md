# thi.ng/xerror

A tiny library to provide x-platform error throwing functions for
Clojure & Clojurescript.

## Leiningen coordinates

```clj
[thi.ng/xerror "0.1.0"]
```

## Usage

```clj
(require '[thi.ng.xerror.core :as err])

(err/throw! "oops, you did it again!")

(err/key-error! :foo)

(err/type-error! 'myns.ExpectedType x)

(err/arity-error! 3)

(err/illegal-arg! 23)

(err/unsupported! "time-travel")
```

## License

Copyright © 2013-2015 Karsten Schmidt 

[Apache Software License 2.0](http://www.apache.org/licenses/LICENSE-2.0)
