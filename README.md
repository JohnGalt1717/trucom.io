# trucom.io

A distributed communications system that is designed to replace all forms of digital communications including SMS, chat, instant messaging, video/voice, and email all the while being uncensorable and completely secure.

Anyone can standup a node of Trucom using a simple docker file and contribute to the network which will then auto-discover other nodes in the network and advertise itself.  Each node acts as a proxy for any clients connected to it so that the clients can paricipate in communications with others and act as search nodes on the network.

Each client caches data on the local device AND on nodes in an encrypted fashion.  If a client needs access to data that it doesn't have on the local device it can request it's own data directly from all nodes that meet the criteria of what is needed or send a search request of the network. Then, they system does an overlay and asks the online client to look at the information for which both parties have access, and do a decryption and search on that information dolling out a request for decrypt and search per record to a single known good client.

Clients can run on web, windows, linux, macOS, android and iOS with varying degrees of storage available depending upon platform (and users can further limit storage used on local devices)

No data within the system can ever truely be lost because the system automatically backs up across nodes and ensures that there are always at least 3 nodes on the system with data.  All data is stored in a blockchain to ensure that the data is not tampered with and each node works to maintain concensus of the data.  Each client is simply caching a small subsection of the block chain and whenever a record is returned by the search, the record information is checked by the node for both access and validity before returning to the requestor.

This system can also function for websites and other static and dynamic content and has a complete monetization system to allow people creating websites to be able to pay for hosting space across the distributed network including audio and video streaming.  Within that environment, trust can be confirmed and cyrptographic keys can be issued to handle decryption and streaming of content on behalf of the original party which can of course be revoked at any time by the original party as well which will disable their access to the data going forward.
