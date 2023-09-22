---
title: "Tailoring prerequisites"
permalink: /poster/tailoring-prerequisites/
excerpt: "prerequisites of tailoring requirements catalogs"
toc: true
toc_sticky: true
sidebar:
  nav: "poster"
---

The process described in the article is established in DLR's Product Assurance and Project Support department.  
DLR is ***NOT*** responsible for any content of this website.
{: .notice--info .text-justify}

Tailoring the requirements for “how a product should be built”, can be a painful task without the support of an adequate tool. 
This article will provide an overview of what needs to be done and how to ease this task to use the tailoringexpert platform.
But before you can start tailoring, there are a number of prerequisites that need to be fulfilled, therefore let’s take a walk through the process.
{: .text-justify}


## Know your domain!

### Requirement sources

Before you can start tailoring a project you need some sort of base requirements catalog. 
This catalog can consist of self-defined requirements or requirements taken from other standards and guidelines, which are relevant to your domain. 
In the European space domain, it is recommended to at least take ECSS for defining the base requirement catalog. 
Also CCSDS, ISO NIST or MIL Stds may also be relevant sources. Note that this is not an exhaustive list
{: .text-justify}

<figure>
  <img src="{{ '/assets/images/catalog.png' | relative_url }}" alt="catalog with example sources">
  <figcaption>Catalog with example sources</figcaption>
</figure>

Keep in mind: Don‘t try to reinvent the wheel! 

### Structuring of requirements

Next, how do you structure such a base catalog?  
There are at least 3 ways:

1. Only refer to the complete source, e.g ECSS-Q-ST-80C, so applying the complete standard,
2. Extract, reference and possibly modify all relevant requirements from a source, e.g ECSS-Q-ST-80C Rev.1, para. 5.1.1.a. , so only a subset of the source will be applied,
3. A combination of 1 and 2.
{: .text-justify}

The approach taken to define the baseline catalog will have impact on the tailoring result and corresponding compliance matrix. While in the approach 1 (complete sources) the detailing of compliance is the task for the contractor as soon as they are not 100% compliant to the complete source. In contrast approach 2 (fine grained requirements) this detailing task remains at customer side. In consequence the discussion of deviations might lead to longer consultations in case of the first approach, but also the first approach runs the risk that the contractor simply states compliance to make life easy.
{: .text-justify}

### Project Perimeters
After defining your base requirements catalog you need to define selection criteria to filter the requirements that shall be applied for your product, e.g. based on its characteristics. The most easiest way is to define a screening sheet which contains all possible  characteristics/perimeters, so that you just can tick off those relevant for your product and use it as a input for your tailoring. These selected parameters are used to calculate the “selection criterions” also called selection vector. The calculation of this selection vector is very customer specific. The choice of base catalog structure will affect the resulting tailoring.
{: .text-justify}

### Requirements criterions
Once you have defined your product perimeters, you can begin to define selection criteria for your requirements to make them applicable. The criteria could be multi-dimensional:
{: .text-justify}

- The first criterion could be a category such as e.g. quality assurance (Q). A list of various criteria may be required.
- The second one could be a level, e.g. ranging from 0 to 10.
- A third criteria could be a screening sheet perimeter, e.g. SAT.

<i class="fas fa-long-arrow-alt-right"></i> This could be result in Q7(SAT).  

Define such selection criteria for all requirements and depths as required. For some requirements several selection criteria may apply.
{: .text-justify}

## Phases
Requirements can also belong to specific phases. It is important to define relevant phases for each requirement. This will shorten discussions with the supplier.
{: .text-justify}

## Full requirement definition example
<figure>
  <img src="{{ '/assets/images/requirement.png' | relative_url }}" alt="full requirement example">
  <figcaption>Requirement definition</figcaption>
</figure>



