---
title: "Create documents"
excerpt: "How to create tailoring documents"
permalink: /manual/tailoring/documents
---
## Introduction

The tailoring result needs to be exported to documents. The platform offers base implementations for

* tailoring requirements catalalog
* compliance matrix
* DRD
* comparison between generated and current tailoring

as PDF documents.

In addation, the platform also offers

* compliance matrix
* tailoring requirements catalog

as Excel export.

The created set of documents id highly tenant specific. The demo platform provides a full set of documents.
{: .notice} 


## Step 1: Open project tailorings
<figure>
    <a href="{{ '/assets/images/project/home.png' | relative_url }}"><img src="{{ '/assets/images/project/home.png' | relative_url }}"></a>
    <figcaption>Startpage</figcaption>
</figure>

### Actions
1. Click <span class="mdi mdi-pencil-outline"></span> to get to the project tailorings

## Step 2: Open downloads
All tailorings of selected project are shown.

<figure>
    <a href="{{ '/assets/images/tailoring/home.png' | relative_url }}"><img src="{{ '/assets/images/tailoring/home.png' | relative_url }}"></a>
    <figcaption>Project tailorings</figcaption>
</figure>

### Actions
1. Click <span class="mdi mdi-download"></span> in _Actions_ section to open documents download dialog.


## Step 3: Edit signees
All system defined signees are shown in a dialog.

<figure>
    <a href="{{ '/assets/images/tailoring/documents/signees.png' | relative_url }}"><img src="{{ '/assets/images/tailoring/documents/signees.png' | relative_url }}"></a>
    <figcaption>Signatories</figcaption>
</figure>

### Actions
1. Click <span class="mdi mdi-pencil-outline"></span> in the _Actions_ section to open the screen for editing signatory entries.

## Step 4: Edit signatory
Entry of one signatory is shown in an additional overlay.

<figure>
    <a href="{{ '/assets/images/tailoring/documents/signee.png' | relative_url }}"><img src="{{ '/assets/images/tailoring/documents/signee.png' | relative_url }}"></a>
    <figcaption>Project cockpit</figcaption>
</figure>

### Actions
1. Edit name of the signee
2. Edit the state that shall be in the generated document.
3. By checking the _applicable_ checkbox, this signatory will be used for document generation.
4. Click [SAVE](#){: .btn .btn--small .btn--disabled} to update signatory or [CANCEL](#){: .btn .btn--small .btn--disabled} to discard changes. In any case you be return to the _create documents_ screen.

## Step 5: Create documents
All system defined signees are shown in an overlay again.

<figure>
    <a href="{{ '/assets/images/tailoring/documents/signees.png' | relative_url }}"><img src="{{ '/assets/images/tailoring/documents/signees.png' | relative_url }}"></a>
    <figcaption>Signatories</figcaption>
</figure>

### Actions
- Click [CATALOG](#){: .btn .btn--inverse .btn--small .btn--disabled} to generate the tailoring catalog based on the applicable requirements
- Click [DOWNLOAD](#){: .btn .btn--inverse .btn--small .btn--disabled} to generate all tailoring documents based on the applicable requirements