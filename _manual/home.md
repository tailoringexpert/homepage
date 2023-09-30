---
title: "Handbook introduction"
excerpt: "Provide informations and links to implemented usecases"
permalink: /manual/
---

This website shall serve as a replacement of a traditional handbook and shall provide informations about implemented usecases
and how to apply them.

## [Project]({{ "/manual/project/home" | relative_url }})
How to:

- Create a new project with an inital automated tailoring
- Delete an existing project
{: .text-justify} 

## [Tailoring]({{ "/manual/tailoring/home" | relative_url }})

### [Edit requirements]({{ "/manual/tailoring/edit" | relative_url }})
After the automatically generated initial tailoring you are able to fine tune the applicable requirements. 
{: .text-justify}

You [can]({{ "/manual/tailoring/edit" | relative_url }}) either
- toogle the applicable state or
- modify the text of an existing requirement.
{: .text-justify}


### [Create documents]({{ "/manual/tailoring/documents" | relative_url }})
There are two "types" of documents that can be [created]({{ "/manual/tailoring/documents" | relative_url }}):
{: .text-justify} 

1. a version of the tailored requirements catalog  
2. a set of documents which is dependent on implementation of this function by the tenants.
{: .text-justify} 

### [Compare requirements catalogs]({{ "/manual/tailoring/compare" | relative_url }})
It is possible to [compare]({{ "/manual/tailoring/edit" | relative_url }}) the current requirements catalog to the initial 
automatically generated one. Applicability and text changes of requirements will be tracked automatically by storing the time of the change.
A PDF is created to display the text and applicability state of each requirement.

In contrast to the applicability change, a text change will only be tracked for the first change. 
I.E. if you change back to the original text, it will still be marked as changed.
{: .text-justify .notice--danger}


### [View screeningsheet]({{ "/manual/tailoring/screeningsheet" | relative_url }}) 
A screeninsheet is the basis for entering a tailoring. It is used to determine/calculate the selectionvector that is recommended to use
for the initial tailoring. This [function]({{ "/manual/tailoring/screeningsheet" | relative_url }})  provides you the screeningsheet file as well as the extracted perimeters and the calculated selectionvector.
{: .text-justify}

This function is highly tenant specific. Every field that should be displayed in the parameter tab must be defined in tenants' implementation 
of the _ScreeningSheetParameterProvider_ interface. 
{: .text-justify .notice--danger}

### [View selectionvector]({{ "/manual/tailoring/selectionvector" | relative_url }})

A selectionvector is the basis for creating the initial automatically tailored requirements catalogue. For each tailoring two possible different
selectionvectors will be stored. 
{: .text-justify}

### [Attachements]({{ "/manual/tailoring/attachments" | relative_url }})

The platform allows you to add files to a tailoring. For each uploaded file a SHA256 checksum will also be calculated and stored with the file.
Attachments could also be downloaded and deleted.
{: .text-justify}

### [Import requirements]({{ "/manual/tailoring/import" | relative_url }})

The automatically tailored requirements catalogue is usually the starting point for fine-tuning the requirements to meet specific project needs.
This can be a tedious task if you have many requirements to review while navigating through the requirements tree.
For this reason a [requirements import]({{ "/manual/tailoring/import" | relative_url }}) is implemented using an Excel file.
{: .text-justify}

Another benefit for such an import is to collect the opinions of various specialists to create an internally agreed catalog of requirements.
{: .text-justify}

### [Notes]({{ "/manual/tailoring/notes" | relative_url }})

Sometimes you may want to add some comments or notes, e.g. why you have chosen an old catalog version. The platform [implements]({{ "/manual/tailoring/notes" | relative_url }})
 functions for
{: .text-justify}
- view
- add

notes.  

Deleting notes will not be implemented for revision reasons.
{: .text-justify .notice--danger}

### [Delete]({{ "/manual/tailoring/delete" | relative_url }})

A project can have multiple tailorings. This may be due to different project phases or internal reasons like ageeing of the applicable 
requirements.
{: .text-justify}

### [Rename]({{ "/manual/tailoring/rename" | relative_url }})

By default the first name of a projects' tailoring is **master**. If this is already used, the system tries to add to number to the automated tailoring.
However it is possible to change the name of the tailoring as long as it is unique in the project.
{: .text-justify}

### [State management]()

### Base requirements catalog

{: .text-justify} 


