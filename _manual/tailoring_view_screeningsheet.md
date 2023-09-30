---
title: "View screeningsheet"
excerpt: "Howto view screeningsheet related data"
permalink: /manual/tailoring/screeningsheet
---
## Introduction

A screeningsheet is the basis for creating a new tailoring. By default, a screeningsheet is a PDF file. 
This function provides a dialog to examine the screeningsheet file and the extracted values. 
The calculated selectionvector based on the screeningsheet is also displayed.
{: .text-justify}

The extracted screeningsheet values depends on the tenants implementation. The screens shown on this page are the example perimeter of the __demo__ tenant.
{: .text-justify .notice--danger}

It may happen, that not all data could be displayed without scrolling.
{: .text-justify .notice--danger}

## Step 1: Open project tailorings

<figure>
    <a href="{{ '/assets/images/tailoring/home.png' | relative_url }}"><img src="{{ '/assets/images/tailoring/home.png' | relative_url }}"></a>
    <figcaption>Tailorings</figcaption>
</figure>

### Action

- Click <span class="mdi mdi-card-account-details"></span> to open the screeningsheet overlay.

## Step 2: Click <span class="mdi mdi-card-account-details"></span>

A dialog with the extracted screeningsheet parameters will be opened.
{: .text-justify}

<figure>
    <a href="{{ '/assets/images/tailoring/screeningsheet/parameters.png' | relative_url }}"><img src="{{ '/assets/images/tailoring/screeningsheet/parameters.png' | relative_url }}"></a>
    <figcaption>Extracted screeningsheet parameters</figcaption>
</figure>

### Actions

- Click <span class="mdi mdi-file-pdf-box"></span> to view the raw file. This will open the used (PDF) file either in your browser or your favorite PDF viewer. This depends on your settings.
- Click on **CALCULATED SELECTIONVECTOR** tab to show the selectionvector calculated based on the screeningsheet parameters
- Click [Close]({{ "/manual/tailoring" | relative_url }}){: .btn .btn--inverse .btn--small} to close the overlay

{: .text-justify}

## Step 3: Click **CALCULATED SELECTIONVECTOR**

The tab will be activated and shows the values of the selectionvector based on the screeningsheet parameters.
{: .text-justify}

<figure>
    <a href="{{ '/assets/images/tailoring/screeningsheet/selectionvector.png' | relative_url }}"><img src="{{ '/assets/images/tailoring/screeningsheet/selectionvector.png' | relative_url }}"></a>
    <figcaption>Calculated selectionvector based on screeningsheet parameters</figcaption>
</figure>

### Actions

- Click <span class="mdi mdi-file-pdf-box"></span> to view the raw file. This will open the used (PDF) file either in your browser or your favorite PDF viewer. This depends on your settings.
- Click on **SCREENINGSHEET PARAMETERS** tab to to extracted parameters of the screeningsheet.
- Click [Close]({{ "/manual/tailoring" | relative_url }}){: .btn .btn--inverse .btn--small} to close the overlay