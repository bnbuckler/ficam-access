---
layout: page_collection
title: Step 4 - Identify Protected Resources
permalink: 4_step-4
---
<script>
$(function() {
  $( "#accordion" ).accordion({
    heightStyle: "content",
    collapsible: "true",
    active: "false"
  });
});
</script>

<script src="https://use.fontawesome.com/e20c671b68.js"></script>
-----------------------------------------------------------

Your agency has valuable assets that require levels of protection. Identification may require gathering information from multiple existing resource inventories because the processes used to identify, track, and catalog resources are often distributed across multiple programs and systems within your agency. Each program or system typically collects and manages information about a subset of the agency’s resources to support a specific business function. For example, all agencies are required under FISMA to have a complete, current inventory of IT systems. ICAM implementers must be able to retrieve information about these resources quickly and efficiently to effectively manage access to them in a coordinated fashion. Additionally, physical and logical resources typically are managed separately from each other within an agency.

For many existing resources, your agency has likely already determined which resources require protection and the necessary level of protection. Guidance for determining protection requirements for information systems, devices, and infrastructure is outlined in many existing policy and guidance documents (e.g., M-04-04, FIPS 199, M-06-16). Guidance for determining levels of protection for facilities and work sites which require electronic security systems is provided by the Interagency Security Committee (ISC). It can be expected that an agency’s physical security group will have previously evaluated all existing facilities and sites within the agency’s custody and determined physical protection requirements; however, for geographically dispersed organizations, this information may be managed locally. The figure below discusses several common programs and functions that collect and manage this information, and may therefore provide a starting point for ICAM implementers.

<br>

| <center> Agency Function </center> | <center> Information Available </center> | <center> Resource Type </center> |
|-------------------------------------------------------------------------------------|
| Facility Management Group / Physical Security Group | Information regarding resources that must be secured using Physical Access Control System (PACS). | <center> Physical </center> | 
| Real Property Group | Information regarding land, building, and improvements that are owned or leased by a federal agency. | <center> Physical </center> | 
| Capital Planning and Investment Control (CPIC) Program | Investment information for capital assets submitted by a federal agency to OMB for funding. | <center> Physical </center><center> Logical </center> |
| Helpdesk/Trouble Ticket Solutions and Records | Often contain lists of resources and/or targets of privilege/access management requests, as they are frequently sources of problems and issues for users. | <center> Physical </center><center> Logical </center> | 
| Enterprise Data Warehouse | Enterprise Architecture (EA) repository of electronically stored data about an organization’s resources and data, commonly maintained to facilitate reporting and analysis. | <center> Physical </center><center> Logical </center> |
| Information Resources Catalog (IRC) | Some agencies may have an existing IRC, which is a comprehensive catalog of resources and resource information. | <center> Physical </center><center> Logical </center> |
| IT System Inventory | Inventory of IT applications and security compliance and reporting information. | <center> Logical </center> |
| Change Control Board (CCB) and/or Change Management System | Maintains the software, hardware, and application baselines for resources within the enterprise as a means of supporting change/upgrade efforts. | <center> Logical </center> |

<br>

### Checklist 

> <i class="fa fa-check-square-o"></i> &nbsp;**Identify Content and Information.** Content is data structured in a usable form to serve specific purposes. Information is any communication or representation of knowledge such as facts, data, or opinions in any medium or form, including textual, numerical, graphic, cartographic, narrative, or audiovisual. Content and information are stored in federal systems and used in the business functions of a federal agency, and can include digital information stored within a database or application. The protection of content and information is important to achieve and maintain confidentiality, integrity, and availability. 

> <i class="fa fa-check-square-o"></i> &nbsp;**Identify Applications and Web Services.** An application is a software program hosted by an information system that performs specific functions. A web service is a software system designed to support interactive and automated interaction with information systems over a network. Together, applications and web services represent the intangible assets that provide functional capabilities that allow federal employees to perform the business functions of their agencies. Examples of applications and web services include employee timekeeping, reporting, and other agency-specific software hosted on local workstations, agency servers, and web-based services, such as a cloud environment. Protecting applications and web services prevents unauthorized users from accessing federal IT systems that host sensitive information, which could affect the availability and reliability of those systems. 

> <i class="fa fa-check-square-o"></i> &nbsp;**Identify Networks and Infrastructure.** A network is an information system implemented with a collection of interconnected components. Infrastructure is the hardware, storage, servers, and data center space or network components that provide IT services to an organization. Networks and infrastructure together represent any tangible technological assets that are interconnected to support the IT needs of an agency, which can include computer networks, servers, switches, hubs, mainframes, and the physical technology that support them. The protection of networks and infrastructure is crucial because they support the agency’s enterprise IT environment. If one element is compromised, related protected resources may become vulnerable.

> <i class="fa fa-check-square-o"></i> &nbsp;**Identify Facilities.** Facilities are all buildings and/or portions of buildings occupied by federal employees (includes existing owned, to be purchased or leased facilities, stand-alone facilities, federal campuses, individual facilities on federal campuses, and special-use facilities). Safeguards for the protection of federal locations not only prevent physical attacks on the location overall, but also the resources housed within the location.

> <i class="fa fa-check-square-o"></i> &nbsp;**Organize your agency’s resources.** You can organize your agency’s resources by using common criteria as a means of providing baseline privileges in an automated fashion. You can do this by examining the resource attributes that determine how users are granted access and looking for similarities that drive access control decisions. Resources may be grouped in several ways, including:

>> * **Physical Location.** Many agencies with multiple offices/buildings in metropolitan areas often grant access to all facilities within that area as a means of ensuring that personnel can easily attend meetings in nearby offices, this may also extend to network/system access associated with a geographic location.

>> * **Project/Program Affiliation.** Projects or programs that rely on a small subset of information systems or specified work locations can group those resources and grant access based upon affiliation with the project or program rather than granting each person access to each individual resource.

>> * **Organizational Relationship.** Within an agency there may be components or bureaus that grant access to resources based upon organizational affiliation (i.e., a component/bureau specific information sharing tool).

>> * **Function/Purpose.** Similar to Project/Program affiliation, certain resources may support a common function or purpose within an organization (i.e., HR systems, accounting systems, etc.).

> You must collect, analyze, and understand your agencies resources to determine the necessary level of protection to establish effective access control policies.  Background information about a resource is often required to support access control decisions. This information can often be obtained by reviewing resource documentation and meeting with resource owners/administrators to discuss how and why access is currently controlled. Examples of contextual information that can be used to support access control are provided in the figure below.

<br>

| <center> Information Componenent </center> | <center> Description </center> |
|-----------------------------------------------------------------------------|
| **Time-based access restriction** | Access to the resource is restricted during particular hours or certain times of the day, week, or year based upon resource requirements |
| **Certification-based access restriction** | Access to the resource requires possession of a particular certification or permit |
| **Organizational affiliation restriction** | Resource access requires a particular affiliation with the organization (e.g., IT systems for federal employee access only), or affiliation with a particular bureau/component/office, etc. |
| **Location-based restriction** | Access to the resource is restricted based on geographical location for both physical and logical resources, and/or Internet Protocol (IP) and Media Access Control (MAC) address for IT resources and data |
| **Resource-based restriction** | Access to certain data or information is dependent upon it being accessed through a particular resource, thereby preventing direct access. | 
| **Data sensitivity restriction** | Certain IT resources or data elements may require that users possess a level of public trust or clearance (National Agency Check with Written Inquiries [NACI], Public Trust, Secret, etc.) before being accessed. | 

<br>

### Benefits

> <i class="fa fa-thumbs-o-up" aria-hidden="true"></i> &nbsp;**Each resource has its own role in your agency’s mission and is subject to potential vulnerabilities and threats.** You must consider how to minimize those vulnerabilities and mitigate threats while maximizing the effective use of the resource and making it available to the appropriate users. As you perform risk assessments of the resources, you’ll be able to identify resource vulnerabilities and the associated risks, and devise solutions to mitigate the risks. The results of this process will determine what other specific elements of the Access Management Framework should be applied during the implementation. This assessment should consist of evaluating how alternative access control models might be applied to the resource, including centrally-controlled enterprise systems and the capabilities of the local resource. 

<br>

<div style="background-color: #edf1f3;color: black;margin: 10px;padding: 10px">

<h3><span>FAQ</span></h3>
<p><strong>Are there any tools available to help determine the level of authentication risk associated with my information systems?</strong></p>
Yes, the <a href="https://www.idmanagement.gov/IDM/s/article_search_detail?KID=ka1t00000004DfQAAU&Type=Site_Article__kav" target="_blank"> eAuthentication Risk and Requirements Assessment (e-RA) tool </a> can be leveraged to assist in determining logical access control risks and appropriate levels of assurance, as defined in M-04-04. Additional guidance for conducting overall security risk assessments is provided in FIPS 199.