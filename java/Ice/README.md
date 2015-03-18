Demos in this directory:

- async

  This demo illustrates the use of Asynchronous Method Invocation
  (AMI) and Asynchronous Method Dispatch (AMD).

- bidir

  This demo shows how to use bidirectional connections for callbacks.
  This is typically used if the server cannot open a connection to the
  client to send callbacks, for example, because firewalls block
  incoming connections to the client.

- callback

  A simple callback demo that illustrates how a client can pass a
  proxy to a server, invoke an operation in the server, and the server
  call back into an object provided by the client as part of that
  invocation.

- context

  This demo shows how to use Ice request contexts.

- hello

  This demo illustrates how to invoke ordinary (twoway) operations, as
  well as how to invoke oneway operations, use datagrams, secure
  invocations, and how to use batched invocations.

- interrupt

  This demo shows how to use Thread.interrupt to interrupt blocking
  client-side invocations, and forcibly shutdown servers.

- invoke

  This demo illustrates the use of the Ice streaming API.

- latency

  A simple latency test that measures the basic call dispatch delay of
  Ice.

- minimal

  This demo illustrates a minimal Ice application.

- multicast

  This demo illustrates the use of UDP multicast.

- nested

  A demo to illustrate how nested callbacks work, and how the size of
  the thread pool affects the maximum nesting depth.

- optional

  This demo shows the use of the optional keyword.

- plugin

  A demo to illustrate how to write and use Ice plugins.

- properties

  Shows how to access a server's PropertiesAdmin facet in order to
  retrieve and modify its configuration properties, and how the server
  can receive notifications whenever its properties are changed.

- serialize

  This demo illustrates how to transfer serializable Java classes
  with Ice.

- session

  This demo shows how to use sessions to clean up client-specific
  resources in a server after the client shuts down or crashes.

- swing

  A swing application that shows how to use Asynchronous Method
  Invocation (AMI) in a graphical client.

- throughput

  A simple throughput demo that allows you to send sequences of
  various types between client and server and to measure the maximum
  bandwidth that can be achieved using serialized synchronous
  requests.

- value

  This demo shows how to use classes, class factories, and the
  difference between local and remote invocations of class operations.