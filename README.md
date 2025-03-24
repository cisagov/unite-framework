# Why is this repository private? #
 
 |                                       |                                        |
 | ------------------------------------- | -------------------------------------- |
 | **Repository made private on:**       | March 24, 2025                        |
 | **Private status approved by:**       | [@h-m-f-t](https://github.com/h-m-f-t) |
 | **Private exception reason:**         | Exploratory discovery to develop a viable framework |
 | **Repository contents:**              | Collaboration docs |
 | **Planned repository deletion date:** | n/a                            |
 | **Responsible contacts:**             | [@m-grote](https://github.com/m-grote)  |
 
 See our [development guide](https://github.com/cisagov/development-guide#readme)
 for more information about our [private repository
 policy](https://github.com/cisagov/development-guide/blob/develop/open-source-policy/practice.md#private-repositories).
 
 - - - - -
 
 <!-- above should be deleted once public -->

# UN!TE Framework for Creating Cyber Defense Collaboration Playbooks
### Overview
Detecting and mitigating cyber threat campaigns often requires collaboration across industry, government, and private threat researchers.  To help scale these defensive operations globally, the UN!TE framework is a standardized set of collaboration actions that allows for easy creation of team playbooks.  
### Who Can Use UN!TE?
National CERTs, threat research teams, and others can use these playbooks to organize defensive campaigns with specific roles for organization types like potential target companies, cybersecurity service providers, internet ecosystem providers, and government agencies.  Each of these organization types have different capabilities and data set that can be brought to the table for responding to a major cybersecurity event, such as a nation-state threat campaign or national response to a major new vulnerability. 
### Integration with MISP
A current focus of the project is to integrate into the MISP platform to enable easy creation and execution of playbooks by threat researchers. 
### Core Framework
The core framework is a JSON file that includes two sets of data: defensive partners and collaborative actions.
```
Header
Defensive Partners - List and details of partner types for playbook actions
Collaborative Actions – List and details of actions to be included in playbooks
```
**Defensive Partners** are the various partner types that participate in collaborative cyber defense operations. Often these organization types have different capabilities and data holdings that can be brought to bear during collaborative efforts.  
**Collaboration Actions** are the specific activities that partners do to collaboratively detect and mitigate threat campaigns.  
### Playbook Format
When sharing indicators or coordinating collaborative defensive campaigns, National CERTs, threat research teams, and others can use the framework to create playbooks of recommended actions. 
```
Header
Defensive Partners
Actions
```
### Playbook Examples
Forthcoming.
### How is UN!TE Different than Other Frameworks?
UN!TE focuses on actions that can be taken as a defensive team across multiple organizations.  It seeks to *leverage and be paired with* other existing frameworks like MITRE ATT&CK, STIX/TAXII, the Incident Command Structure, CSIRT Services Framework, and CACAO.
### Authors & Contributors
[@m-grote](https://github.com/m-grote) 
