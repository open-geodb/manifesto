# manifesto version 0.0.1

**Manifesto for the modern open source geospatial stack**

This is a manifesto for the creation of a **modern open source geospatial** stack. It will not spacify the technology but rather specify the purpose for each part of the stack. So from that perspective this may be seen a versioned specification.

The **modern** in the context of a modern open source geospatial stack refers to the demands of distributed systems (e.g. micro services, cloudnative, hybridcloud), big data and machine learning. Traditional GIS has generally not addressed these topics and they have remained in the sphere of computer science.

Although I call this a stack since it has layers where higher layers depend on the lower layers it is in-fact a mix of a stack and [distributed achitectural pattern](https://martinfowler.com/articles/patterns-of-distributed-systems/). Since some layers sit adjacent to other layers and may be run in issolation as a service or a microservice

# Stack Layers

## Common

This is the base layer of the stack

- Infrascturcture: Servers and Networks
- Distributed Filesystems
- Distributed Databases
- Data Lakes and Warehouses
- Replication
- Access Control
- Distributed Query Alogrithms
- Query Processing Systems


## For Applications Developers

- Configuration management tools
- Applications (APIs)
- User Interfaces (Frontend libs)

## For Data Science

### For Training

- Pretrained Model access
- Training GPUs Resources

### For Data Wrangling

- Query Processing Systems
- Data Pipelines (ETLs)

### For Inference

- Publish Models to API

## For DevOps & MLOps

- Data Pipelines
- Big Data Stacks
- IaaC tools
- Configuration management tools

## For Analysts

- NoCode Tools
- Basic SQL
- Dashboarding Tools

