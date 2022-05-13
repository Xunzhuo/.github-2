<div align="center">
  
![WasmEdge Logo](wasmedge-runtime-logo.png)

WasmEdge is a lightweight, high-performance, and extensible WebAssembly runtime. It is [one of the fastest Wasm VMs](https://ieeexplore.ieee.org/document/9214403) today. WasmEdge is an official sandbox project hosted by the [CNCF](https://www.cncf.io/). Its [use cases](https://wasmedge.org/book/en/intro/use.html) include modern web application architectures (Isomorphic & Jamstack applications), microservices on the edge cloud, serverless SaaS APIs, embedded functions, blockchain smart contracts, and smart IoT devices.
  
**[Check out our official documentation](https://wasmedge.org/book/en/)**

</div>

## Quickstart

🚀 [Install](https://wasmedge.org/book/en/start/install.html) WasmEdge \
⌨️ Run a standalone [Wasm program](https://wasmedge.org/book/en/index.html#webassembly-examples) or a [JavaScript program](https://wasmedge.org/book/en/dev/js.html) from CLI \
🔌 Embed a Wasm function in your [Go](https://wasmedge.org/book/en/embed/go.html), [Rust](bindings/rust/), or [C](https://wasmedge.org/book/en/embed/c.html) app \
🛠 Manage and orchestrate Wasm runtimes using [Kubernetes](https://wasmedge.org/book/en/kubernetes.html), [data streaming frameworks](https://wasmedge.org/book/en/frameworks/app/yomo.html), and [blockchains](https://medium.com/ethereum-on-steroids/running-ethereum-smart-contracts-in-a-substrate-blockchain-56fbc27fc95a)

## Repository guides

### Runtimes

* [The WasmEdge Runtime](https://github.com/WasmEdge/WasmEdge) is the main repo for the WebAssembly VM as well as SDKs for [host apps to embed the VM](https://wasmedge.org/book/en/embed.html).
* [WasmEdge QuickJS JavaScript runtime](https://github.com/second-state/wasmedge-quickjs) allows JS programs to run inside WasmEdge. | [Tutorials](https://wasmedge.org/book/en/dev/js.html)

### Developer APIs

* [WasmEdge Socket API](https://github.com/second-state/wasmedge_wasi_socket) is a Rust API to make or serve network requests in WasmEdge. | [Examples](https://wasmedge.org/book/en/dev/rust/networking.html)
* [WasmEdge Tensorflow API](https://github.com/second-state/wasmedge_tensorflow_interface) is a Rust API to run AI inference on Tensorflow and TFLite models in WasmEdge. | [Examples](https://wasmedge.org/book/en/dev/rust/tensorflow.html)
* [WasmEdge Bindgen](https://github.com/second-state/wasmedge-bindgen) provides an easy interface for calling WebAssembly functions from a host. | [Examples](https://wasmedge.org/book/en/embed/go/function.html)

### Integrations

* The [dapr-wasm](https://github.com/second-state/dapr-wasm) project demonstrates integration between Dapr and WasmEdge. WasmEdge functions are now available as Dapr microservices.
* The [YoMo WasmEdge](https://github.com/yomorun/yomo-wasmedge-tensorflow) project demonstrates using WasmEdge functions as data processing backends for YoMo data streams.
* The [container examples](https://github.com/second-state/wasmedge-containers-examples) project demonstrates how WasmEdge apps can be managed by container tools and k8s. | [Tutorials](https://wasmedge.org/book/en/kubernetes.html)

## Contributors

Thank y'all!

<a href="https://github.com/wasmedge/wasmedge/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=wasmedge/wasmedge" />
</a>

