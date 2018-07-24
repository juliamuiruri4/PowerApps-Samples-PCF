---
title: "Work with Activity Party Records MicrosoftDocs"
description: "Sample code doc which expalins different methods used in this sample."
ms.custom:
  - dyn365-developer
  - dyn365-marketing
ms.date: 07/18/2018
ms.service: dynamics-365-marketing
ms.technology: 
  - "marketing"
ms.topic: "get-started-article"
applies_to: 
  - "Dynamics 365 (online)"
ms.assetid: 73ede6c7-1972-4506-917c-4f147ecea033
author: NavaKiran 
ms.author: nabuthuk
---
# Work with activity party records

This sample code shows how to work with activity party records. 

## How to run this sample

See [How to run samples](../../../How-to-run-samples.md) for information about how to run this sample.

## What this sample does
This sample creates some sample data, to work with activity party records. 

## How this sample works

In order to simulate the scenario described in [What this sample does](#what-this-sample-does), the sample will do the following:

### Setup
1. Creates three contact records which are required for this sample.


### Demonstrate
1. Retrieves the contact records that are created in the Setup(#Setup). 
2. Creates the activity party records for each contact.
3. Also creates Letter activity and set **From** and **To** fields to the respective Activity Party entities.

### Clean up

1. Display an option to delete the records created during [Setup](#setup). If you opt **Yes** all the records are deleted.

    The deletion is optional in case you want to examine the entities and data created by the sample. You can manually delete the records to achieve the same result.