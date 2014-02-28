# trampiti

Clojure library designed to provide API to some of cryptocoin exchanges ([Cryptsy](https://www.cryptsy.com/) now and [BTC-e](https://btc-e.com/) in future).

## Usage

Basic usage in REPL:

```Clojure
user=> (require '[trampiti.core :as t])
user=> (let [crypsy (t/->Cryptsy "api-key" "api-secret")]
         (t/market-data crypsy :all))
```

Full list of API methods you can see at [Cryptsy API docs](https://www.cryptsy.com/pages/api).

## TODO

 - implement BTC-e API
 - implement coins-e API

## License

Copyright © 2014 Alexander Dinu, Reid McKenzie

Distributed under the Eclipse Public License, the same as Clojure.
