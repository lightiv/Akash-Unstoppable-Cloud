# Akash-Unstoppable-Cloud
This is the home of SkyNet's deployments to Akash's Decentralized Cloud.  SkyNet fully believes in and supports Akash Network's Decentralized Cloud principles.  We are focusing provide the most flexible onboarding experience that does not necessitate learning an entire new process for standing up your deployments.

## About Akash Network: 

Akash Network is Censorship-resistant, permission-less, and self-sovereign, Akash DeCloud is a faster, more efficient, and lower cost cloud built for DeFi, decentralized projects, and high growth companies, providing unprecedented scale, flexibility, and price performance. Up to 10x lower in cost, our serverless computing platform is compatible with all cloud providers and all applications that run on the cloud.

## Our Mission

We are accomplishing our mission but working off a base SSH enabled Ubuntu image.  The beauty of this is that having this access allows for the ulitimate in flexability. This allows you to commission your deploymet the way you are accustom to without the need to configure using the deploy.yml file via environment variables. I do want to point out the following information provided by Adam Bozanich, CTO Akash Network:
```  
In "container-native" deployment environments you configure things with environment variables.  
12factor.net, especially here: https://12factor.net/config
```  
We will attempt to adhiere to the above principles as much aas possible but ultimately we want to be able to commission our deployments in a time manner.

Our working images are based on the fine work of Coffeeroaser: https://github.com/coffeeroaster/akash-ubuntu

# Optional : build custom Docker image (recommended)

Update Dockerfile for your needed custimizations.
``` 
# Note you can also use the prebuilt image at user994455/ubuntu-base:0.2
$ docker build -t $your_dockerhub_user/ubuntu-base:0.2 .
```  
Update deply.yml to point to your newly built docker image. (or keep the prebuilt image)

## How To Deploy To Akash

You can review our Akash DeCloud deployment cheat-sheet here: https://github.com/lightiv/SkyNet/wiki/Akash-Decentralized-Deployment-Guide
