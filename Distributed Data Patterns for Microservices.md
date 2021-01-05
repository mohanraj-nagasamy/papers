# Distributed Data Patterns for Microservices
* https://microservices.matrixlms.com/

## Overview of the distributed data management workshop

## Patterns
* https://docs.microsoft.com/en-us/azure/architecture/antipatterns/monolithic-persistence/
* https://docs.microsoft.com/en-us/azure/architecture/best-practices/data-partitioning
* https://docs.microsoft.com/en-us/azure/architecture/antipatterns/improper-instantiation/

## Patterns in Distributed Systems
* https://www.infoq.com/news/2019/06/patterns-distributed-systems
* https://verraes.net/2019/05/patterns-for-decoupling-distsys-domain-query/



#### Welcome and workshop overview
![image](https://user-images.githubusercontent.com/2755263/82329799-12a6ea00-999f-11ea-9b4a-56451b5e143e.png)

![image](https://user-images.githubusercontent.com/2755263/82329869-34a06c80-999f-11ea-991d-c9fc8df7900d.png)

#### Additional resources

Here are some useful links:

1.  [About Chris](https://chrisrichardson.net/about.html)
2.  [Microservices.io](https://microservices.io/)
3.  My book [Microservices Patterns](https://microservices.io/book)

## Microservices essentials

The microservice architecture is becoming increasing important. But what is it exactly? Why should you care about microservices? And, what do you need to do to ensure that your organization uses the microservice architecture successfully? In this talk, I’ll answer these and other questions using shapes as visual metaphors. You will learn about the motivations for the microservice architecture and why simply adopting microservices is insufficient. I describe essential characteristics of microservices, You will learn how a successful microservice architecture consist of loosely coupled services with stable APIs that communicate asynchronous. I will cover strategies for effectively testing microservices.

Watch this JFokus 2020 conference talk: [Cubes, Hexagons, Triangles, and More: Understanding Microservices](http://chrisrichardson.net/microservices/2020/02/04/jfokus-geometry-of-microservices.html)

## Transactions and queries in a microservice architecture

Module overview: Transactions and queries in a microservice architecture
In this module you will learn how the need for loose design-time and run-time coupling affects how you implement transactions and queries that span services.

![image](https://user-images.githubusercontent.com/2755263/82330808-872e5880-99a0-11ea-89ad-8617389ba44c.png)

![image](https://user-images.githubusercontent.com/2755263/82330927-ab8a3500-99a0-11ea-81ea-8738d9900205.png)

![image](https://user-images.githubusercontent.com/2755263/82330970-ba70e780-99a0-11ea-8f4e-d61977939e89.png)


![image](https://user-images.githubusercontent.com/2755263/82331082-e12f1e00-99a0-11ea-986d-e5cdd8c2ad82.png)

![image](https://user-images.githubusercontent.com/2755263/82331155-f99f3880-99a0-11ea-8d9b-370b2ff10f32.png)

![image](https://user-images.githubusercontent.com/2755263/82331209-0d4a9f00-99a1-11ea-8066-b1ebf9255e7a.png)

![image](https://user-images.githubusercontent.com/2755263/82331305-2c493100-99a1-11ea-91cd-891c8f404eca.png)

## Overview of the Saga pattern
Module overview: Saga pattern
In this module you will how to use the Saga pattern to implement transactions that span services.

![image](https://user-images.githubusercontent.com/2755263/82331484-6f0b0900-99a1-11ea-9668-a690623f2bc3.png)

![image](https://user-images.githubusercontent.com/2755263/82331652-a7124c00-99a1-11ea-8219-4857373d717b.png)


![image](https://user-images.githubusercontent.com/2755263/82331675-ae395a00-99a1-11ea-9e56-75c840675af2.png)

![image](https://user-images.githubusercontent.com/2755263/82331732-bee9d000-99a1-11ea-93bf-b43c7b3bdf8a.png)

![image](https://user-images.githubusercontent.com/2755263/82331807-db860800-99a1-11ea-9bf1-e599b983c3ec.png)

![image](https://user-images.githubusercontent.com/2755263/82331852-e8a2f700-99a1-11ea-9247-6a46779cc630.png)

![image](https://user-images.githubusercontent.com/2755263/82331884-f22c5f00-99a1-11ea-9a62-338e31c4e32e.png)

![image](https://user-images.githubusercontent.com/2755263/82331983-0e300080-99a2-11ea-9cda-5ed5ccf6057e.png)

![image](https://user-images.githubusercontent.com/2755263/82332001-14be7800-99a2-11ea-96b3-76141e4cbb4e.png)

![image](https://user-images.githubusercontent.com/2755263/82332120-3ddf0880-99a2-11ea-9511-3ff072e8b1e4.png)

![image](https://user-images.githubusercontent.com/2755263/82332161-4c2d2480-99a2-11ea-8f6c-ce972b1c79b5.png)

![image](https://user-images.githubusercontent.com/2755263/82332504-b9d95080-99a2-11ea-907e-71c1234ad23d.png)


![image](https://user-images.githubusercontent.com/2755263/82332565-cbbaf380-99a2-11ea-9353-16fe361c2527.png)

![image](https://user-images.githubusercontent.com/2755263/82332705-f5741a80-99a2-11ea-823d-30ecfa7c37f6.png)


![image](https://user-images.githubusercontent.com/2755263/82332795-13da1600-99a3-11ea-9f1a-0dd23883143c.png)

![image](https://user-images.githubusercontent.com/2755263/82332826-1fc5d800-99a3-11ea-9eb9-944b1354e76c.png)

![image](https://user-images.githubusercontent.com/2755263/82332958-526fd080-99a3-11ea-9380-70a120616085.png)


![image](https://user-images.githubusercontent.com/2755263/82332986-5b60a200-99a3-11ea-9a76-4f2c9f63d1f9.png)

![image](https://user-images.githubusercontent.com/2755263/82333036-6d424500-99a3-11ea-8b3b-d57ee11d9c94.png)

![image](https://user-images.githubusercontent.com/2755263/82333082-7c28f780-99a3-11ea-8e66-4b10b8fe1f52.png)

#### Learn more about the Saga pattern

Here are some useful links:

* [Saga pattern](https://microservices.io/patterns/data/saga.html)
* [A series of articles on using the Saga pattern](https://chrisrichardson.net/post/microservices/2019/07/09/developing-sagas-part-1.html)
* Chapter 4 of [Microservices Patterns](https://microservices.io/book)


## Saga communication and coordination mechanisms
Module overview: saga communication and orchestration
In this module, you will learn about mechanisms for Saga participant communication and coordination.

![image](https://user-images.githubusercontent.com/2755263/82333341-da55da80-99a3-11ea-851a-6e64170b4c0b.png)

![image](https://user-images.githubusercontent.com/2755263/82333417-f0639b00-99a3-11ea-92df-58af633b1bd4.png)

![image](https://user-images.githubusercontent.com/2755263/82333447-f8233f80-99a3-11ea-9093-cc6356a46e20.png)

![image](https://user-images.githubusercontent.com/2755263/82333521-112bf080-99a4-11ea-8790-5a88a57787f6.png)

![image](https://user-images.githubusercontent.com/2755263/82333555-1db04900-99a4-11ea-98ad-d1292f7c4123.png)

![image](https://user-images.githubusercontent.com/2755263/82333616-328cdc80-99a4-11ea-82bf-0dc2b1d2919d.png)

![image](https://user-images.githubusercontent.com/2755263/82333644-3a4c8100-99a4-11ea-9a31-7bf0196d7db8.png)

![image](https://user-images.githubusercontent.com/2755263/82333688-4b958d80-99a4-11ea-9ee0-36f26ef8f9f8.png)


![image](https://user-images.githubusercontent.com/2755263/82333753-5cde9a00-99a4-11ea-9878-06425abcd1b0.png)

![image](https://user-images.githubusercontent.com/2755263/82333817-6ff16a00-99a4-11ea-954b-d294a7e5f759.png)

![image](https://user-images.githubusercontent.com/2755263/82334012-a929da00-99a4-11ea-9671-22d4d6b45f16.png)

![image](https://user-images.githubusercontent.com/2755263/82334071-b6df5f80-99a4-11ea-84de-45c57aaed84f.png)


![image](https://user-images.githubusercontent.com/2755263/82334133-cb235c80-99a4-11ea-8020-3c943d0a2076.png)

![image](https://user-images.githubusercontent.com/2755263/82334214-e7bf9480-99a4-11ea-9e88-5f72c9f36f51.png)

![image](https://user-images.githubusercontent.com/2755263/82334235-eee6a280-99a4-11ea-819d-1a5885bd608b.png)

![image](https://user-images.githubusercontent.com/2755263/82334276-fa39ce00-99a4-11ea-8f5a-d9fb9ebc886d.png)


![image](https://user-images.githubusercontent.com/2755263/82334313-06259000-99a5-11ea-84d3-0e04623d418a.png)


![image](https://user-images.githubusercontent.com/2755263/82334342-1473ac00-99a5-11ea-9e86-8db9c37ae350.png)


![image](https://user-images.githubusercontent.com/2755263/82334394-25bcb880-99a5-11ea-9242-24d866d65e01.png)


![image](https://user-images.githubusercontent.com/2755263/82334625-76341600-99a5-11ea-85e9-4a1177e8867d.png)



![image](https://user-images.githubusercontent.com/2755263/82334655-80eeab00-99a5-11ea-893f-df20ef864e1a.png)

![image](https://user-images.githubusercontent.com/2755263/82334686-8c41d680-99a5-11ea-92e4-3e43e9308483.png)


![image](https://user-images.githubusercontent.com/2755263/82334736-9f54a680-99a5-11ea-915a-897950fb50c0.png)

![image](https://user-images.githubusercontent.com/2755263/82334804-b398a380-99a5-11ea-9612-e14a499c1d31.png)


![image](https://user-images.githubusercontent.com/2755263/82334862-c7dca080-99a5-11ea-999a-1a0c76cfa52d.png)

# [Saga communication and coordination mechanisms](https://microservices.matrixlms.com/learner_modules/list/294072 "List all modules")[    ![](https://microservices.matrixlms.com/images/icons/book.svg)
  ](https://microservices.matrixlms.com/learner_modules/list/294072 "Return to the modules overview")

#### Learn more about querying in the microservice architecture

* [API Composition pattern](https://microservices.io/patterns/data/api-composition.html)
* [CQRS pattern](https://microservices.io/patterns/data/cqrs.html)
* Chapter 7 of [Microservices Patterns](https://microservices.io/book)

## Using choreography-based sagas
Module overview: choreography-based sagas
In this module, you will learn about choreography-based sagas, and their benefits and drawbacks.

![image](https://user-images.githubusercontent.com/2755263/82335126-243fc000-99a6-11ea-8438-1274b43475aa.png)

![image](https://user-images.githubusercontent.com/2755263/82335168-315caf00-99a6-11ea-9d69-42335f390244.png)

![image](https://user-images.githubusercontent.com/2755263/82335337-6b2db580-99a6-11ea-92a4-3760344b87e9.png)

![image](https://user-images.githubusercontent.com/2755263/82335356-72ed5a00-99a6-11ea-8ac9-681b6c0e0564.png)

![image](https://user-images.githubusercontent.com/2755263/82335486-a4662580-99a6-11ea-9ab4-3d45e6066ade.png)

![image](https://user-images.githubusercontent.com/2755263/82335542-b9db4f80-99a6-11ea-910e-9fd4b127ab39.png)

![image](https://user-images.githubusercontent.com/2755263/82335599-ccee1f80-99a6-11ea-9aaf-5955ab4dbb05.png)

![image](https://user-images.githubusercontent.com/2755263/82335629-d9727800-99a6-11ea-9f52-d4b38daff6f9.png)


![image](https://user-images.githubusercontent.com/2755263/82335668-e5f6d080-99a6-11ea-831e-6ca2c72bfa0f.png)


![image](https://user-images.githubusercontent.com/2755263/82335733-fc9d2780-99a6-11ea-928d-0496bf478501.png)

![image](https://user-images.githubusercontent.com/2755263/82335772-058df900-99a7-11ea-82c4-b60822bff227.png)

![image](https://user-images.githubusercontent.com/2755263/82335806-0e7eca80-99a7-11ea-8bf4-3200c9f439ab.png)

![image](https://user-images.githubusercontent.com/2755263/82335861-1f2f4080-99a7-11ea-8e75-40316732c11b.png)

![image](https://user-images.githubusercontent.com/2755263/82336035-4dad1b80-99a7-11ea-8a26-36516e06ad66.png)
![image](https://user-images.githubusercontent.com/2755263/82336054-57368380-99a7-11ea-89b7-22a07ed3a505.png)
![image](https://user-images.githubusercontent.com/2755263/82336135-6f0e0780-99a7-11ea-80fd-691c835c1b1c.png)
![image](https://user-images.githubusercontent.com/2755263/82336155-7503e880-99a7-11ea-93f6-f7db5c58c70b.png)

## Using orchestration-based sagas
Module overview: Using orchestration-based sagas
In this module, you will learn about orchestration-based sagas, and their benefits and drawbacks.

![image](https://user-images.githubusercontent.com/2755263/82336332-ac729500-99a7-11ea-9449-97c82ea23f76.png)
![image](https://user-images.githubusercontent.com/2755263/82336369-b8f6ed80-99a7-11ea-8208-182dde9ad801.png)

![image](https://user-images.githubusercontent.com/2755263/82336504-eba0e600-99a7-11ea-81d6-d4539cbaefdd.png)

![image](https://user-images.githubusercontent.com/2755263/82336529-f196c700-99a7-11ea-9bf9-de6a4fb7b0a9.png)

![image](https://user-images.githubusercontent.com/2755263/82336542-f9566b80-99a7-11ea-8956-a83aaf4e42e3.png)
![image](https://user-images.githubusercontent.com/2755263/82336571-007d7980-99a8-11ea-97fb-85920c16f0f7.png)
![image](https://user-images.githubusercontent.com/2755263/82336587-07a48780-99a8-11ea-8531-b8f893ff299b.png)
![image](https://user-images.githubusercontent.com/2755263/82336619-0ecb9580-99a8-11ea-9131-c4011e2886cc.png)

![image](https://user-images.githubusercontent.com/2755263/82336717-260a8300-99a8-11ea-9600-2e7e05af7f71.png)
![image](https://user-images.githubusercontent.com/2755263/82336871-4e927d00-99a8-11ea-9ee1-5688fb994486.png)
![image](https://user-images.githubusercontent.com/2755263/82336893-56522180-99a8-11ea-885e-d29a68fb90e7.png)

![image](https://user-images.githubusercontent.com/2755263/82337103-9f09da80-99a8-11ea-9c40-45f488262839.png)

![image](https://user-images.githubusercontent.com/2755263/82337133-a6c97f00-99a8-11ea-9cc0-848b4db59c2f.png)
![image](https://user-images.githubusercontent.com/2755263/82337159-af21ba00-99a8-11ea-8c33-5b7416ead9d9.png)

![image](https://user-images.githubusercontent.com/2755263/82337198-bba61280-99a8-11ea-9a1d-eec2c7587f08.png)
![image](https://user-images.githubusercontent.com/2755263/82337228-c3fe4d80-99a8-11ea-8a97-b103cf74a3de.png)

![image](https://user-images.githubusercontent.com/2755263/82337306-d8dae100-99a8-11ea-8d9e-278077a3fbca.png)
![image](https://user-images.githubusercontent.com/2755263/82337334-e1331c00-99a8-11ea-981d-22cea181a951.png)
![image](https://user-images.githubusercontent.com/2755263/82337371-ee500b00-99a8-11ea-8a64-1dcf0978b256.png)

![image](https://user-images.githubusercontent.com/2755263/82337391-f5771900-99a8-11ea-8a04-f6002ce34bd2.png)

![image](https://user-images.githubusercontent.com/2755263/82337459-0758bc00-99a9-11ea-956e-a32c107d3752.png)

![image](https://user-images.githubusercontent.com/2755263/82337516-18a1c880-99a9-11ea-9d2c-0fd7d4a768d3.png)
![image](https://user-images.githubusercontent.com/2755263/82337549-235c5d80-99a9-11ea-810a-81429657a3f9.png)
![image](https://user-images.githubusercontent.com/2755263/82337715-50107500-99a9-11ea-9693-3d07e94411fb.png)
![image](https://user-images.githubusercontent.com/2755263/82337750-5868b000-99a9-11ea-9e99-8293bbcd11fb.png)
![image](https://user-images.githubusercontent.com/2755263/82337796-628aae80-99a9-11ea-9a13-b32c33dcea9f.png)

![image](https://user-images.githubusercontent.com/2755263/82337856-759d7e80-99a9-11ea-862a-e889d16cfe8b.png)

## The challenges implementing queries in a microservice architecture
Module overview: querying in a microservice architecture
In this module, you will learn about the challenges with implementing queries that span services in a microservice architecture.

![image](https://user-images.githubusercontent.com/2755263/82453258-86afc380-9a6d-11ea-9e98-bd30ddfde937.png)
![image](https://user-images.githubusercontent.com/2755263/82453363-aba43680-9a6d-11ea-9974-4c991e54faab.png)
![image](https://user-images.githubusercontent.com/2755263/82453388-b3fc7180-9a6d-11ea-8940-8b332ba5f87e.png)
![image](https://user-images.githubusercontent.com/2755263/82453463-c9719b80-9a6d-11ea-960b-f56876aaa160.png)
![image](https://user-images.githubusercontent.com/2755263/82453484-d0001300-9a6d-11ea-9879-e352915111d8.png)
![image](https://user-images.githubusercontent.com/2755263/82453520-dd1d0200-9a6d-11ea-8cd1-d9734b56dc57.png)
![image](https://user-images.githubusercontent.com/2755263/82453549-e60dd380-9a6d-11ea-98e5-d26895813c69.png)
![image](https://user-images.githubusercontent.com/2755263/82453621-fb82fd80-9a6d-11ea-9ea5-d33b6412093b.png)
![image](https://user-images.githubusercontent.com/2755263/82453680-0c337380-9a6e-11ea-8096-2e56ced0f3df.png)

## Implementing queries using the CQRS pattern
Module overview: using the CQRS pattern
In this module, you will learn how to use the CQRS pattern to implement queries that span services.

![image](https://user-images.githubusercontent.com/2755263/82453822-3f760280-9a6e-11ea-9e4a-719f9a6097fe.png)

![image](https://user-images.githubusercontent.com/2755263/82453868-5157a580-9a6e-11ea-93e6-7d66980bc455.png)

![image](https://user-images.githubusercontent.com/2755263/82453940-6f250a80-9a6e-11ea-9357-d3bffc972929.png)
![image](https://user-images.githubusercontent.com/2755263/82453974-78ae7280-9a6e-11ea-8944-83ad5af2c07f.png)
![image](https://user-images.githubusercontent.com/2755263/82454054-8ebc3300-9a6e-11ea-960f-6cd9fea5aab6.png)

![image](https://user-images.githubusercontent.com/2755263/82454111-9f6ca900-9a6e-11ea-970e-994d5829621a.png)

![image](https://user-images.githubusercontent.com/2755263/82454234-bca17780-9a6e-11ea-9164-b4a6738a6143.png)
![image](https://user-images.githubusercontent.com/2755263/82454256-c3c88580-9a6e-11ea-86b6-fb64afbcaa3c.png)
![image](https://user-images.githubusercontent.com/2755263/82454279-cc20c080-9a6e-11ea-934d-c9f1d44ecdc2.png)
![image](https://user-images.githubusercontent.com/2755263/82454418-fa060500-9a6e-11ea-9869-57c6ec27993e.png)

![image](https://user-images.githubusercontent.com/2755263/82454440-038f6d00-9a6f-11ea-9143-515ad9b31915.png)
![image](https://user-images.githubusercontent.com/2755263/82454461-0ab67b00-9a6f-11ea-86d3-9e5dedbb70ce.png)
![image](https://user-images.githubusercontent.com/2755263/82454564-2457c280-9a6f-11ea-897f-f7a76123ec91.png)
![image](https://user-images.githubusercontent.com/2755263/82454814-78fb3d80-9a6f-11ea-82cc-def62538dacb.png)
![image](https://user-images.githubusercontent.com/2755263/82454918-97f9cf80-9a6f-11ea-8e59-e6d155aba5ab.png)
![image](https://user-images.githubusercontent.com/2755263/82454948-a3e59180-9a6f-11ea-8df7-c611e5ccb69f.png)
![image](https://user-images.githubusercontent.com/2755263/82454977-aba53600-9a6f-11ea-85bf-30136c959088.png)
![image](https://user-images.githubusercontent.com/2755263/82455054-bfe93300-9a6f-11ea-9a5c-37b23b5e6681.png)
![image](https://user-images.githubusercontent.com/2755263/82455091-cd062200-9a6f-11ea-8abe-823916ee049a.png)
![image](https://user-images.githubusercontent.com/2755263/82455136-d98a7a80-9a6f-11ea-9c42-ed5f94706e45.png)
![image](https://user-images.githubusercontent.com/2755263/82455195-e9a25a00-9a6f-11ea-88f7-4f987704ca44.png)
![image](https://user-images.githubusercontent.com/2755263/82455231-f3c45880-9a6f-11ea-9d51-795ca451820b.png)
![image](https://user-images.githubusercontent.com/2755263/82455270-fe7eed80-9a6f-11ea-8255-652ae478e762.png)
![image](https://user-images.githubusercontent.com/2755263/82455356-18b8cb80-9a70-11ea-9c17-1fa1e6449486.png)
![image](https://user-images.githubusercontent.com/2755263/82455435-2cfcc880-9a70-11ea-9d05-c54ce68f7f54.png)
![image](https://user-images.githubusercontent.com/2755263/82455493-3a19b780-9a70-11ea-8552-74ada86e3eec.png)
![image](https://user-images.githubusercontent.com/2755263/82455534-43a31f80-9a70-11ea-83e3-478c9c28310b.png)
![image](https://user-images.githubusercontent.com/2755263/82455590-59b0e000-9a70-11ea-80dc-90fa52ae591a.png)
![image](https://user-images.githubusercontent.com/2755263/82455655-69c8bf80-9a70-11ea-9508-c2d41c363d10.png)
![image](https://user-images.githubusercontent.com/2755263/82455744-8c5ad880-9a70-11ea-84c6-27db31588e78.png)

## Module overview: Eventuate and Redis
In this module, you will learn how to use [Eventuate](https://eventuate.io/) and Redis together in a microservice architecture.

![image](https://user-images.githubusercontent.com/2755263/82456133-0ee39800-9a71-11ea-8934-641a74b70367.png)

![image](https://user-images.githubusercontent.com/2755263/82456176-1c008700-9a71-11ea-8b7b-ab19d670ee1a.png)
![image](https://user-images.githubusercontent.com/2755263/82456199-24f15880-9a71-11ea-81ff-cc97d4afba89.png)
![image](https://user-images.githubusercontent.com/2755263/82456254-3aff1900-9a71-11ea-8f42-85419a660449.png)
![image](https://user-images.githubusercontent.com/2755263/82456316-536f3380-9a71-11ea-8533-217469ba11f5.png)
![image](https://user-images.githubusercontent.com/2755263/82456374-6124b900-9a71-11ea-8749-80efe76531d5.png)
![image](https://user-images.githubusercontent.com/2755263/82456404-6a158a80-9a71-11ea-8e58-6e28dd0517a9.png)
![image](https://user-images.githubusercontent.com/2755263/82456439-76014c80-9a71-11ea-9beb-2f141ce009aa.png)
![image](https://user-images.githubusercontent.com/2755263/82456528-94674800-9a71-11ea-89d5-82da2169bc37.png)
![image](https://user-images.githubusercontent.com/2755263/82456560-9f21dd00-9a71-11ea-969c-7d9fef6a6f4e.png)
![image](https://user-images.githubusercontent.com/2755263/82456579-a8ab4500-9a71-11ea-93f2-75f0e5cf831a.png)
![image](https://user-images.githubusercontent.com/2755263/82456606-b06ae980-9a71-11ea-82c1-cbc2c04c57f1.png)
![image](https://user-images.githubusercontent.com/2755263/82456628-bb257e80-9a71-11ea-8648-f1b4b3f48149.png)
![image](https://user-images.githubusercontent.com/2755263/82456666-c678aa00-9a71-11ea-8824-96996d49396d.png)
![image](https://user-images.githubusercontent.com/2755263/82456710-d2646c00-9a71-11ea-818b-2f2bc52ccdb4.png)
![image](https://user-images.githubusercontent.com/2755263/82456728-d85a4d00-9a71-11ea-88ac-63910fa0f60d.png)
![image](https://user-images.githubusercontent.com/2755263/82456758-e0b28800-9a71-11ea-8082-2af6cc3e6f50.png)
![image](https://user-images.githubusercontent.com/2755263/82456779-e740ff80-9a71-11ea-9347-afde953a4895.png)
![image](https://user-images.githubusercontent.com/2755263/82456809-ef993a80-9a71-11ea-9a58-1d828ef590fa.png)
![image](https://user-images.githubusercontent.com/2755263/82456834-f627b200-9a71-11ea-988f-6413fbee649f.png)
![image](https://user-images.githubusercontent.com/2755263/82456858-ff188380-9a71-11ea-9897-f7541e5ea13c.png)
![image](https://user-images.githubusercontent.com/2755263/82456911-0dff3600-9a72-11ea-9464-4fbfbe5f5eaa.png)
![image](https://user-images.githubusercontent.com/2755263/82456949-15beda80-9a72-11ea-802e-d5d7134f14cd.png)
![image](https://user-images.githubusercontent.com/2755263/82457008-2a9b6e00-9a72-11ea-9515-5e52f7e8ac0a.png)
![image](https://user-images.githubusercontent.com/2755263/82457049-36873000-9a72-11ea-8cfe-513b2c8f0691.png)
![image](https://user-images.githubusercontent.com/2755263/82457079-41da5b80-9a72-11ea-9c20-c534955829a4.png)

[  ](https://microservices.matrixlms.com/learner_module/show/294072?from=%2Flearner_module%2Fshow%2F294072%3Flesson_id%3D1020803%26section_id%3D6180811&lesson_id=1020803&section_id=6182199)

#### Learn more about Eventuate
* The [Eventuate Platform](https://eventuate.io/)
* [Eventuate and microservices patterns](https://eventuate.io/post/eventuate/2020/02/24/why-eventuate.html)
* [Eventuate example applications](https://eventuate.io/exampleapps.html)

## Eventuate and Redis labs

Please work your way through the lab guide.

1.  Build and run the Customers and Orders application
2.  Review the implement of a choreography-based saga
3.  Review the implementation of a CRS view

Here is the guide again:

[Microservices_Workshop_Labs.pdf](https://microservices.matrixlms.com/files/2218387/Microservices_Workshop_Labs_lmsauth_a4e1d5b6386ff1176e2865d3bf62b703cb9658c9.pdf)

## Wrap up - More information
I help organizations all over the world adopt the microservice architecture.
To learn more about how I can help:

* [Consulting](https://chrisrichardson.net/consulting.html)
* [Training](https://chrisrichardson.net/training.html)









