---
title: "What is Zenoh?"
weight: 1100
menu: 
    docs:
        parent: overview
---

Zenoh is the Next Big Thing in Internet Computing. You may think this is a bold statement, but hopefully after this short read you'll share the perspective.

Technically speaking,  Zenoh is a pub/sub/query protocol that unifies data in motion,  data at rest and computations.  That said, one way of thinking about Zenoh is to imagine it as a data liberator protocol. Zenoh liberates data in several dimensions.

**Cloud to the Microcontroller Communication.** Zenoh is the only protocol available on the market that can work efficiently and perform from server-grade hardware and networks to the embedded microcontroller and extremely constrained networks. As a consequence, Zenoh liberates the data allowing it to freely flow vertically and horizontally from the microcontroller to the data-center. Likewise, it liberates developers from the need to integrate technologies to bridge the communication between the enterprise and the embedded world..
  
**Data Centricity and Location Transparency for Data in Movement and at Rest.**  Since the introduction of Publish/Subscribe the world of data in movement has enjoyed location transparency. In other terms, the ability of receiving data without having to care about the location of the publisher.  Location transparency is a consequence of data centricity -- in these systems users only need to express interests without any concern on the location of its source. This feature is extremely important as it makes it easier to deal with scale, failures, and load-balancing. Zenoh is the first technology to bring location transparency for data at rest, allowing queries to be expressed without any concerns on the actual location of data, i.e. the location of the data-bases. It is Zenoh that takes care of identifying the optimal set of data bases available in  the network where the query should  be executed.

**Easy to Use and Performant.** Zenoh has been designed ground up to be simple to use and high-performance across all its applicability range. It constantly delivers higher throughput and lower latency and achieves that in a fraction of the code of competing protocols. This ensures that developers can be productive from day one and don't need to write brittle and unmaintainable code in order to get performance.

**Energy Efficient.** Few people are aware that communication is incredibly energivore. Think about the difference in the battery life of your mobile when surfing the internet. Now realize that the bulk of the energy that is being used is in the networks that connect you to the data-centers. Zenoh was designed for energy efficiency. This is reflected in its minimal wire-overhead of 4-6 bytes, and its support for exploiting locality in communication.

**Adopted by Next Generation Applications.** In spite of its young age, Zenoh has witnessed an incredibly swift adoption and is used today in next generation applications, such as, Robotics, Autonomous Vehicles, Internet Gaming, and Telecommunications. Specifically, in Robotics, Zenoh is emerging as the protocol of choice for Robot-to-Robot communication and  Internet-scale monitoring management and real-time teleoperation. Likewise, several Autonomous Vehicles and Mobility initiatives, such as [CARMA](https://discourse.ros.org/t/carma-migrating-to-ros-2-with-cyclonedds-and-zenoh/17541) and the [Indy Autonomous Challenge](https://www.indyautonomouschallenge.com),  have adopted Zenoh for Vehicle-to-Anything communication and in a growing number of cases as the only protocol used for on- and off- vehicle communication.

Zenoh has achieved all of this by extremely careful design and craftsmanship. It is the first protocol available on the market that has managed to integrate Internet-Scale Publish/ Subscribe with Geo-Distributed Queries. Thus, why not  [getting started](https://zenoh.io/docs/getting-started/first-app/) with it now?  

### Online References
- [Zenoh: The Genesys](https://www.youtube.com/watch?v=BryexPfh0Jc&t=898s)
- [Improving the Communication Layer of Robot Applications with ROS2 and Zenoh](https://www.youtube.com/watch?v=1NE8cU72frk)
- [Zenoh and Edge Computing: A Perfect Marriage](https://www.youtube.com/watch?v=_NUP-ihrXjQ)

<!-- 
Additionally, for performance, efficiency and privacy reasons, there is an increasing desire to keep the data processing as close as possible to the source, while at the same time not hindering access to geographically remote applications. In other terms, we are experiencing a mainstream [architectural switch](https://perspectives.tech/2019/12/10/architectural-liberum-arbitrium/) from cloud-centric paradigms in which data is stored, processed and retrieved from the cloud to fog and [edge-centric](https://edgenative.eclipse.org/) paradigms where data is stored and processed where it makes most sense for performance, energy efficiency and security matters.  -->

<!-- ~~**Zenoh** has been designed to address the needs of those applications that need to deal with data in movement, data at rest and computation in a scalable, efficient and location transparent manner.~~ -->

<!-- **Zenoh is a pub/sub/query protocol** that unifies data in motion, data in use, data at rest and computations.  It carefully blends traditional pub/sub with geo-distributed storages, queries and computations, while retaining a level of time and space efficiency that is well beyond any of the mainstream stacks. 


**Zenoh** has been designed to:

- Provide a small set of primitives to deal with data in motion, data at rest and computations.

- Give total control on storage location and back-end technology integration.

- Minimize network overhead – the minimal wire overhead of a data message is 4 bytes.

- Support extremely constrained devices – its footprint on Arduino Uno is of 300 bytes.

- Supports devices with low duty-cycle by allowing the negotiation of data exchange modes and schedules.
  
- Provides a rich set of abstraction for distributing, querying and storing data along the entire system. 
  
- Provide extremely low latency and high throughput.  -->
