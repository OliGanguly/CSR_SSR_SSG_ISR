## What is CSR SSG SSR ISR
# CSR_SSR_SSG_ISR
New web dev terms
- CSP: Client side rendering
- SSR:Server side rendering
- SSG:Static site Generation
- ISR:Incremental static Regeneration


```bash
  Sorce Code [write code in local]->
  Build [Write code in server]->
  Server [store the code in server]->
  Client[Requesting web page]
```

* CSR: Client side rendering
```bash
1. Build phase -> HTML , CSS , JS Kept seperately 

2. Server phase ->  HTML , CSS , JS stored seperately in server.

3. Clint -> A blank html page send to the client , after this it throws some JS to the client ,
         Once the js reaches to the client , Now its job is to render the webpage, if it requires some Js it 
         requests to the server again.
```
* SSR: Server Side Rendering
```bash
1. Build phase -> HTML , CSS , JS Kept seperately 

2. Server phase -> Rendering happing in server side instead happing
in client side.EveryTime Clent send a Req a new web page created , rendered on the server and throw it to client.

3. Clint -> Request is being sent from client to server , Server
takes the req, download all info, data from DB , paints a page and sent back to client , so toatl html, css , js go to the Clint in one go.
```
* SSG: Static Site Generation
```bash
1. Build phase -> Generate Each web page in Build phase

2. Server phase -> Pages are stored in server

3. Clint -> Client send req to server , Server send back the webpage
so when there is new build happen you will get updated content.
```

* SSG: Incremental Static ReGeneration
```bash
1. Build phase -> Generate Each web page in Build phase
But ISR says Every after sometime a build phase will happien
2. Server phase -> Pages are stored in server

3. Clint -> Client send req to server , Server send back the webpage

```
![SCR,SSR,SSG,ISR1](https://github.com/OliGanguly/CSR_SSR_SSG_ISR/assets/82031303/bfc10bb9-96e5-4c76-8df1-1dc762994fbb)
![CSR,SSR,SSG,ISR](https://github.com/OliGanguly/CSR_SSR_SSG_ISR/assets/82031303/baf14eba-686d-4c3c-8db5-c98a9402f414)





