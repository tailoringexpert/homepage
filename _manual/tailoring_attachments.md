---
title: "Tailoring attachments"
excerpt: "Process of renaming a tailoring"
permalink: /manual/tailoring/attachments
---
## Introduction
The platform allows you to add files to a tailoring. For example you can add signed documents such as
{: .text-justify}

- tailored requirements catalog
- compliance matrix
{: .text-justify}

When an attachment is uploaded, a SHA256 checksum is calculated and stored with the file. 
All uploaded files are displayed in the dialog along with the calculated checksum.
An attachment can
{: .text-justify}

- downloaded
- deleted

## Step 1: Open project tailorings

<figure>
    <a href="{{ '/assets/images/tailoring/home.png' | relative_url }}"><img src="{{ '/assets/images/tailoring/home.png' | relative_url }}"></a>
    <figcaption>Tailorings</figcaption>
</figure>

## Step 2: Click <span class="mdi mdi-paperclip"></span>

A dialog is opened:

<figure>
    <a href="{{ '/assets/images/tailoring/attachments/list.png' | relative_url }}"><img src="{{ '/assets/images/tailoring/attachments/list.png' | relative_url }}"></a>
    <figcaption>Attachments dialog</figcaption>
</figure>

### Actions

- Add an attachment
- Download an attachement
- Delete an attachment

## Step 3: Upload file

This action consists of following two steps.

### Step 3.1: Select a file to upload

Either click <span class="mdi mdi-paperclip"></span> or input field by the icon. A file dialog is opened to select the file to upload.

<figure>
    <a href="{{ '/assets/images/tailoring/attachments/filedialog.png' | relative_url }}"><img src="{{ '/assets/images/tailoring/attachments/filedialog.png' | relative_url }}"></a>
    <figcaption>System file dialog</figcaption>
</figure>

#### Actions

- Click system button for open. In this case [Öffnen](){: .btn .btn--inverse .btn--small .btn-disabled}
- Click [Close]({{ "/manual/tailoring" | relative_url }}){: .btn .btn--inverse .btn--small} to close the dialog

### Step 3.2: [Upload <span class="mdi mdi-cloud-upload theme--dark"></span>]()

Click [Upload <span class="mdi mdi-cloud-upload theme--dark"></span>](){: .btn .btn--success .btn--small} to perform the file upload.

<figure>
    <a href="{{ '/assets/images/tailoring/attachments/upload.png' | relative_url }}"><img src="{{ '/assets/images/tailoring/attachments/upload.png' | relative_url }}"></a>
    <figcaption>Attachments dialog</figcaption>
</figure>

#### Actions

- Click [Close]({{ "/manual/tailoring" | relative_url }}){: .btn .btn--inverse .btn--small} to close the dialog

## Step 4: Download an attachement

Click <span class="mdi mdi-download-circle"></span> to download the selected file. 

<figure>
    <a href="{{ '/assets/images/tailoring/attachments/download.png' | relative_url }}"><img src="{{ '/assets/images/tailoring/attachments/download.png' | relative_url }}"></a>
    <figcaption>Attachments dialog</figcaption>
</figure>

The behviour of this action is dependent on file type and system configuration.
{: .text-justify .notice--danger}

### Actions

- Click [Close]({{ "/manual/tailoring" | relative_url }}){: .btn .btn--inverse .btn--small} to close the dialog

## Step 5: Delete an attachment

Click <span class="mdi mdi-delete"></span> to delete the file.  
A confirmation dialog is opened.

<figure>
    <a href="{{ '/assets/images/tailoring/attachments/confirmation.png' | relative_url }}"><img src="{{ '/assets/images/tailoring/attachments/confirmation.png' | relative_url }}"></a>
    <figcaption>Delete confirmation</figcaption>
</figure>

### Actions

- Click [Ja](){: .btn .btn--inverse .btn--small} to delete the attachment
- Click [Nein](){: .btn .btn--inverse .btn--small} to keep the attachment
