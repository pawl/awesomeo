## Clojure


[**Metabase**](https://github.com/metabase/metabase) is the easy, open source way for everyone in your company to ask questions and learn from data.

![metabase](https://cdn-images-1.medium.com/max/720/0*1hEfM4l394n4NlkR.png)

---
[**compojure**](https://github.com/weavejester/compojure)  —  a small routing library for Ring that allows web applications to be composed of small, independent parts.

This small Compojure application demonstrates creating a Ring handler from two routes:

```clojure
(ns hello-world.core
  (:require [compojure.core :refer :all]
            [compojure.route :as route]))
(defroutes app
  (GET "/" [] "<h1>Hello World</h1>")
  (route/not-found "<h1>Page not found</h1>"))
```

---
[**Aleph**](https://github.com/ztellman/aleph) exposes data from the network as a Manifold stream, which can easily be transformed into a java.io.InputStream, core.async channel, Clojure sequence, or many other byte representations. It exposes simple default wrappers for HTTP, TCP, and UDP, but allows access to full performance and flexibility of the underlying Netty library.

![aleph](https://cdn-images-1.medium.com/max/720/0*5fSwMgOlFvdKvvKR.png)

---
[**Datascript**](https://github.com/tonsky/datascript)  —  an immutable in-memory database and Datalog query engine in Clojure and ClojureScript.

![datascript](https://cdn-images-1.medium.com/max/720/1*VcZuVmpc41Vduc3ZUFXz3g.png)

---
[**Quil**](https://github.com/quil/quil) is a Clojure/ClojureScript library for creating interactive drawings and animations.

![quil](https://camo.githubusercontent.com/90bc972502b59f7b670dd3c249a7cfc9796f8d23/687474703a2f2f636c6f75642e6769746875622e636f6d2f646f776e6c6f6164732f7175696c2f7175696c2f7175696c2e706e67)

---
[**yada** ](https://github.com/juxt/yada) —  a web library for Clojure, designed to support the creation of production services via HTTP.

Typically, yada handlers are created from a configuation expressed in data.

```clojure
(require '[yada.yada :as yada])

(yada/handler
  {:methods
    {:get
      {:produces "text/html"
       :response "<h1>Hello World!</h1>"}}})
```

---
[**Hoplon**](https://github.com/hoplon/hoplon)  —  a set of tools and libraries for making web applications.

![hoplon](https://camo.githubusercontent.com/75c776f58649a9aeb79835f37eefef65fc508df9/687474703a2f2f686f706c6f6e2e696f2f696d616765732f6c6f676f732f686f706c6f6e2d6c6f676f2e706e67)


---
[**Pedestal**](https://github.com/pedestal/pedestal) is a set of libraries written in Clojure that aims to bring both the language and its principles (Simplicity, Power and Focus) to server-side development.

[Here](https://github.com/pedestal/pedestal/tree/master/samples) you can find samples.

