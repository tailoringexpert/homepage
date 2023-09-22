---
title: "Platform introduction"
permalink: /docs/platform-introduction/
excerpt: "Overview of most relevant information about the opensource platform"
toc: true
toc_sticky: true
sidebar:
  nav: "poster"
---

## What is tailoringexpert?

Tailoringexpert is a multi tenant open source platform to create easily, fast and reproduceable requirement documentation based on 
general requirements catalogs on a limited set of parameters, which characterize the specific project. 
The platform is multi-tenant capable and only a limited number of interfaces are need to be implemented per tenant. 
It is based on Spring and uses open source libraries to create PDF and Excel files. 
REST services are implemented as HATEOAS to provide rels that can be used to build your own frontend. 
The base catalog and tailored requirements catalog, are stored in a relational database using Spring Data JPA. 
Because of the fact, that an initial tailoring is created based on fixed rules and requirements, the tailoring is full reproducible and not dependent on the bias of the tailoring person. However, this approach is flexible enough to fine tune and adapted to the specifics of the project and its stakeholders.
{: .text-justify} 

## Implemented use cases

Tailoringexpert implements use cases for
- Create new project with an automated initial tailoring.
- Modifying requirement state or text.
- Creating contractually required documents like (complete set is highly dependent on tenant)
  - Applicable requirements catalog,
  - Compliance matrix,
  - Document requirement definitions,
  - Export of current tailoring, which can also be used as import file for another tailoring.
- Import of (Excel) requirement file,
- Adding new tailorings to an existing project.
{: .text-justify} 


## State Modell 
A state model is implemented to protect tailoring of modification and deletion: 
{: .text-justify} 
- **CREATED**  
The tailoring was created and could be edited or deleted.
- **AGREED**  
The tailoring is a signature loop and could not be modified or deleted.
- **RELEASED**  
The tailoring is signed by all parties involved and cannot be changed or deleted.
{: .text-justify} 

## Base catalog
The used base catalog containing all requirements and limitations is defined in a json structure and will be imported using a REST interface.
{: .text-justify} 

## Tailoring results
The result of a tailoring is primarily stored in a database, but it is also generated as an Excel file that can be used as a starting point for other (similar) projects, or to restore the tailoring after a system crash. If you need to restore, you will need to create a new tailoring and then import the Excel file. This is also ensures full traceability and achievability of the contractual relevant tailoring(s).
{: .text-justify} 

## Files/Attachments to a tailoring
The platform offers the capability to store relevant files, such as the signed documents, in the database. This  leads to a single point of truth of the contractual relevant documents.
{: .text-justify} 


 
