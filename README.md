# MSA_Data_Dictionary
An automated system to document MS Dynamics 365 ERP data and store it for future analytical use.

WHAT I BUILT (as Product Owner & Data Engineer)
1. Designed end-to-end data pipelines in Microsoft Fabric to extract and refresh SQL metadata automatically.

2. Implemented stored procedures in Fabric to keep documentation continuously up to date as schemas evolve.

3. Built a Copilot Agent in Copilot Studio that lets “data users enquire”, and “knowledge owners validate and update” column/table definitions through conversations in natural language. This agent can be integrated into any of the partner’s Microsoft tools. Users can access it with a single click, whether they are in Teams, Outlook, or any other platform.

4. Orchestrated metadata flows with Power Automate, merging Fabric-based technical metadata and user-generated (via copilot AI agent) business definitions into a common SharePoint list.

This project sits at the intersection of automation, AI assistance, and human-centered design in ERP data management. On the technical side, the main challenge was orchestrating multiple cloud tools into a stable, repeatable flow. On the human side, the challenge was more subtle: how to encourage busy professionals to participate in documentation without framing it as an additional burden.
