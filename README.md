# 'csharp-state-machine' README

## Overview

The 'csharp-state-machine' is a CSharp template library for creating 
an API State Machine using EffortlessAPI and Airtable. 
This repository provides a basic setup to help you get started 
quickly with building your own customized state machine.

## Prerequisites

Before using the 'csharp-state-machine', ensure that you have the following:

- An Airtable account.
- A registered account on effortlessapi.com.
- Basic knowledge of DotNet/C#.
- [EffortlessAPI Developer Assistant](https://chrome.google.com/webstore/detail/effortlessapi-developer-a/jcoeiomcmmmphkdkadkjpjiakdlpahok?hl=en) Chrome Extension Installed.

## Getting Started

### Step 1: Copy Airtable Template

- Log into your Airtable account.
- Copy the Airtable template for a [Phone Call State Machine](https://airtable.com/appIOcQy7lkKvoWMW/tblErId6eisJcnd7F/viwrywZ1VgdFLMtzS?blocks=hide) - into your own account.

### Step 2: Customize State Machine

- Open the copied Airtable template in your account.
- Modify the state machine by adding, removing, or modifying states according to your specific use case.

### Step 3: Create a New Airtable Project on EffortlessAPI

- Log into your EffortlessAPI account at effortlessapi.com.
- Create a new Airtable project within the EffortlessAPI platform.
- **IMPORTANT** - After making your changes open the API Documentation with the EffortlessAPI Developer Assistant Chrome Extension Installed.

### Step 4: Create Project in EAPI

- Follow the provided instructions in your EffortlessAPI account to create a new project.
- Set up the necessary connections to your Airtable project within the EffortlessAPI platform.

### Step 5: Create API State Machine Seed

- In this repository, navigate to the C# template file.
- Create a new API State Machine seed using the C# template.
- Follow the code comments to understand how the state machine works.
- Customize the seed as per your requirements.


### Draw.io Toolset

The main transpilers are part of the ssot.me draw.io toolset.  As a result - in addition to the airtable mentioned above, there is also a draw.io traffic draw.io file that can be opened with
[draw.io](https://draw.io).  

From there it can be updated/modified and then exported to xml.  From there - when you do a `ssotme -build` it will generate a `state-machine.xml` file based on that draw.io file.

If you copy that `state-machine.xml` file into the StateMachine folder - and then do a `> ssotme -build` specifically in that folder then it will update the entire state machine to match the draw.io version of the state machine.