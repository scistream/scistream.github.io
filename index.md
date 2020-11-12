---
layout: default
---
[Home](index.html) | [Papers](papers.html) | [Participants](participants.html) | [Resource](resource.html) | [News](news.html)

# About

__SciStream__: _Architecture and toolkit for data streaming between federated science instruments_ project is fund by the U.S. National Science Foundation's CC* Integration-Large program. 

# Project Overview 
Technological advancements enable scientific instruments to generate data at unprecedented rates. 
However, data are often processed at a rate far below the capability of the instruments leading to either operating the instruments at a lower data rate (e.g., detectors at light sources); and/or discarding a (significant) portion of the data without processing (e.g., cosmology simulations).
To alleviate these issues, we propose to  design and implement solutions for efficient and secure memory-to-memory data streaming between geographically distributed and federated scientific instruments. 
Lack of direct external network connectivity for scientific instruments,  mismatch of authentication and security requirements between batch and stream processing, and absence of the software stacks and tools for accommodating data streams are the key challenges in providing such capability. 
We propose to (1) develop an architecture to enable data streaming from a producer’s memory at one facility to a consumer’s memory at another remote facility through a small set of gateway nodes at both facilities; (2) create protocols to establish authenticated and transparent connection between producer and consumer via gateway nodes; (3) build on our current prototype and develop additional tools to realize the proposed architecture in an operational environment and develop APIs to facilitate data streaming.

# Our mission
Through the exploration of architectural and design choices and addressing issues of control protocols and security, the proposed work will advance the understanding of the challenges in supporting memory-to-memory data streaming between remote instruments in federated science environments. 
The successful implementation of this project will not only 
advance the state-of-the-art in data streaming between a data producer and a remote data consumer for a broad range of applications in scientific environments, but also will uncover new challenges and spur further research in this area. 
Through a reference architecture and best practices guide, the project will help the campuses support stream processing in a secure and robust fashion.  
As a crucial element for enabling near-real-time analysis of high-speed data, this project will help advance both experimental and computational steering. 
By removing the storage and file systems (and their associated bottleneck) in the critical path, this project  not only will help improve the performance of distributed science workflows but also will help increase the utility of expensive science instruments. The team has a strong record of developing and delivering high-quality software for the scientific community.

# Broader
__SciStream__ will benefit all scientific applications that require memory-to-memory data streaming between federated science instruments. 
Scientific applications require such a capability for near-real-time analysis of large-scale data from expensive experiments and simulations to steer them to collect useful data and to minimize the amount of data discarded because of storage limitations. 
Recent trends in scientific instruments and data-intensive science workflows suggest that the number of such applications will grow. __SciStream__ will help significantly reduce the time to solution for these applications, resulting in far-reaching benefits for society.
We will engage with a scientific user facility, two university research computing centers, and science champions in two scientific disciplines to validate the software developed, promote it within their communities, and develop case studies to reach a wider audience. 
Through conference presentations and tutorials, the project will disseminate project results and provide training to enable a broader community to leverage the project software. 
In addition to open sourcing the software resulting from this project, we will encourage community contributions and will maintain the GitHub repository with appropriate quality control. 
Such an activity, we believe, can serve as a starting point for follow-up research and help grow a community of researchers in this area, thereby sustaining the project software into the future. 
The project will train undergraduate and graduate students in high-performance data streaming in federated science environments through coursework and programming assignments.
