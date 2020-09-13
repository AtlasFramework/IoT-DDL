# IoT Device Description Language (IoT-DDL)
IoT-DDL is an XML-based human- and machine-readable configuration scheme to describe a thing in IoT in terms of inner components, identity, capabilities, resources, attachments and services. The IoT-DDL also describes the knowledge (social bonds and relationships) injected or acquired by the thing, as well as the different interactions that engage the thing with cloud platforms, edges, users (e.g., end-user, developer) and space-mates (nearby things or remote ones). 
<br />
A thing in an IoT ecosystem, as illustrated in the figure below, is a composition of a set of resources, entities, services, and attachments that work together to provide various interactions and are defined through a set of attributes and properties that influence essential internal services. A thing’s resources describe the shared components that a thing requires to be part of the IoT (e.g., network module, memory unit). A thing’s entities define the different hardware and software components that allow a smart space and its things to interact with it. These individual interactions are represented as services, functions with well-defined interfaces (APIs) that can be utilized by users or other things. A thing may also offer additional interactions through external attachments, or cloud-based resources that offer additional services (e.g., log server, database, dashboard).
<br />
Such configuration schemes are created by the thing vendor or owner and this then gets uploaded to the thing to enable the thing to self-discover its own power and engage with the surrounding IoT ecosystem.


<p align="center">
  <img src="https://github.com/AtlasFramework/IoT-DDL/blob/master/Resources/ThingTaxnomy.jpg" width="700" height="550" title="The Architecture">
</p>


## Access the latest version of the IoT-DDL Builder:
> - [Use this tool to build an IoT-DDL file for your Atlas thing.](https://atlasframework.github.io/IoT-DDL/DDL_Builder/builder.html)
> - [Example for a Coffee Machine IoT-DDL.](https://github.com/AtlasFramework/IoT-DDL/blob/master/Resources/Coffee_Machine_IoTDDL.xml)


## Read more about IoT-DDL through the following paper:
> - Khaled, Ahmed E., Abdelsalam Helal, Wyatt Lindquist, and Choonhwa Lee. [IoT-DDL–device description language for the “T” in IoT.](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8334820) IEEE Access 6 (2018): 24048-24063.


## Check the other parts of the framework:
> - [Atlas Thing Architecture.](https://github.com/AtlasFramework/Atlas-Thing-Architecture)
> - Inter-Thing Relationship Framework
> - Runtime Interactive Development Environment
 
 
