Nexus is a protocol for arbitrary duration RPC operations. These operations are modeled using a predefined set of synchronous RPCs.

A Nexus caller sends a request to a Nexus server. The request is handled by a Nexus handler. The handler responds either with a result, or with a reference to an asynchronous operation. The caller can cancel an asynchronous operation, check for its outcome, or fetch its current state. The caller can also specify a callback URL that the handler will use to asynchronously deliver the result of an operation when it is complete.

Nexus is currently in development. For more information, see [docs.temporal.io/nexus](https://docs.temporal.io/nexus).
