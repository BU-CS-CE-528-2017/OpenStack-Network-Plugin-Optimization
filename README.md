# OpenStack Network Plugin Optimizing Performance

Software based networking infrastructure is a major component of cloud infrastructure along with cloud compute and storage infrastructure. Workloads such as cryptography, deep packet inspection (DPI) and delay sensitive traffic transmission (such as video and financial data) require high performance networking. OpenStack provides cloud based networking services (layer 3 networking services includes NAT, static routing, etc.). Some OpenStack use cases require highly performant networking services. 

It is often difficult to predict what level of performance a user can expect for some targeted applications they would like to run in a given environment. Especially in a public cloud environment (like OpenStack) where users have no control of the underlying system.The overall performance achievable is dependent on multiple factors and not trivial to model across multiple components, interconnects and software packages. OpenStack’s networking service, Neutron, becomes a bottleneck with larger workloads. In such a situation, within the deployment the User is in a fix whether to rely on the default Neutron services or to invest in expensive hardware tools. Wouldn't it be great if the application user of OpenStack would know if his application requires expensive hardware router or it can be managed by default software itself ensuring no degradation in performance.

The Repository contains the Project Proposal which contains detailed information about the project including the project goals, Scope and features of the project, and other details. 

* Short project-cloud introduction video: https://www.youtube.com/watch?v=uPMrOnTrF0g
* Cisco Cloud CTO, Lew Tucker cloud computing overview: https://www.youtube.com/watch?v=olnLpuUDZv8
* Cisco OpenStack Router Overview: https://www.youtube.com/watch?v=MtCRx8F52kc

### Repository Contents
You can clone the Repository to be able to view and see all the contents. 

Pre-requisites:
DevStack for OpenStack with Neutron is a requirement for this project.

INSTALLATION:
Since our project was based on OpenStack. We have penned down a complete documentation on how to correctly deploy DevStack for OpenStack. The document contains all the steps to be followed and some common errors have also been addressed.

Some OpenStack Python codes have been analyzed and put in. For complete information: https://github.com/openstack/neutron

In order to try the web UI created by us for linking to KloudBuster, these are the requirements to OpenStack:
- Neutron networking
- Admin access to the cloud under test (non-admin might work with some tweaks and limitations)
- 3 available floating IPs if running the HTTP data plane scale test
- 2 available floating IPs if running the Storage scale test

For complete documentation to KloudBuster refer: http://kloudbuster.readthedocs.io/en/latest/readme.html

## Mentors
- Sridar Kandaswamy (CISCO)
- Bob Melander (CISCO)
- Dipa Thakker (CISCO)

Special thanks to:
- Shweta Padubidri (CISCO)
- Yichen Wang (CISCO)

## Developers
- Aastha Anand
- Chaitanya Kulkarni
- Gabrielle Belok

