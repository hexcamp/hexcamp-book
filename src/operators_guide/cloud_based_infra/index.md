# Cloud-Based Infra

The goal of the project is to move computing resources and storage away from the cloud and host it locally, often in community member's homes on small computers such as the Raspberry Pi.

But in order to keep things simple, safe and performant, we still use a small amount of cloud-based resources.

It might be possible to run entirely on hardware resources that are located within residential networks. However, it makes the setup more complicated as each wifi router would need to be configured to run port forwarding for services such as HTTP, HTTPS and DNS to small servers located inside the home.  Different Internet Service Providers will use different wifi routers, which might not support everything needed, and would be difficult to document the setup.

It would also be necessary to advertise the home IP addresses via DNS, and those addresses would be exposed in such a way that they might become a target for malicious traffic from the internet, such as DDoS attacks (Distributed Denial-of-Service).  


