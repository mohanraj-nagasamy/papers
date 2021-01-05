# Advanced Distributed System Design (Free Online)
* https://particular.net/training-courses
* https://particular.net/adsd

## Fallacies of Distributed Computing

#### Introduction: Systems vs. Applications

![image](https://user-images.githubusercontent.com/2755263/79871799-295b2080-83a2-11ea-81f9-d8bba833b7c7.png)

ex: Application for ex: Word, Power-point, Keynote -> Single Machine

![image](https://user-images.githubusercontent.com/2755263/79872185-af776700-83a2-11ea-999f-6226886d8d98.png)

* Trying to abstract away the network has led to 

![image](https://user-images.githubusercontent.com/2755263/79872487-14cb5800-83a3-11ea-8909-0b443679a8fb.png)

* 3 more

![image](https://user-images.githubusercontent.com/2755263/79872689-565c0300-83a3-11ea-9992-8f197fcc6647.png)

#### Fallacy #1: The network is reliable

![image](https://user-images.githubusercontent.com/2755263/79872819-7ee3fd00-83a3-11ea-9816-13aa95270085.png)

##### Solution

![image](https://user-images.githubusercontent.com/2755263/79873074-d71aff00-83a3-11ea-8bc9-9150c496f674.png)

#### Fallacy #2: Latency isn’t a problem

* Round trip time vs Latency time
* Latency - given everything has been serialized - how long it will take to travel from the client to the server over the network

![image](https://user-images.githubusercontent.com/2755263/79873620-98397900-83a4-11ea-8d0d-1e6095809496.png)

* 1 CPU cycle is scaled to 1 second

![image](https://user-images.githubusercontent.com/2755263/79873918-fb2b1000-83a4-11ea-932c-012458fac28f.png)

##### Solution

![image](https://user-images.githubusercontent.com/2755263/79874289-6674e200-83a5-11ea-9d9b-3a40546edeca.png)


#### Fallacy #3: Bandwidth isn’t a problem

![image](https://user-images.githubusercontent.com/2755263/79874549-bce22080-83a5-11ea-8910-af6dede92a70.png)

##### Solution

![image](https://user-images.githubusercontent.com/2755263/79874625-d5ead180-83a5-11ea-8ff8-428c07e62db8.png)

* Logical decoupling to low vs high priority networks
* Subdividing into logically gives us OPTIONS. ex: Reporting service and  
* Designing monolithically DOESN't gives us those OPTIONS

![image](https://user-images.githubusercontent.com/2755263/79875740-4ba36d00-83a7-11ea-9d08-73e29f502937.png)

#### Fallacy #4: The network is secure

![image](https://user-images.githubusercontent.com/2755263/79875821-683fa500-83a7-11ea-884b-a2d660a02069.png)

##### Solution

![image](https://user-images.githubusercontent.com/2755263/79875883-81e0ec80-83a7-11ea-83f9-b452657f48db.png)


#### Fallacy #5: The network topology won’t change

![image](https://user-images.githubusercontent.com/2755263/79876180-f451cc80-83a7-11ea-9e2a-47d78be91e6e.png)

##### Solution

![image](https://user-images.githubusercontent.com/2755263/79876226-03d11580-83a8-11ea-8f8d-f05c8fc665c7.png)

#### Fallacy #6: The admin will know what to do

![image](https://user-images.githubusercontent.com/2755263/79876659-8eb21000-83a8-11ea-9949-f70f0c1ed5c3.png)

##### Solution

![image](https://user-images.githubusercontent.com/2755263/80219273-7851c180-85ff-11ea-8c42-073061909974.png)

* ITIL process
* Upgrading while keeping backward compatible.
* When you are looking for a needle in a haystack, don't create more haystacks
* Maybe we need magnets to pull the needles

#### Fallacy #7: Transport cost isn’t a problem

![image](https://user-images.githubusercontent.com/2755263/80219586-eac2a180-85ff-11ea-9788-a39758150aa9.png)
* Ser/Deser takes a lot of CPU time 
* Quiz: Is it cheaper to 


#### Fallacy #8: The network is homogeneous

![image](https://user-images.githubusercontent.com/2755263/80222125-9a4d4300-8603-11ea-95df-c4ea1e2f230e.png)

* Every industry has a standard. 
* And standard has some extensibility - ie fancy way of saying - it some one want to do little bit of different than others (which is every body :)) 
* How to deal with semantic interoperability -> ie one systems (A) accepts user is null value, other system (B) doesn't accept user as null. If B depends on A, we can't integrate. Talk to business.

in health-care, ER system always doesn't have DOB (sometime they wheeled into hospital when they are unconscious). 
But the medication system - you can't prescription certain type of medication with out the DOB.

##### Solution

* Noting works out of the box. 
* Everything Takes Longer Than Anticipated: Hofstadter’s Law [Mental Models]
* https://www.rightattitudes.com/2017/03/24/hofstadter-law-delays/


#### Fallacy #9: The system is atomic

![image](https://user-images.githubusercontent.com/2755263/80381114-ae8c7c80-885d-11ea-9757-0bc33ec8ba56.png)


##### Solution

![image](https://user-images.githubusercontent.com/2755263/80382581-acc3b880-885f-11ea-96d8-189b376a88c6.png)

* Will spend time on How to do this stuff.
* The idea is simple, practice what makes them hard.
* In theory, there is no difference between theory and practice. But in practice, there is.

#### Fallacy #10 : The system is finished

![image](https://user-images.githubusercontent.com/2755263/80383143-70448c80-8860-11ea-9092-f96fe642f089.png)

* You have been asked to lift the buildings all time in software. 
* There is no such thing is software maintenance. There is also  no such thing is maintenance programmer. 
* iPhone never went on maintenance mode after the first release.
* 

![image](https://user-images.githubusercontent.com/2755263/80388871-a6393f00-8867-11ea-88fc-1253bd6a3533.png)

* We human change behaviors as a result of pain

##### Solution

![image](https://user-images.githubusercontent.com/2755263/80389251-19db4c00-8868-11ea-9fe0-6fab79d92bf3.png)

#### Fallacy #10: Towards a better development process

![image](https://user-images.githubusercontent.com/2755263/80389425-4d1ddb00-8868-11ea-8d31-1ea580f8d3d0.png)

* You have to understand why want what you want.

![image](https://user-images.githubusercontent.com/2755263/80389998-172d2680-8869-11ea-8234-0a1e0b71e59d.png)

* Well-formed team -> A group of people worked in the past. Not a collection of individuals.
* Knowledge and skill components are also important.

![image](https://user-images.githubusercontent.com/2755263/80391475-01b8fc00-886b-11ea-93da-844c51a1812d.png)

* you let people do what needs to be done -> then scope creep. 
* you can't take something from facebook, google, twitter and implant into your organization. 

#### Fallacy #11 : The business logic can and should be centralized

* fancy way of saying re-use is good. ex: UI, service, entities

![image](https://user-images.githubusercontent.com/2755263/79870131-b9e43180-839f-11ea-8034-124cb391b4a7.png)

##### Solution

![image](https://user-images.githubusercontent.com/2755263/80402424-2026f380-887b-11ea-83e6-cd0c7d1addbd.png)

* DRY vs WET - Write Everything Twice
* Duplication is not evil as it is often stated. 

#### Summary

![image](https://user-images.githubusercontent.com/2755263/79871668-ec8f2980-83a1-11ea-9ea2-d57437938aa8.png)

### Quiz:

```
Splitting just for splitting is creating all kinds of different problems.</span>
I very much agree that separating out your APIs and stuff like that is always 
At least if you don’t get into creating interfaces on your domain model just for the 
I resent the equality sign between evil and monolith just outright.</span>
If you make the cost be your only guideline, you can go wrong.</span>
In the cloud that might be an issue, if all you are looking at is the bottom line.</span>
Isn’t this a case of different time frames and different types of costs?</span>
Because, I think you can say it’s all about cost.</span>
You can get the best architecture, it should be the least expensive, the cheapest, 
The term that matters.</span>
You can say the upfront cost might be higher, but the maintainability of changes coming 
Lower total cost of ownership.</span>

I’ve had a different thought about that.</span>
That, sometimes just the cost factor is affecting your architecture.</span>
Because it would be more expensive to do it the right way and cheaper to do it the 
The more you glue things together, the cheaper it gets.</span>
What I’ve heard here in the room is that monoliths equal evil.</span>
I’m not buying into that. To a certain degree, I agree.</span>
If you have too big of a monolith and it’s causing you trouble.</span>
At the end of the day, the monolith is paying our salary and it’s doing a lot of 
If you have trouble with your monolith then it’s time to split it.</span>
Splitting just for splitting is creating all kinds of different problems.</span>
I very much agree that separating out your APIs and stuff like that is always 
At least if you don’t get into creating interfaces on your domain model just for 
I resent the equality sign between evil and monolith just outright.</span>
If you make the cost be your only guideline, you can go wrong.</span>
In the cloud that might be an issue, if all you are looking at is the bottom 

I very much agree that separating out your APIs and stuff like that is 
At least if you don’t get into creating interfaces on your domain model 
I resent the equality sign between evil and monolith just 
If you make the cost be your only guideline, you can go wrong.</span>
In the cloud that might be an issue, if all you are looking at is the 
Isn’t this a case of different time frames and different types of 
Because, I think you can say it’s all about cost.</span>
You can get the best architecture, it should be the least expensive, the 
The term that matters.</span>
You can say the upfront cost might be higher, but the maintainability of 
Lower total cost of ownership.</span>


Fallacy: 8
There is another fallacy, which is the human factor.
Obviously not all developers understand technical implementations.
In my team that’s a very big issue.
How can we get over that?
The trend is developers choosing their own technology to deliver the service. They make the simplest thing possible, at first.
They don’t divide things up, they don’t handle all the physical boundaries and stuff like that.
You just pick a card from the backlog.
I’m done, finish, sprint demo and off t o the next task.
That’s a trend that keeps growing.
It’s hard to enforce, or even suggest, the architecture up-front.
It’s about the complexity.

Distributed computing is more complex to build.
The monolith is a lot easier to explain and you can do more inside the monolith than your diagram there.
It’s more complex for the developers to understand and build.
It’s more likely that they mess it up and make it worse than the monolith.

I think the skill level of the developer is important.
We even talk about this as a stopping factor.
Maybe we can’t introduce event driven architecture because the developers don’t understand it and will just create a mess.

Fallacy: 9

Isn’t there the same issue with a distributed system? Everything seem to work as well, but you have even less visibility.
If you have a set of microservices
and want them all to deliver business value together.
If one of them sends a message with nulls
because we forgot about that.
You won’t get any compilation errors in a distributed system either.
```

## Coupling



#### Coupling in applications: afferent and efferent

![image](https://user-images.githubusercontent.com/2755263/80592578-ebcb4880-89dc-11ea-8938-58d008fe62d1.png)

* Coupling is very subjective - it boils down to I like it vs I don't like it.

![image](https://user-images.githubusercontent.com/2755263/80592695-15846f80-89dd-11ea-91c7-cd931ec0d597.png)

* Afferent (Incoming) vs Efferent (Outgoing)

![image](https://user-images.githubusercontent.com/2755263/80592921-7c098d80-89dd-11ea-9004-0439b859e3c7.png)

* Which kind is worst?

![image](https://user-images.githubusercontent.com/2755263/80593080-c428b000-89dd-11ea-8b96-6288789ac10d.png)

* D is good here. But does it produce any business value? it might be useless.

![image](https://user-images.githubusercontent.com/2755263/80594526-634ea700-89e0-11ea-8281-4bb22599d409.png)

![image](https://user-images.githubusercontent.com/2755263/80596198-38198700-89e3-11ea-961f-4a04bb4eadd9.png)

C => could be service layer - calling daos, entities. 
B => could be presentation layer
A => could be utility, self-contained and we expect to be used in a number of places. 

* How to count coupling?

![image](https://user-images.githubusercontent.com/2755263/80596469-a3fbef80-89e3-11ea-87c4-b94309a4c6db.png)

* Which one is more stable?
* Add rules in the build pipeline - why would you break the rule vs fix the code (by talking to computer)

#### Coupling in systems: platform, temporal and spatial

* Make the coupling explict


#### Coupling in applications: afferent and efferent

![image](https://user-images.githubusercontent.com/2755263/80592578-ebcb4880-89dc-11ea-8938-58d008fe62d1.png)

* Coupling is very subjective - it boils down to I like it vs I don't like it.

![image](https://user-images.githubusercontent.com/2755263/80592695-15846f80-89dd-11ea-91c7-cd931ec0d597.png)

* Afferent (Incoming) vs Efferent (Outgoing)

![image](https://user-images.githubusercontent.com/2755263/80592921-7c098d80-89dd-11ea-9004-0439b859e3c7.png)

* Which kind is worst?

![image](https://user-images.githubusercontent.com/2755263/80593080-c428b000-89dd-11ea-8b96-6288789ac10d.png)

* D is good here. But does it produce any business value? it might be useless.

![image](https://user-images.githubusercontent.com/2755263/80594526-634ea700-89e0-11ea-8281-4bb22599d409.png)

![image](https://user-images.githubusercontent.com/2755263/80596198-38198700-89e3-11ea-961f-4a04bb4eadd9.png)

C => could be service layer - calling daos, entities. 
B => could be presentation layer
A => could be utility, self-contained and we expect to be used in a number of places. 

* How to count coupling?

![image](https://user-images.githubusercontent.com/2755263/80596469-a3fbef80-89e3-11ea-87c4-b94309a4c6db.png)

* Which one is more stable?
* Add rules in the build pipeline - why would you break the rule vs fix the code (by talking to computer)

#### Coupling in systems: platform, temporal and spatial
![image](https://user-images.githubusercontent.com/2755263/80597827-9fd0d180-89e5-11ea-8efd-52c0c51d2973.png)

* Make the coupling explicit

```
Even if we're dealing with two different representations of the same shared resource in the database, is that still coupling?
Or when you live with your boat, beside the street.
Is there a good static analysis tool that will give you reliable figures for afferent and efferent coupling?
We use Sonar at the moment, but I’m not sure if that gives us these figures.
If it does, I’m not sure it gives it with this naming convention. Does NDepend present it this way?
```
![image](https://user-images.githubusercontent.com/2755263/80598274-50d76c00-89e6-11ea-9470-3b9560bd0c44.png)

##### Platform coupling

![image](https://user-images.githubusercontent.com/2755263/80598458-9eec6f80-89e6-11ea-9b13-f9629c1a9814.png)

* Fallacy NO:8 -> network is homogeneous 
* REST vs AVRO vs RMI vs RemoteObject Invocation 

##### Temporal coupling
![image](https://user-images.githubusercontent.com/2755263/80598938-571a1800-89e7-11ea-8247-24bf696219bf.png)

* You may have temporal decoupled but still have platform coupling.

##### Spatial coupling

![image](https://user-images.githubusercontent.com/2755263/80599126-a82a0c00-89e7-11ea-95c1-71e394d6f04a.png)

##### Platform coupling: Solutions 
![image](https://user-images.githubusercontent.com/2755263/80599541-546bf280-89e8-11ea-8e10-92288b5f5aa4.png)

* Productivity vs Interoperability 
* Something thrown into schema is validation
* SOAP - provides envelop and describes what things can go in there vs HTTP headers. 
* WSDL - describes incoming payload and outgoing payload 
* REST - HATEOAS -> great idea but impractical 

![image](https://user-images.githubusercontent.com/2755263/80600355-82056b80-89e9-11ea-96fb-76a1ba11333b.png)

```
You talked about schema. Did you say use schema or don’t use schema?
It’s about developer productivity. As things evolve and you have to update things.
Then the schema may break stuff, I suppose. It’s like static typing in a way.
I’ve heard this talk about robustness of the Internet. It’s a very accepting technology. It doesn’t enforce much.
It makes it harder to predict what you’ll get. On the other hand, it doesn’t throw up in your face when you introduce something new.
You can evolve it better in production that way. That’s the same thing with statically typed vs dynamically typed languages.
Statically typed languages are nice when you’re trying to develop something by yourself on your own computer, because you’ll get compile errors, etc.
But that’s only about developer’s comfort. When you go into production, static typing doesn’t really help you anymore.
I wanted to ask you about some real-life examples of using SMTP in a way you described before.
Does NServiceBus have a plugin for SMTP?

```
##### Temporal coupling: Solutions

![image](https://user-images.githubusercontent.com/2755263/80601292-dd842900-89ea-11ea-88f0-c0d3fec511f8.png)

![image](https://user-images.githubusercontent.com/2755263/80601404-03a9c900-89eb-11ea-9fe2-6d665a1b74ff.png)

![image](https://user-images.githubusercontent.com/2755263/80601795-816dd480-89eb-11ea-922c-663f3f31813d.png)

![image](https://user-images.githubusercontent.com/2755263/80601824-8c286980-89eb-11ea-8057-15176240769e.png)

![image](https://user-images.githubusercontent.com/2755263/80602043-df9ab780-89eb-11ea-871e-08a81b5c9a92.png)

![image](https://user-images.githubusercontent.com/2755263/80602696-a7e03f80-89ec-11ea-89fc-3675570e9910.png)

![image](https://user-images.githubusercontent.com/2755263/80602808-d231fd00-89ec-11ea-853a-21afcf3b202d.png)

![image](https://user-images.githubusercontent.com/2755263/80602958-07d6e600-89ed-11ea-9ea3-4f655ee6b265.png)


##### Spatial coupling: Solutions 

![image](https://user-images.githubusercontent.com/2755263/80603262-68feb980-89ed-11ea-8702-44104a4b90c6.png)

![image](https://user-images.githubusercontent.com/2755263/80603343-82a00100-89ed-11ea-8240-558ed3e86ff1.png)

![image](https://user-images.githubusercontent.com/2755263/80603481-b5e29000-89ed-11ea-9b16-1bdab092f027.png)

#### Summary

![image](https://user-images.githubusercontent.com/2755263/80604132-91d37e80-89ee-11ea-8fd3-c226a1c53a97.png)



## Intro to messaging

#### Why messaging?
![image](https://user-images.githubusercontent.com/2755263/80605719-ac0e5c00-89f0-11ea-9c4d-422ad050c9f6.png)

![image](https://user-images.githubusercontent.com/2755263/80605749-b6c8f100-89f0-11ea-9101-5ef145290a9c.png)

#### One-way, fire & forget

![image](https://user-images.githubusercontent.com/2755263/80605971-f5f74200-89f0-11ea-9ea5-1f4237d4e990.png)

![image](https://user-images.githubusercontent.com/2755263/80606035-0b6c6c00-89f1-11ea-8291-de99e2a12e81.png)

![image](https://user-images.githubusercontent.com/2755263/80606207-479fcc80-89f1-11ea-898f-6a976e151985.png)

![image](https://user-images.githubusercontent.com/2755263/80606343-7322b700-89f1-11ea-92be-176f3fe640de.png)

![image](https://user-images.githubusercontent.com/2755263/80606805-f512e000-89f1-11ea-9e0c-1e495e08dc73.png)

#### Performance: messaging vs RPC

![image](https://user-images.githubusercontent.com/2755263/80607502-cf3a0b00-89f2-11ea-9565-798caf4e3dd4.png)

#### Service interfaces vs strongly-typed messages

#### Service interfaces vs strongly-typed messages

![image](https://user-images.githubusercontent.com/2755263/80609184-0b6e6b00-89f5-11ea-870e-488cf2844c9e.png)

![image](https://user-images.githubusercontent.com/2755263/80614732-07921700-89fc-11ea-8f57-fab18311672f.png)

![image](https://user-images.githubusercontent.com/2755263/80614888-3f00c380-89fc-11ea-932f-1c13e4d40e88.png)

![image](https://user-images.githubusercontent.com/2755263/80615140-8c7d3080-89fc-11ea-837d-a04a2cbd6359.png)

##### Command Messaging vs RPC
* Events doesn't reject the facts.
* will discus from the context of CQRS later

![image](https://user-images.githubusercontent.com/2755263/80617795-c4d23e00-89ff-11ea-97cc-a6ec473fa6d3.png)

![image](https://user-images.githubusercontent.com/2755263/80622024-6e67fe00-8a05-11ea-988a-dc779e96bc07.png)

#### Fault tolerance 

![image](https://user-images.githubusercontent.com/2755263/80624028-56de4480-8a08-11ea-87d9-d2c65856a176.png)

![image](https://user-images.githubusercontent.com/2755263/80625546-99a11c00-8a0a-11ea-9405-ac70272b8fb0.png)
![image](https://user-images.githubusercontent.com/2755263/80625862-04525780-8a0b-11ea-849f-bf489bef0abe.png)

![image](https://user-images.githubusercontent.com/2755263/80626196-4c717a00-8a0b-11ea-8c1d-fc4445f8aab3.png)

![image](https://user-images.githubusercontent.com/2755263/80626441-aeca7a80-8a0b-11ea-883c-968b01c564f2.png)

![image](https://user-images.githubusercontent.com/2755263/80626543-d6b9de00-8a0b-11ea-9010-ec66215f9d1d.png)
![image](https://user-images.githubusercontent.com/2755263/80626864-4c25ae80-8a0c-11ea-9878-7ab080de233a.png)

![image](https://user-images.githubusercontent.com/2755263/80626987-7bd4b680-8a0c-11ea-96a3-f981be3a5f37.png)

![image](https://user-images.githubusercontent.com/2755263/80627125-aaeb2800-8a0c-11ea-9846-1a73617e97df.png)

#### Auditing

![image](https://user-images.githubusercontent.com/2755263/80627509-4aa8b600-8a0d-11ea-8e78-ac24c9f76b47.png)

![image](https://user-images.githubusercontent.com/2755263/80628253-521c8f00-8a0e-11ea-9c04-24958302351b.png)
![image](https://user-images.githubusercontent.com/2755263/80628290-5f397e00-8a0e-11ea-8b5a-fc7370c5474f.png)
![image](https://user-images.githubusercontent.com/2755263/80628468-9f006580-8a0e-11ea-9cc0-81ffb918bc4f.png)


#### Web Services invocation

![image](https://user-images.githubusercontent.com/2755263/80715310-68305b00-8ab3-11ea-8b9c-fab46840202b.png)

![image](https://user-images.githubusercontent.com/2755263/80716032-687d2600-8ab4-11ea-8b3b-df3b7947eef4.png)

* Its better get the ID from client generated

![image](https://user-images.githubusercontent.com/2755263/80716831-5f408900-8ab5-11ea-8602-cdfd713870ef.png)

* One more level of indirect using message
* What if the WS is down or already received the order -> to solve this, query the WS first before submit.
* Given any piece of technology - a queue and a DB - OR a queue and a WebService. The rule of thumb is:
* When you getting a response from the WS, you shouldn’t write directly into the DB. Why you are violating the two. Instead send response message from the blue box (WS to queue), then queue to DB.
* Be aware of semantic differentiations (for ex: reporting use-cases, or down stream systems) - that mean DB may have null values - because of eventual consistency.  
* Prefer reliability over performance 
* 


## Exercise: selling messaging to your organization

#### Exercise: selling messaging to your organization - overview

* avoid judgemental question like - web-services suck. 
* you can experts quotes, book and talk references.
* Try to understand the context - for this company, for this project this makes sense. 

#### Exercise: selling messaging to your organization - discussion (part 1)

* Why do we want to things differently from traditional 3-tier web-services stack

```
Once a month, on the 1st day of the month, we have peak load in our system.
Our web services architecture that performs well for the rest of the month, doesn’t degrade very well under high load.
```
![image](https://user-images.githubusercontent.com/2755263/80812720-bb72de00-8b85-11ea-8206-4932928ff699.png)

Udi: From Web-Services perspective, it is  build for this. we can scale up when we see more load. and scale down when there is no load.

```
That implies that the ability to scale up the cloud resources is almost instantaneous, when it probably isn’t.
In a retail environment, let’s say you issue a big promotion or an email campaign. Suddenly the traffic on the website peaks, very dramatically.
It’s not a slow rise, it’s a peak rise. There’s gonna be latency in spinning up those extra resources.
Whereas actually on the website all you’re really concerned about is taking the order. But backend processing, for example doing fraud check, that all could happen later.
By queueing up the orders we could handle that instantaneous peak much better.
And by the time your cloud infrastructure spun up, that little peak might have gone,
because the promotional email goes out, people go to the website and place order.
You might have lost some order in the process.
```

Udi: From Web-Services perspective 
- we should be able to spinnup in mins not in hours.
- cloud providers canonical internet to provide that kind of ability to move more things into infrastructure 
- We are changing the business process around the technology 

```
The same point, but he said it better than I would have.
I’d say that is probably a cost issue, because you pay for the hardware. Especially in the cloud. There’ll be a cost to ramp up.
The messaging architecture is scalable but also cost-effective. Because we can only take the order, but process it later.
Storage is a lot cheaper, so you take the message payload and you don’t need that much hardware if you write better software.
One problem with using this kind of queue, instead of proper messaging, is that with messaging you can start to actually physically separate your resources.
Storage is a lot cheaper, so you take the message payload and you don’t need that much hardware if you write better software.
One problem with using this kind of queue, instead of proper messaging, is that with messaging you can start to actually physically separate your resources.
For example, you take the original request, and you have to make an invoice or write it down in the database, but now the batch process have to use the same database to query the data.
If you use messaging however, you can send a message and process it on a separate database.
You get this physical separation for pieces of operation, so you can handle it better.
Isn’t there then database coupling instead?
		</div>
But you’re assuming that the business process that takes the order is actually the one building the message to send over.
While you could send a domain event like “OrderReceived”, then you could have a kind of adapter that pick it up and actually generate the message.
```

#### Exercise: selling messaging to your organization - discussion (part 2)

```
Listening to what what’s been said in the last few minutes...
We’ve been talking about temporal coupling, platform coupling and spatial coupling. Each of those is common.
You’ve responded how we can deal with it if it became a problem.
Whereas messaging is an approach to think about these things up front. Before these problems may manifest.
You talked about scaling in the cloud, that you can pull up more resources, but you’re still talking to just one database.
There’s contention on it, and you have a limited number of connections.
But if you put messaging in front of it, you can control how many threads are actually talking to the database at a time.
Assuming that the web service system is non-trivial, where we have lots of web services that are interconnected. It’s an enterprise.
Then the business would have easier time getting more things done if we switched to messaging.
Because then we can have services that are independent of each other, switch out, easier versioning management.
We’ll be more able to make new stuff, provide more business functionality, because the front end can stay up as we switch things in the background.
No need to allot one time a year when we shut down everything and then install everything and hope for the best.
One remark. I think the complexity will be linear instead of exponential.
Because web services are typically interconnected.
But if you have a bus in the middle, you would actually not make every client have three proxies to different web services.
```

UDI: Be careful buying into that messagings going to solve all of our problems. Historically when new technology  comes up,  under the promise - it is going to solve all of problem. It creates new set of problems that we not familiar with. Then, we can to figureout how to solve those problems.

UDI: Going thru the dip, doesn't put on the high plateau.

```
But if you put messaging in front of it, you can control how many threads are actually talking to the database at a time.
Assuming that the web service system is non-trivial, where we have lots of web services that are interconnected. It’s an enterprise.
Then the business would have easier time getting more things done if we switched to messaging.
Because then we can have services that are independent of each other, switch out, easier versioning management.
We’ll be more able to make new stuff, provide more business functionality, because the front end can stay up as we switch things in the background.
No need to allot one time a year when we shut down everything and then install everything and hope for the best.
One remark. I think the complexity will be linear instead of exponential.
Because web services are typically interconnected.
But if you have a bus in the middle, you would actually not make every client have three proxies to different web services.
They’ll just have a queue they can put messages to, and they’ll have handlers. That’s what messaging would enable.
Just internally
At least you’ll just have a logical mess, instead of having a physical mess.
I’m thinking about the event-driven possibilities. With a messaging solution you can decouple.
You have more options of decoupling because you can separate the concerns into smaller workers with responsibility for certain actions.
And then you have a publisher for events, that doesn’t need to know who does what or even if anything is being done.
```


#### Exercise: selling messaging to your organization - overview

* avoid judgemental question like - web-services suck. 
* you can experts quotes, book and talk references.
* Try to understand the context - for this company, for this project this makes sense. 

#### Exercise: selling messaging to your organization - discussion (part 1)

* Why do we want to things differently from traditional 3-tier web-services stack

```
Once a month, on the 1st day of the month, we have peak load in our system.
Our web services architecture that performs well for the rest of the month, doesn’t degrade very well under high load.
```
![image](https://user-images.githubusercontent.com/2755263/80812720-bb72de00-8b85-11ea-8206-4932928ff699.png)

Udi: From Web-Services perspective, it is  build for this. we can scale up when we see more load. and scale down when there is no load.

```
That implies that the ability to scale up the cloud resources is almost instantaneous, when it probably isn’t.
In a retail environment, let’s say you issue a big promotion or an email campaign. Suddenly the traffic on the website peaks, very dramatically.
It’s not a slow rise, it’s a peak rise. There’s gonna be latency in spinning up those extra resources.
Whereas actually on the website all you’re really concerned about is taking the order. But backend processing, for example doing fraud check, that all could happen later.
By queueing up the orders we could handle that instantaneous peak much better.
And by the time your cloud infrastructure spun up, that little peak might have gone,
because the promotional email goes out, people go to the website and place order.
You might have lost some order in the process.
```

Udi: From Web-Services perspective 
- we should be able to spinnup in mins not in hours.
- cloud providers canonical internet to provide that kind of ability to move more things into infrastructure 
- We are changing the business process around the technology 

```
The same point, but he said it better than I would have.
I’d say that is probably a cost issue, because you pay for the hardware. Especially in the cloud. There’ll be a cost to ramp up.
The messaging architecture is scalable but also cost-effective. Because we can only take the order, but process it later.
Storage is a lot cheaper, so you take the message payload and you don’t need that much hardware if you write better software.
One problem with using this kind of queue, instead of proper messaging, is that with messaging you can start to actually physically separate your resources.
Storage is a lot cheaper, so you take the message payload and you don’t need that much hardware if you write better software.
One problem with using this kind of queue, instead of proper messaging, is that with messaging you can start to actually physically separate your resources.
For example, you take the original request, and you have to make an invoice or write it down in the database, but now the batch process have to use the same database to query the data.
If you use messaging however, you can send a message and process it on a separate database.
You get this physical separation for pieces of operation, so you can handle it better.
Isn’t there then database coupling instead?
		</div>
But you’re assuming that the business process that takes the order is actually the one building the message to send over.
While you could send a domain event like “OrderReceived”, then you could have a kind of adapter that pick it up and actually generate the message.
```

#### Exercise: selling messaging to your organization - discussion (part 2)

```
Listening to what what’s been said in the last few minutes...
We’ve been talking about temporal coupling, platform coupling and spatial coupling. Each of those is common.
You’ve responded how we can deal with it if it became a problem.
Whereas messaging is an approach to think about these things up front. Before these problems may manifest.
You talked about scaling in the cloud, that you can pull up more resources, but you’re still talking to just one database.
There’s contention on it, and you have a limited number of connections.
But if you put messaging in front of it, you can control how many threads are actually talking to the database at a time.
Assuming that the web service system is non-trivial, where we have lots of web services that are interconnected. It’s an enterprise.
Then the business would have easier time getting more things done if we switched to messaging.
Because then we can have services that are independent of each other, switch out, easier versioning management.
We’ll be more able to make new stuff, provide more business functionality, because the front end can stay up as we switch things in the background.
No need to allot one time a year when we shut down everything and then install everything and hope for the best.
One remark. I think the complexity will be linear instead of exponential.
Because web services are typically interconnected.
But if you have a bus in the middle, you would actually not make every client have three proxies to different web services.
```

UDI: Be careful buying into that messagings going to solve all of our problems. Historically when new technology  comes up,  under the promise - it is going to solve all of problem. It creates new set of problems that we not familiar with. Then, we can to figureout how to solve those problems.

UDI: Going thru the dip, doesn't put on the high plateau.

```
But if you put messaging in front of it, you can control how many threads are actually talking to the database at a time.
Assuming that the web service system is non-trivial, where we have lots of web services that are interconnected. It’s an enterprise.
Then the business would have easier time getting more things done if we switched to messaging.
Because then we can have services that are independent of each other, switch out, easier versioning management.
We’ll be more able to make new stuff, provide more business functionality, because the front end can stay up as we switch things in the background.
No need to allot one time a year when we shut down everything and then install everything and hope for the best.
One remark. I think the complexity will be linear instead of exponential.
Because web services are typically interconnected.
But if you have a bus in the middle, you would actually not make every client have three proxies to different web services.
They’ll just have a queue they can put messages to, and they’ll have handlers. That’s what messaging would enable.
Just internally
At least you’ll just have a logical mess, instead of having a physical mess.
I’m thinking about the event-driven possibilities. With a messaging solution you can decouple.
You have more options of decoupling because you can separate the concerns into smaller workers with responsibility for certain actions.
And then you have a publisher for events, that doesn’t need to know who does what or even if anything is being done.
```
#### Exercise: selling messaging to your organization - summary



## Messaging patterns

#### Dealing with out of order messages

#### Request-response

![image](https://user-images.githubusercontent.com/2755263/81013507-787c6900-8e18-11ea-93b8-844699ca40b0.png)

![image](https://user-images.githubusercontent.com/2755263/81013744-eb85df80-8e18-11ea-9f81-35c24ba1289d.png)

![image](https://user-images.githubusercontent.com/2755263/81013909-2f78e480-8e19-11ea-88f3-b1488478f7e4.png)

#### Publish-subscribe

![image](https://user-images.githubusercontent.com/2755263/81014688-93e87380-8e1a-11ea-992e-214609890eb5.png)

![image](https://user-images.githubusercontent.com/2755263/81014802-c5f9d580-8e1a-11ea-9750-3ebe852ae3e6.png)

![image](https://user-images.githubusercontent.com/2755263/81014943-08bbad80-8e1b-11ea-9a49-b3e3b91910be.png)
![image](https://user-images.githubusercontent.com/2755263/81074673-92fd2380-8ea6-11ea-8a3f-dcce6515e946.png)
![image](https://user-images.githubusercontent.com/2755263/81074715-a4dec680-8ea6-11ea-8a2e-b62222ad1b99.png)

#### Publish-subscribe: topics
![image](https://user-images.githubusercontent.com/2755263/81076267-b45f0f00-8ea8-11ea-8df5-16e3bb27914c.png)
![image](https://user-images.githubusercontent.com/2755263/81076934-85956880-8ea9-11ea-8564-90a15310e6da.png)

![image](https://user-images.githubusercontent.com/2755263/81077346-18ce9e00-8eaa-11ea-8708-1085fd4d6e56.png)

![image](https://user-images.githubusercontent.com/2755263/81077848-bd50e000-8eaa-11ea-9fc6-2cc7302b80bd.png)
![image](https://user-images.githubusercontent.com/2755263/81078055-f5f0b980-8eaa-11ea-8c57-21f2855f2394.png)

#### Exercise: dealing with out of order messages - overview

![image](https://user-images.githubusercontent.com/2755263/81078642-bb3b5100-8eab-11ea-8406-88b39a376d7a.png)

* Shipping: Has to see both Billing has accepted and Order has been accepted 

![image](https://user-images.githubusercontent.com/2755263/81079018-356bd580-8eac-11ea-93c6-da2980829705.png)

* Shipping is waiting :) 
![image](https://user-images.githubusercontent.com/2755263/81079079-4ae0ff80-8eac-11ea-98e0-def090b0c94f.png)

* Rant about Unit-Testing: The most effective way to find bugs are by code reading. 
* Book: Code Complete 

![image](https://user-images.githubusercontent.com/2755263/81081717-85986700-8eaf-11ea-80b5-2833f5d63f74.png)

#### Exercise: dealing with out of order messages - solutions

* How many time I see this message before - some kind of counter 
* After a while I would move to error-queue 
* Delayed retry

![image](https://user-images.githubusercontent.com/2755263/81082586-b6c56700-8eb0-11ea-9c08-0a5edc230cf2.png)

![image](https://user-images.githubusercontent.com/2755263/81178070-e0d86100-8f64-11ea-8a4c-5d9cc6545f36.png)

* Not all exceptions are errors. 
* After few retries, the msg goes to error-queue. 
* Log: info->warn->error

#### Visualization
* https://particular.net/blog/what-does-your-particular-system-look-like
* https://docs.particular.net/nservicebus/architecture/principles
* https://docs.particular.net/nservicebus/architecture/
* Dealing with eventual consistency
* https://vimeo.com/372096465

![image](https://user-images.githubusercontent.com/2755263/81180483-5a258300-8f68-11ea-82b9-c92805f33c90.png)

#### Messaging patterns: summary

![image](https://user-images.githubusercontent.com/2755263/81183261-2ea49780-8f6c-11ea-8f6c-aabffef971a3.png)

![image](https://user-images.githubusercontent.com/2755263/81183614-98bd3c80-8f6c-11ea-9eac-e5e0129fa272.png)

## Intro to architectural styles
## Intro to architectural styles
![image](https://user-images.githubusercontent.com/2755263/81183724-bbe7ec00-8f6c-11ea-8c2d-924114589625.png)

* Multiple views of software architecture: Logical vs Development vs Deployment
* Multiple views of software architecture styles: Broker vs BUS and REST
![image](https://user-images.githubusercontent.com/2755263/81184047-2862eb00-8f6d-11ea-87bd-ee71e958ec42.png)

![image](https://user-images.githubusercontent.com/2755263/81184063-30228f80-8f6d-11ea-9ce6-ed12f31d48a5.png)

![image](https://user-images.githubusercontent.com/2755263/81184607-d1a9e100-8f6d-11ea-947d-831618a07382.png)
![image](https://user-images.githubusercontent.com/2755263/81184631-da021c00-8f6d-11ea-9f81-1f60f30717d2.png)

* We have to max different ingredients at different parts of the system
* We endup building custom meal on almost on every project
* We don't really have recipe: Oh you are building a online shop - here is the recipe.  
*  Oh you are building a online shop - here is the list of the ingredients, you go figure out how to build it.  
* SOA, EDA - they are not architectures. they are architectural styles

![image](https://user-images.githubusercontent.com/2755263/81185638-108c6680-8f6f-11ea-8c41-db3cafadbf69.png)

#### Architectural styles: Broker

![image](https://user-images.githubusercontent.com/2755263/81185879-5e08d380-8f6f-11ea-86cb-0b9e548ddac7.png)

![image](https://user-images.githubusercontent.com/2755263/81186294-de2f3900-8f6f-11ea-907e-f2fb911e006f.png)


![image](https://user-images.githubusercontent.com/2755263/81190166-b4c4dc00-8f74-11ea-8eca-038644da3a58.png)


![image](https://user-images.githubusercontent.com/2755263/81190757-75e35600-8f75-11ea-9a39-ed8d36f8ef04.png)


![image](https://user-images.githubusercontent.com/2755263/81301813-c8d11200-9036-11ea-842a-b234a3d755fb.png)

![image](https://user-images.githubusercontent.com/2755263/81302078-1f3e5080-9037-11ea-9ea5-32b8664a651f.png)


#### Architectural styles: Bus

![image](https://user-images.githubusercontent.com/2755263/81302863-26b22980-9038-11ea-9e7c-c6136293eaa7.png)

EX: PCI bus -> the problem is trying solve, the other thing might not be there ex: hard-drive, floppy-drive
* Each ethernet card has physical mac address. But the IP address are logical 
![image](https://user-images.githubusercontent.com/2755263/81303511-046cdb80-9039-11ea-83da-14de2596ae1d.png)

![image](https://user-images.githubusercontent.com/2755263/81409010-89b8c480-90fb-11ea-8764-101bfd175c3a.png)

* Dump pipes and swart endpoints

![image](https://user-images.githubusercontent.com/2755263/81409490-70fcde80-90fc-11ea-91da-37aab3184711.png)

* EAI was bad. ESBs came to light.

![image](https://user-images.githubusercontent.com/2755263/81409621-a73a5e00-90fc-11ea-80b0-4cf5d22537bd.png)

![image](https://user-images.githubusercontent.com/2755263/81409961-3e9fb100-90fd-11ea-8823-51295eb42ff6.png)

* MDB -> Message driven beans
* New JMS pushed towards broken styple

![image](https://user-images.githubusercontent.com/2755263/81410450-f92fb380-90fd-11ea-8e33-4f83d3e953c6.png)

#### Architectural styles: Bus vs Broker

![image](https://user-images.githubusercontent.com/2755263/81410555-2da36f80-90fe-11ea-8505-74f37c413dfe.png)

* Its not about vs -> You liked need both approaches for a project 

![image](https://user-images.githubusercontent.com/2755263/81410708-6cd1c080-90fe-11ea-8f77-51c4010f4ba3.png)

![image](https://user-images.githubusercontent.com/2755263/81413357-8412ad00-9102-11ea-9292-48122c28becc.png)

![image](https://user-images.githubusercontent.com/2755263/81413850-5f6b0500-9103-11ea-857b-c8850bd825e1.png)

## Intro to SOA

## Intro to SOA
![image](https://user-images.githubusercontent.com/2755263/81568290-cc2c0c80-935a-11ea-8425-90795fc2dbd5.png)

#### SOA tenets

![image](https://user-images.githubusercontent.com/2755263/81568485-16ad8900-935b-11ea-9fe3-3bc2af14611d.png)

![image](https://user-images.githubusercontent.com/2755263/81568920-b539ea00-935b-11ea-8fc6-bb7265ddc890.png)
* Communication about policy lenent - physical layer -> ex: json over AMQP or xml over AMQP or this encryption over other encryption 
* SOA started, at the same vendors gathered in a parallel track with web-services consortium 
* web-services meant to solve vendor interoperability 
* SOA and web-services total accident of naming.
 
![image](https://user-images.githubusercontent.com/2755263/81569638-c6372b00-935c-11ea-8bc0-586dc9e6b55d.png)

![image](https://user-images.githubusercontent.com/2755263/81570777-4ad67900-935e-11ea-84cc-48afa0d3a424.png)

* Encapsulation for micro-service

![image](https://user-images.githubusercontent.com/2755263/81571111-bf111c80-935e-11ea-812e-f5fc93d99c27.png)

![image](https://user-images.githubusercontent.com/2755263/81571205-dbad5480-935e-11ea-8072-d13724f1d88f.png)

#### Service example
![image](https://user-images.githubusercontent.com/2755263/81571686-87ef3b00-935f-11ea-94eb-7cab5af1ee63.png)

![image](https://user-images.githubusercontent.com/2755263/81571840-b1a86200-935f-11ea-8aa5-61333fb29907.png)

![image](https://user-images.githubusercontent.com/2755263/81571893-c553c880-935f-11ea-980a-c5e86fe7371f.png)

* Events flow in bi-direction. There isn’t any single direction. They are more peer model than the hierarchy.
* There is no hierarchy in Services too.
 
![image](https://user-images.githubusercontent.com/2755263/81572301-46ab5b00-9360-11ea-81e8-1c92059fa501.png)

* Make things obvious in the retrospective but non-obvious before we see the solutions

![image](https://user-images.githubusercontent.com/2755263/81699538-be42be00-9424-11ea-9668-334d40640c30.png)

* One of ways to find the right service boundaries has to with UI

![image](https://user-images.githubusercontent.com/2755263/81699928-3a3d0600-9425-11ea-8bf0-f30ea1692f4c.png)

* What if this page doesn’t exist on any single service
* What if this page is single software artifact 

![image](https://user-images.githubusercontent.com/2755263/81700126-7ec8a180-9425-11ea-96d7-2dea5997eeb1.png)

![image](https://user-images.githubusercontent.com/2755263/81700262-ab7cb900-9425-11ea-960a-c5083e229483.png)

* Think of it as widgets -> Each widgets live in its own source control repository 

#### Q&A

```
We’ve got rid of the big bucket of mud. How do we stop getting a bucket of spider's webs?

Because there are events and there’s messaging in between. Obviously somebody’s business process is also taken into account.
I’ve got object A, and object B, give me object C, which is matching something compatible between the two.

UDI: A service is not system. A service is responsible for its data/information and possibly other apps.

The number there, 7, 8, 10… What chunk of the business would you say it is?
We have way too many services, and everybody knows that, especially in the piece of software that we outsourced to some consultants.
They took it too far, and we have a huge amount of services, all of them for a small piece of thing.
So when you talk about the number of services, it’d be very nice to know what kind of context would you put that number on.
Yeah. In this case all of these very small services have their own data storage, and everything is completely separate.
In this case every aggregate root has its own service. It’s a horrible mess.
Is there an element of eventual consistency then between services when they’re talking to their database.
Does that help to find the boundary if it’s acceptable to be eventually consistent between the boundaries?

UDI: By doing UI layer composition, we can let the data live on each service instead of doing pub-sub which workaround for request-response . 

A scenario I was thinking of is when you want to do something in a service that is the source of the truth of data, but it’s blocked by some reference in another system.
Say you want to withdraw a product but you’ve already got orders in flight. Something like that. In that case, the state of the system is in messages.
Sometimes a requirement might come in, and you need to catch up. You have to suddenly move the lines a bit.
You’re gonna talk about performance later, so I’ll hear your views on that and   then I’ll ask the question.

UDI: We constantly reevaluating our boundaries. 
```

![image](https://user-images.githubusercontent.com/2755263/81821288-edbdfd00-94ee-11ea-98ee-79c43f6b58c6.png)

* Performance 
```
You’re gonna talk about performance later, so I’ll hear your views on that and   then I’ll ask the question.
Still thinking about it, it’s OK.
I think Netflix has got a similar approach, they’re doing the exact same thing, but it’s kind of dependent on the device you’re on.
So instead of making a dozen of requests they have a service that sits on top of it and works for the type of device you’re on.. It’ll do the exact same thing.
I’m trying to understand what this means in the big scale of things. I’m talking about the UI, widget composition.
We’ve been trying that with web components. I get how you can make that work, because essentially the user aggregates this information, but what if there’s no user?
It’s actually a calculation process that needs to make a complicated business calculation using lots of data.
Doesn’t that need to know what data to get? How can they be autonomous if they are part of an “equation”?
```
![image](https://user-images.githubusercontent.com/2755263/81823609-b69d1b00-94f1-11ea-816c-40ecb2a10fb4.png)

![image](https://user-images.githubusercontent.com/2755263/81823837-fbc14d00-94f1-11ea-8701-dc2dc959c60c.png)

![image](https://user-images.githubusercontent.com/2755263/81823973-290dfb00-94f2-11ea-9fcf-b2383f231744.png)

![image](https://user-images.githubusercontent.com/2755263/81824277-86a24780-94f2-11ea-838b-0b36ff839c89.png)


#### Services modelling: Workflows, boundaries and business capabilities

![image](https://user-images.githubusercontent.com/2755263/81939733-f0cef100-95b3-11ea-9713-8b9fbd9a9ee7.png)

![image](https://user-images.githubusercontent.com/2755263/81939872-24118000-95b4-11ea-8bf2-966b34a31fac.png)

* Service team own the data across the stack

![image](https://user-images.githubusercontent.com/2755263/81941014-7f903d80-95b5-11ea-9242-b8856f6e8f9f.png)

* OrderId has been created first 

![image](https://user-images.githubusercontent.com/2755263/81941195-b8301700-95b5-11ea-9691-1682f239a9aa.png)

![image](https://user-images.githubusercontent.com/2755263/81941218-c120e880-95b5-11ea-8da1-06c51a3a41a6.png)

![image](https://user-images.githubusercontent.com/2755263/81941427-0c3afb80-95b6-11ea-90c7-3788b64f332f.png)

* Tradicional model
![image](https://user-images.githubusercontent.com/2755263/81942108-ed893480-95b6-11ea-8ba4-325ff2587655.png)

* Another way to model this is to invert the direction or dependency

![image](https://user-images.githubusercontent.com/2755263/81942501-68eae600-95b7-11ea-97be-f81870f2396a.png)

* OrderId has been created first from the workflow
* The central identifier  has to be created much earlier in the workflow
* This why we don't have to send much data-copy

#### UI composition and Branding service

![image](https://user-images.githubusercontent.com/2755263/81943824-1a3e4b80-95b9-11ea-85c6-9733ab0d6bf5.png)

![image](https://user-images.githubusercontent.com/2755263/81944345-dc8df280-95b9-11ea-8c27-8ce8869cdf02.png)

![image](https://user-images.githubusercontent.com/2755263/82060246-5b4f6200-9684-11ea-9dbf-1b0a8d429e39.png)

```
I was wondering who owns it, who gives you the original page and who owns the whole workflow.
Because it seems like UI is actually doing the workflow and has the business logic for that, because none of the services are doing it.
So Branding knows about all the services?
I buy that you can do that, but wouldn’t the team that’s responsible for the service for all the platforms, build all the UI, all the widgets?
Because you have to support mobile, Android, iOS, Web and couple of other thick clients, where the data which belongs to this service will be exposed and shown.
Imagine the project is in your TFS source control, where you actually cannot build the stuff yourself, but you have lots of snippets and stuff that should be built when the actual application is being built.
You get a real challenge to mock up everything to see. How can I make shell for iOS to see if it renders my service stuff properly?
At build time, their stuff will have to check out my project and build that stuff. How should that work? Can you walk me through that?

```

![image](https://user-images.githubusercontent.com/2755263/82061071-779fce80-9685-11ea-99c5-eaea728901b7.png)

#### IT/Ops service

![image](https://user-images.githubusercontent.com/2755263/82061507-090f4080-9686-11ea-947f-432ebe84bb6c.png)

![image](https://user-images.githubusercontent.com/2755263/82061527-0f9db800-9686-11ea-86e7-5ccfbcac2011.png)

```
I’m fine with the different services: Sales, Billing, and stuff, and the Branding service which doesn’t talk to them all, it gets the data from all.
How is IT/Ops a service? How is a connection string part of the service, when they all can’t do anything without it?
Is there IT/Ops service in the sample code?
Is it transactional? Because something may fail on the line.
Will you have a service URL somewhere here?
Or would it just be messages across the bus?
And the URL will be in the app.config for the IT/Ops?
```

![image](https://user-images.githubusercontent.com/2755263/82062268-1a0c8180-9687-11ea-9bf9-2b1328883e1f.png)

![image](https://user-images.githubusercontent.com/2755263/82062418-504a0100-9687-11ea-9bee-c041697fbaed.png)

* This looks like hub-and-spoke model

#### Exercise: services modelling (hotel) - overview















