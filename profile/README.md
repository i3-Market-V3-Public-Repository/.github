 # Welcome to the i3-MARKET Backplane
 
![i3-market-logo](https://github.com/i3-Market-V2-Public-Repository/.github/blob/main/profile/i3-market-logo.png)

### Free* Open Source Software Tools for SMEs, Developers and Large Industries Building/Enhancing their Data Marketplaces.
### www.open-source.i3-market.eu
### https://www.i3-market.eu/
### https://i3-market.gitlab.io/code/backplane/backplane-api-gateway/backplane-api-specification/index.html

#### We Present here the Release 3 of the i3-Market Backplane Solutions

#### Intelligent, Interoperable, Integrative and deployable open source MARKETplace backplane Tools for easy deployment of DaaS and a platform to support online data marketplaces.

## i3-MARKET Backplane – Short Description

Data is changing the way people understand society, Data is mobilising all industry sectors to be more competitive, productive and aware of technological problems, every day more Data is available directly from the sources i.e. sensors, smart devices, manufacturing systems, etc. The Data has an estimated value considering the different characteristics and also the purpose for which the data is collected for, this large amount of Data has an inherent value which has been for long time unexploited or in hand of intermediaries.

The i3-MARKET project is a consortium of diverse 14 partners, from large industries and system integrators, SMEs associations and research organisations, and different EU countries that collaborate to address common challenges in the area of Big Data technologies. We are a cluster of experts performing multiple activities, from coordination and management to technical design and software development, that all together bring the know-how and the expertise in building the i3-MARKET backplane solution based on high quality standards.

The i3-MARKET project addresses the challenge of being integrative following design methods used in industry and OSS implementation best practices, interoperable by using semantic models that defines a common conceptual framework and information model that enables cross domain data exchange and sharing, intelligent from the perspective of smart contracts generated automatically and associating those financial operations into a set of software tools that facilitate that data assets can be commercialised via intra-domain or cross-domain almost transparently in a secure and protected digital market environment.

The i3-MARKET consortium is happy to present its software in the form of a backplane with a set of software support tools and as a solution addressing the challenge of enabling the coexistence of dataspaces with marketplaces for enlarging the European Digital Market Ecosystem. The i3-MARKET project has built a blueprint open source software architecture called “i3-MARKET Backplane” (www.open-source.i3-market.eu, https://www.i3-market.eu/, https://i3-market.gitlab.io/code/backplane/backplane-api-gateway/backplane-api-specification/index.html) that addresses the growing demand for connecting multiple data spaces and marketplaces in a secure and federated manner. i3-MARKET consortium is contributing with the developed software tools to build the European Data Market Economy by innovating marketplace platforms, demonstrating with three industrial reference implementations (pilots) that a decentralised data economy and more fair growth is possible.

![i3-market-architecture](https://github.com/i3-Market-V2-Public-Repository/.github/blob/main/profile/i3-market-architecture.png)


## i3-MARKET Backplane Architecture

The i3-MARKET architecture design provides adequate and in-house developed building blocks for trustworthy (secure and reliable), data-sharing and exchange of existing data assets for current and new future marketplace platforms, with special attention on commercialising data assets from individuals, SMEs or large industrial corporations. We use and develop open source technologies that impulse the adoption and exploit the open source culture, a tendency that form more than a decade is hitting the industry markets and that today more and more industries are following.

i3-MARKET Architecture Level 1 or backplane access is composed by the basic functionalities i3-MARKET platform uses to operate and provide core services, 

The Backplane Gateway System is the building block in charge of offering to all participants and marketplaces access to the Operation Backplane services via APIs. The goal of the Backplane API is therefore twofold: on one hand, it serves an integrated API endpoint for all the i3-MARKET services offered by i3-MARKET and implemented in the respective building blocks and on the other hand, it provides secure mechanisms for preventing not allowed accesses. 

The Data Access System is the building block in charge of allowing data consumer obtain access in a secure and protected manner to the data offered by the data providers. 

The Trust, Security and Privacy (TSP) is the building block in charge of providing the self-sovereign identity, access management, contracting, consents, accounting and payments blockchain-based solutions managed in the i3-MARKET system in order to guarantee the desired levels of trust, security and privacy for federated data markets. 

The Data Storage system is the building block in charge of storing common data shared across all participants instances.

The Semantic Engine System is the building block in charge of providing the needed semantic data models for make possible the consumers and applications understand the meaning of the data exchanged between different stakeholders. Apart from that, the semantic engine will allow the participants to taking advantage of this semantic data models by means of providing a metadata management in charge of registering offering and performing queries for discovery purposes. 

i3-MARKET Architecture Level 2 or backplane operations allows the subsystems of i3-MARKET to be isolated and not exposed publicly, so that they can only be accessed by the Backplane or other Level 1 subsystems. External connections are all handled by the Backplane Level 1, making connection security and encryption simpler and thus services are optimised and executed easily and more straightforward. The design of the Backplane Level 2 functionalities makes that data spaces and marketplaces can use of backplane functionalities more easily, scalable and replicable, making the addition of new backplane instances transparent for both the subsystems and the clients.

(The i3-Market Backplane solutions are also available as open-source in GitLab at https://gitlab.com/i3-market-v3-public-repository)
