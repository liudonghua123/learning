##SOA特征

- **可重用**：一个服务创建后能用于多个应用和业务流程。

- **松耦合**：服务请求者到服务提供者的绑定与服务之间应该是松耦合的。因此，服务请求者不需要知道服务提供者实现的技术细节，例如程序语言、底层平台等等。

- **明确定义的接口**：服务交互必须是明确定义的。Web服务描述语言（Web Services Description Language，WSDL）是用于描述服务请求者所要求的绑定到服务提供者的细节。WSDL不包括服务实现的任何技术细节。服务请求者不知道也不关心服务究竟是由哪种程序设计语言编写的。

- **无状态的服务设计**：服务应该是独立的、自包含的请求，在实现时它不需要获取从一个请求到另一个请求的信息或状态。服务不应该依赖于其他服务的上下文和状态。当产生依赖时，它们可以定义成通用业务流程、函数和 数据模型。

- **基于开放标准**：当前SOA的实现形式是Web服务，基于的是公开的W3C及其他公认标准．采用第一代Web服务定义的SOAP、WSDL和UDDI以及第二代Web服务定义的WS-*来实现SOA。