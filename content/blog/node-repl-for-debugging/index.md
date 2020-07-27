---
title: The power of Node REPL
date: "2020-07-27"
description: Leverage the power of REPL to debug or find bugs in your module
---

If you use Node, it comes with a handy REPL (or Programming Shell) where can you invoke functions & see the results right away.

One thing we recently started doing at work is developing client modules for the APIs. That way you can make sure API requests are sent properly from consumer side. Think of it as enforcing a contract between the API and the consumer.

That's where REPL comes in handy, you can sometimes catch bugs or use it to debug the module without using `npm link`. 