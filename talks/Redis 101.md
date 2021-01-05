# Redis 101- Getting Started with Redis by Kyle Davis of Redis Labs - RedisConf 2020
* https://www.youtube.com/watch?v=oHPcou3LYXc

![image](https://user-images.githubusercontent.com/2755263/82465298-5c193700-9a7c-11ea-8360-d6db71d36dfb.png)

![image](https://user-images.githubusercontent.com/2755263/82465228-49066700-9a7c-11ea-86f6-44d892edb84a.png)

![image](https://user-images.githubusercontent.com/2755263/82465344-66d3cc00-9a7c-11ea-86db-353c4ffe1c52.png)
![image](https://user-images.githubusercontent.com/2755263/82466147-46584180-9a7d-11ea-97fc-d14817914943.png)

![image](https://user-images.githubusercontent.com/2755263/82466301-76074980-9a7d-11ea-81bf-94d282e0c4e5.png)

![image](https://user-images.githubusercontent.com/2755263/82466321-7c95c100-9a7d-11ea-8a12-d4c4b47137d6.png)

![image](https://user-images.githubusercontent.com/2755263/82466371-8fa89100-9a7d-11ea-8d8c-a26dfc6a867d.png)

![image](https://user-images.githubusercontent.com/2755263/82466412-9df6ad00-9a7d-11ea-914b-0a358d4d07ab.png)

![image](https://user-images.githubusercontent.com/2755263/82466578-d6968680-9a7d-11ea-976a-34aa5dc27362.png)

![image](https://user-images.githubusercontent.com/2755263/82466603-e1e9b200-9a7d-11ea-89dd-6d5d52ab417b.png)

* Note: Redis is single threaded
* DEL - synchronously deletes
* 99% time use UNLINK -> Its more performant since its asynchronous operation 

![image](https://user-images.githubusercontent.com/2755263/82468023-933d1780-9a7f-11ea-8f80-9bbb1698790b.png)

![image](https://user-images.githubusercontent.com/2755263/82468076-a3ed8d80-9a7f-11ea-96ce-d5a20a106146.png)

![image](https://user-images.githubusercontent.com/2755263/82468279-da2b0d00-9a7f-11ea-8372-11aed6fb5e4b.png)

![image](https://user-images.githubusercontent.com/2755263/82468347-f2029100-9a7f-11ea-9a12-a03aa087ca13.png)

![image](https://user-images.githubusercontent.com/2755263/82468495-16f70400-9a80-11ea-8ce9-ccb84f0c2b58.png)

![image](https://user-images.githubusercontent.com/2755263/82468544-25ddb680-9a80-11ea-92e5-45b29a64adca.png)

![image](https://user-images.githubusercontent.com/2755263/82468576-3130e200-9a80-11ea-8131-fe5c0372d739.png)

![image](https://user-images.githubusercontent.com/2755263/82468724-62a9ad80-9a80-11ea-93ef-37cc236072e6.png)

![image](https://user-images.githubusercontent.com/2755263/82468892-908ef200-9a80-11ea-93be-7d1d00ee5886.png)

![image](https://user-images.githubusercontent.com/2755263/82468971-a69cb280-9a80-11ea-8aca-cb5bb00385c5.png)

![image](https://user-images.githubusercontent.com/2755263/82469002-b2887480-9a80-11ea-80a3-95a1dd79c258.png)

![image](https://user-images.githubusercontent.com/2755263/82469073-ca5ff880-9a80-11ea-9c63-43b1f4d06507.png)

![image](https://user-images.githubusercontent.com/2755263/82469154-e6639a00-9a80-11ea-9bae-ea26e54641a3.png)

![image](https://user-images.githubusercontent.com/2755263/82469217-fa0f0080-9a80-11ea-946f-8f4b1bcbb5be.png)

![image](https://user-images.githubusercontent.com/2755263/82469277-085d1c80-9a81-11ea-8430-b5187062258e.png)

![image](https://user-images.githubusercontent.com/2755263/82469467-49edc780-9a81-11ea-990a-ea4262617b38.png)

![image](https://user-images.githubusercontent.com/2755263/82469637-88838200-9a81-11ea-9573-2b2098d9a1fb.png)

![image](https://user-images.githubusercontent.com/2755263/82469765-b36dd600-9a81-11ea-86e5-9db40afc55fc.png)

![image](https://user-images.githubusercontent.com/2755263/82469954-f334bd80-9a81-11ea-856c-7d2b46b2df61.png)

![image](https://user-images.githubusercontent.com/2755263/82470020-09427e00-9a82-11ea-8ce0-993d6facc667.png)

![image](https://user-images.githubusercontent.com/2755263/82470097-211a0200-9a82-11ea-9ee5-09c79793b19e.png)

![image](https://user-images.githubusercontent.com/2755263/82470144-31ca7800-9a82-11ea-8752-0603d73b833e.png)

![image](https://user-images.githubusercontent.com/2755263/82470230-4eff4680-9a82-11ea-9fbb-af2009445c83.png)

![image](https://user-images.githubusercontent.com/2755263/82470369-7d7d2180-9a82-11ea-8578-7e78f70bfb1c.png)

`SMEMBERS` is O(n) - so be careful about it

![image](https://user-images.githubusercontent.com/2755263/82470547-bf0dcc80-9a82-11ea-85b1-5af854f4c43e.png)

![image](https://user-images.githubusercontent.com/2755263/82470576-c634da80-9a82-11ea-8a6a-b8d27bff0dbc.png)

![image](https://user-images.githubusercontent.com/2755263/82470769-fe3c1d80-9a82-11ea-8459-4b17979bcfc5.png)

![image](https://user-images.githubusercontent.com/2755263/82470862-1ca21900-9a83-11ea-8a79-c96ebd51557d.png)

![image](https://user-images.githubusercontent.com/2755263/82471197-9afebb00-9a83-11ea-946a-b1e80dd8e52f.png)

![image](https://user-images.githubusercontent.com/2755263/82471225-a81baa00-9a83-11ea-9693-9b7c41ca62df.png)
![image](https://user-images.githubusercontent.com/2755263/82471535-09dc1400-9a84-11ea-99fc-b52ecf80bda0.png)

![image](https://user-images.githubusercontent.com/2755263/82471599-20826b00-9a84-11ea-817c-a53be972d61d.png)
![image](https://user-images.githubusercontent.com/2755263/82471648-35f79500-9a84-11ea-8074-17870c26605e.png)

![image](https://user-images.githubusercontent.com/2755263/82471707-4ad42880-9a84-11ea-967b-1341fbdec677.png)

![image](https://user-images.githubusercontent.com/2755263/82471822-7a833080-9a84-11ea-96ec-4b02cc58ebec.png)

![image](https://user-images.githubusercontent.com/2755263/82471950-a999a200-9a84-11ea-8f65-8974bc552437.png)

![image](https://user-images.githubusercontent.com/2755263/82471986-b74f2780-9a84-11ea-997a-eda5e56864fb.png)

![image](https://user-images.githubusercontent.com/2755263/82472074-d64db980-9a84-11ea-96c0-087447d38cf0.png)

![image](https://user-images.githubusercontent.com/2755263/82472315-393f5080-9a85-11ea-8504-b79f31e27e43.png)

![image](https://user-images.githubusercontent.com/2755263/82472386-52480180-9a85-11ea-8645-6b23994d46c7.png)

`Pub/Sub` is a capability of Redis. It is not a data-structure 
![image](https://user-images.githubusercontent.com/2755263/82472572-9e934180-9a85-11ea-923c-52b61a402a6c.png)

![image](https://user-images.githubusercontent.com/2755263/82472596-a94dd680-9a85-11ea-8896-ae12f50be332.png)
 
![image](https://user-images.githubusercontent.com/2755263/82472615-b23ea800-9a85-11ea-8ae2-6ffceb9920a5.png)

* Fire and forget model
* Not durable or persistent - if the subscriber is not available, the msg is not received 

![image](https://user-images.githubusercontent.com/2755263/82472921-13667b80-9a86-11ea-9529-236e25b2dfed.png)

![image](https://user-images.githubusercontent.com/2755263/82472997-2da05980-9a86-11ea-9a17-fd348f1c6d48.png)

![image](https://user-images.githubusercontent.com/2755263/82473098-50327280-9a86-11ea-8c00-fb8085709c38.png)


