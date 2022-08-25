## Golang Microservices
These days I studied more about frameworks used in microservice specifically in Golang. I think Go giving a good ease in coding simply makes an excellent platform for microservice
development. There are in fact a lot of tools in go that makes coding easier with code generation and frameworks that easily build production ready microservices thru enforcing their 
own programming practices. Go being close to hardware and its native functionality also makes efficient tools for a microservice lower level technologies like transport layer.

So I took a close look into Go-zero  and the more complex Go-micro.
Go zero has a good principle of api-design first pattern and its super easy to organize your microservices with their structure, I found this similar to Goa which is simple enough and yet it 
has good paradigms while Go micro has a cloud native feels to it. You will probably choose go-micro between the two. However both are easy enough with code generation tools they've got.


**I created this simple services in Go micro**

### GrocerGuy API 
- Greetings
- GetGroceryList
- Call

First you have to install the go-micro cli and having done that it will instruct you to add its dependencies. Then in your local directory add a folder for a project. The microservice that I made
simply has a 2 different call. This means I have only one service for 2 different method. You could do different strategy from this. You could also add more advance and crazy features of go-micro  
as adding its own broker, tracing hosts for each service.



