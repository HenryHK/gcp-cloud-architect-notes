# Google Cloud Architect Learning Notes

This learning notes contain notes of my google cloud architect certification learning.

This notes is accurate as of it's published.

- [Google Cloud Architect Learning Notes](#google-cloud-architect-learning-notes)
  - [Pre-requisite Knowledge](#pre-requisite-knowledge)
    - [Methodologies of application development](#methodologies-of-application-development)
    - [Service models of cloud computing](#service-models-of-cloud-computing)
  - [Google Cloud Platform Basics](#google-cloud-platform-basics)
    - [Products and services](#products-and-services)
      - [Access management](#access-management)
      - [Compute](#compute)
      - [Storage](#storage)
      - [Networking](#networking)
      - [Stackdriver](#stackdriver)
      - [Tools](#tools)
      - [Big Data](#big-data)
      - [Artificial Intelligence](#artificial-intelligence)
      - [Other](#other)

## Pre-requisite Knowledge

Before going into the google cloud architect learning, one should have a basic yet solid understanding of how application is developed, published and managed. Google cloud provides a platform to enbrace these methods.

### Methodologies of application development

* Monolithic application design

* Container based development and deployment

* Microservice architecture

* Serverless architecture

* Application supporting technologies, e.g. message queues

* Database and other storage technologies, e.g. blob, SQL, NoSQL

### Service models of cloud computing

| Name/Characteristics | Infrastructure as a service                              | Platform as a service                                                                                              | Software as a service                                                              | Serverless Computing                                                                                                         | Kubernetes as a Service                                                       |
| :------------------- | :------------------------------------------------------- | :----------------------------------------------------------------------------------------------------------------- | :--------------------------------------------------------------------------------- | :--------------------------------------------------------------------------------------------------------------------------- | :---------------------------------------------------------------------------- |
| Explanantion         | Low level: VM, servers, storage, load balancers, network | Development environments, less flexible, more standard: exuction run time, database, web server, development tools | Access to application software/ database is provided: CRM, Email, Virtuanl Desktop | Code execution model: Provider fully control the state of virtual machine, services and charges relies on invocation/request | Fully managed Kubernetes environment: you can run containers easily inside it |
| GCP product          | Compute Engine                                           | App Engine                                                                                                         | GSuite                                                                             | Cloud Function                                                                                                               | Google Kubernetes Engine                                                      |

## Google Cloud Platform Basics

### Products and services

You can see the official documents by Google [here](https://cloud.google.com/terms/services) or a full list of Google Cloud products [here](https://cloud.google.com/products/).

#### Access management

* [IAM - Cloud Identity & Access Management (Cloud IAM)](Management/IAM.md)

    provides administrators the ability to manage cloud resources centrally by controlling who can take what action on specific resources.

#### Compute

* App Engine

* Compute Engine

* Kubernetes Engine

* Cloud Function

#### Storage

* Bigtable - NoSQL

* Datastore - NoSQL

* Firestore - NoSQL

* Cloud Storage - Blob

* Cloud SQL - SQL

* Cloud Spanner - OLTP, SQL

* Cloud Memorystore - In-Memory DB, Redis

* Filestore - File

#### Networking

* VPC Network

* Network Services

* Hybrid Connectivity

* Network Service Tiers

* Network Security

#### Stackdriver

* Monitoring

* Debug

* Trace

* Logging

* Error Reporting

* Profiler

#### Tools

* Cloud Build

* Cloud Scheduler

* Cloud Tasks

* Container Registry

* Source Repositories

* Deployment Manager

* Customer Identity

* Endpoints

#### Big Data

* BigQuery

* Pub/Sub

* Dataproc

* Dataflow

* IoT Core

* Composer

* Genomics

* Dataprep

#### Artificial Intelligence

* ML Engine

* Natural Language

* Talent Solution

* Translation

* Vision

#### Other

* Maps