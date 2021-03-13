# Kubenretes-industry-use



Kubernetes is one of the fastest growing DevOps tool and that is based on containerization technology and thus it is used to utilized the physical resources i.e. The Computing Unit (RAM and CPU) and Storage Unit (Hard disk) to their fullest.
A little History
The technology upgradation for provisioning of Operating Systems started back in 2008 when virtualization technology came into picture
Virtualization: By utilizing the same set of physical resources we were now able to launch more than one OS by using a hypervisor just above physical devices. This felt kind of amazing in the start but when it came to performance then there were some drawbacks of using Virtualization.
Even after using the drivers like Intel VT-x and AMD-v we need too much of resources to run our application . We are using a lot of resources for installing different OS but our need was only to run applications in the OS.

Containerization: This is where a need of new technology like containers came .In containers, we make use of resources directly from a bare metal setup or a Virtual machine and by making use of engine , we distribute the resources directly to the new OS to be launched.
So where is Kubernetes ?
As mentioned earlier , Kubernetes is based upon containerization technology. So making use of Kubernetes we can provision new operating system for running our applications in collaboration with DevOps methods and thus making our need of automation a success. This is why K8s is also known for being an Orchestration tool
Why Kubernetes ?
Kubernetes has many benefits over the former container only technology when it comes to application specific needs
Container in Pods

By making use of pods as a wrapping layer we can take fully control over resources , Images , needs and even monitor our OS running in various containers
2. One Single Interface to Every container Technology

Although docker is the first to come up with container technology but Kubernetes also supports a lot more engines than only docker .
The best part is we don’t have to know domain specific commands for each container technology , knowledge on Kubernetes commands and any one technology is more than enough.
3. Easy to scale , manage and deploy
Using Kubernetes we can scale our applications , update them any time using some deployment strategies, can roll back if wanted and everything is done within some minutes or even seconds
4. Has Capability of Multi-Node Cluster Setup

To avoid SPOF(Single Point Of Failure) make use of a number of nodes and avoid data loss due to system failure. This will be a huge business loss to the company if any single data is lost.
Kubernetes has a lot of benefits. Its time to see how Industry utilizes it.
Industry Use Cases
There a number of companies who have been upgraded to K8s and adopted the DevOps standards make them a more powerful than their competitors
Spotify

Spotify: Case Study
Spotify being world’s most famous music streaming platform with a record of 74 million users in 2020.
“Our goal is to empower creators and enable a really immersive listening experience for all of the consumers that we have today — and hopefully the consumers we’ll have in the future” says Jai Chakrabarti, Director of Engineering, Infrastructure and Operations.
Spotify started its Helios platform with the adoption of microservices and Docker but later around 2017 it was realized that something better than as small community is needed so they extended their flaws to K8s
Kubernetes was more feature-rich than Helios. Plus, “we wanted to benefit from added velocity and reduced cost, and also align with the rest of the industry on best practices and tools.” At the same time, the team wanted to contribute its expertise and influence in the flourishing Kubernetes community. The migration, which would happen in parallel with Helios running, could go smoothly because “Kubernetes fit very nicely as a complement and now as a replacement to Helios,” says Chakrabarti.
For more information follow the Spotify Case Study | Kubernetes
2. IBM

IBM: Case Study
IBM Cloud is very well know for offering public ,private and hybrid cloud based services. IBM had already adopted Kubernetes as a service in the form of IKS but they themselves implemented K8s for setting up a private and secure registry on their cloud.
Around Feb 2018 they came up with this image trust service, called Portieris. Users can now create image security policies for each Kubernetes namespace, or at the cluster level, and enforce different levels of trust for different images.
The offering is that image registry server runs in IBM’s cloud, and then Portieris runs inside the IKS cluster (IBM K8s). Thus users can use their custom images also proper verification.
For more information follow the IBM Case Study | Kubernetes
3. OpenAI

OpenAi : Case Study
OpenAI is a Robotics and gaming based company which runs its various applications both in Clouds and in its own data centers, depending on which cluster has free capacity.
“We use Kubernetes mainly as a batch scheduling system and rely on our auto scaler to dynamically scale up and down our cluster,” says Christopher Berner, Head of Infrastructure. “This lets us significantly reduce costs for idle nodes, while still providing low latency and rapid iteration.”
This profited the company in very huge ways but saving and utilizing the most out of resources.
For more information follow the OpenAI Case Study | Kubernetes
4. Babylon

Babylon: Case Study
Babylon is a ML and AI based company which offers various application . Babylon is designed to work like a doctor’s brain using its AI and ML powers. While a doctor can serve one patient at a time , Babylon can work with millions.
Being a AI/ML practitioner they definitely needed lots of computing power also which could help their servers. So they moved to K8s
“We tried to create a Kubernetes core server, we deployed Kubeflow, and we orchestrated the whole experiment, which ended up being a really good success” says AI Infrastructure Lead Jérémie Vallée.
This way the team became self-service AI training platform on top of Kubernetes.
For more information follow the Babylon Case Study | Kubernetes
Kubernetes is a great tools every IT industry is moving forward to it and making a lot of profit . Recently RedHat had already came up with OpenShift which also overpowered K8s 
