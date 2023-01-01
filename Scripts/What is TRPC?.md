Hey dev.

Do you know about RPC? If not make sure to checkout my previous RPC video. Because in this video we are going to talk about TRPC.

You also may have seen my previous video about GRPC as well. Well TRPC has nothing to do with GRPC. 

TRPC is a flavour RPC. It relates to the RPC concept of dealing with API's. So the idea is rather than sending let's say a HTTP request with Axios. What TRPC allows you to do is expose functions from one system to another and call those functions as if you were part of that system. 

So lets thimk of a frontend and a backend. Now instead of you making that axios request. You would setup what coulld be considered a "contract" of sorts between these two systems. So define a function on the backend and call it on the frontend and get it's response. This does not require any code generation and is all done using Typescript.

This creates a full typesafe environment between both your frontend and backend. Now there are some pros and cons but let me know what you think in the comments.

If you enjoyed this video make sure to follow my page and checkout my Twitch channel to get more content like this.

