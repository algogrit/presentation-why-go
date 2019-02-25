* Go is a simple, concurrent language
* Born @ Google - what do they use for?
* Sub-millisecond response times!
* Cross-compilation
* Goroutines & channels
* Go Toolchain

Go's programming style?
  * Simplicity over complexity
  * Neither OOP nor functional in nature
  * Concurrency over parallelism

What Open Source tools are built using it?
  * Docker
  * Kubernetes
  * CockroachDB
  * Hyperledger
  * Jaeger
  * Terraform
  * ...

Which companies are using it?
  * Google
  * Uber
  * Go-JEK
  * Grab
  * BBC
  * SoundCloud
  * CloudFlare
  * Basecamp
  * Heroku

Where Go doesn't shine?
* Package Manager
  Community is still deciding
* null pointer (nil in Go) - Billion dollar mistake!
* No functional programming paradigm (map/reduce/fold)
* Dealing with errors (`return val, err`)

Is Go only a systems programming language?
* Gomobile
* Gobots for IoT
* Go WASM
* Go for AI/ML (https://github.com/esimov/pigo / Tensorflow)
* Blockchain

--

* At Hotstar, we generate more than 10 billion clickstream events per day, at peak. This data is generated from multiple sources and by multiple teams. We built Bifrost, our internal Data Management Platform, as a single platform that allows users to ingest data of any kind & shape, and allow users to query the streaming and stationary data with ease.

* https://medium.com/smsjunk/handling-1-million-requests-per-minute-with-golang-f70ac505fcaa

* ‘Why Go’ the smallest answer is “It is Simple” and then you can take different area/aspect and show simplicity for each :+1::skin-tone-2:

* Netflix, Uber, The Dollar Shave Club (http://highscalability.com/blog/2016/9/13/the-dollar-shave-club-architecture-unilever-bought-for-1-bil.html), Hotstar, Gojek, QubeCinemas, etc use Go

  Yo.. just saw your post on Why Go.. [1] good cross-compilation (as long as CGO is not enabled) & fast compilation (in sec) .. [2] goroutines; the fact that OS thread mgmt, + scaling based on underlying H/w is just a few tweaks on the `runtime` is also a nice selling point; .. [3] there was some talk by Brad Fitzp. on Go's version stability over releases; covered many perf improvements etc.. + GC stop-the-world time reduction etc ... [4] on go-nuts there are plenty of threads by Java shops trying to migrate to Go; where most Qs are if Go can handle large heap sizes .. like >160GB etc .. you may find some on Twitter too.. [5] Go tooling .. never fails to impress :smile:
  Reg: .. success stories at companies adopting Go; . that's a straight dive into twitter feeds :stuck_out_tongue: .. sorry; really wish to help but held up with many things, .. if I come across stuff I'll tell you
