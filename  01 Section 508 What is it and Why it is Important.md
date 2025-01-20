# Section 508 What is it and Why it is Important

DEFINITION: ICT = "Information and Communication Technology"

The US government is required to meet the standards of Section 508 of the Rehabilitation Act when it develops, procures, maintains, or uses ICT. 

Section 508 was ratified in 1973 and amended since. Its goal is to make ICT accessible to people who have disabilities, comparable to the experience of people who do not have disabilities.

People who have unequal access to ICT have unequal access to opportunities

## What is Section 508?

### ICT

Examples include:
- Computers and peripheral equipment
- Information kiosks and transaction machines
- Telecommunications equipment (telephones, telephone systems)
- Customer premises equipment (servers, routers)
- Multifunction office machines
- Software, applications, and websites
- Videos
- Electronic documents

#### Non-ICT

- equipment that contains ICT but isn't primarily ICT, like HVAC units and medial equipment like X-ray machines
- ICT products that are just exceptions:
  - CDs and DVDs (although the content must be accessible???)
  - Cables and cords
  - Wi-Fi, fiber optics

### Revised Section 508 Standards

Originally, 508 took a product-based approach, but was revised to care about ICT functions. This is good because when new technology comes out, like smartphones, it's already covered even if it isn't mentioned explicitly.

The content is divided into chapters that I'm sure we'll come back to.

### Functional Performance Criteria

Functional performance criteria support the needs of users with:

1. Blindness or visual impairments.
2. Deafness, hearing impairments, or use of assistive hearing devices.
3. Difficulty with speech.
4. Difficulty with fine motor control.
5. Limited reach and strength.

They are used when the hardware and software standards don't explicitly cover something.

DEFINITION: Equivalent Facilitation = Using an alternate design or technology that results in "substantially equivalent or greater accessibility and usability" by users with disabilities THAN WOULD BE PROVIDED BY the hardware or software requirements.

### Web Content Accessibility Guidelines (WCAG) 2.0

Section 508 uses WCAG 2.0 levels A and AA as a universal standard.

### Covered Electronic “Content”

All types of public-facing content and 9 categories of non-public facing content must be accessible.

DEFINITION: Content = "all forms of electronic information and data"

The revised standards cover documents better.

### Interoperability Requirements

508 requires how ICT should interact with Assistive Technologies like screen readers, but does not apply to assistive technologies themselves.

### What ICT Activities are Covered?

Federal agencies are subject to Section 508 Standards during four specific ICT-related activities:

- Development
- Procurement
- Maintenance
- Use

### Development of ICT

All team members are responsible for meeting Section 508 standards when a new product or service is being created. This can include software, websites, hardware, and documents.

### ICT Accessibility Examples

- An agency wants to provide customers with a way to access personal medical information from mobile and desktop software.
- A supervisor sends his assistant a financial report in PDF format and asks him to distribute it to the entire department. Because this document _supports the agency's mission_, the assistant should determine if the document is accessible before sending it out as an email attachment.
- A national park owned and managed by the Federal government creates new information kiosks for several locations along a scenic walking path

#### Procurement of ICT

- You have been asked to procure a new help desk system for your agency. Because that help desk system will be used by employees of a Federal agency, you must procure the most compliant product available that meets your agency’s business needs.
- The department’s multifunction machine has stopped working and cannot be repaired. You have the authority to procure replacement equipment locally. As an employee of a Federal agency, you must make sure the new multifunction machine is the most conformant device available today that meets your business needs.
- Your agency wants to procure mobile devices for field staff so they can submit inspection reports quickly and easily. You must make sure that the mobile devices, along with the software loaded on them, are the most conformant products available today that meet your business needs.

#### Maintenance of ICT

Section 508 standards must be met when ICT products are maintained. Below are some examples of ICT maintenance needs.

- A vendor has been awarded a contract by a government agency to update its Internet website.
- A software application used by an agency is reviewed and appropriately updated by the vendor every three years.

#### Use of ICT

In some cases ICT is used by agencies, but not actually procured by them. Products and services of this type are also covered by Section 508. Below are some examples of ICT use needs.

- An open source content management system (CMS) is used by a small agency to maintain their intranet site.
- An agency’s staff advertises upcoming seminars and job fairs on a social networking site. The features of the site used by staff to enter and post information must be usable by persons with disabilities, or a Section 508-conformant alternative must be provided in addition to the social networking site.

## Why is Section 508 important?

### What are disabilities?

Section 508 uses a _medical_ definition: "Individuals with disabilities are people who have sensory, physical, or cognitive impairments that substantially limit their ability to perform one or more major life activities."

As such, this website lists barriers for people with disabilities, like "People who use screen readers may not be able to access information in documents, such as Microsoft Word, Excel, PowerPoint, or PDF, if accessibility is not considered."

This is all basic stuff from CPACC training talking about why it's important to build things accessibly, but with a backward view that the disability is inherent to the person.

### Assistive Technologies

DEFINITION: Assistive Technology (AT) = "AT includes hardware or software that enables a person with a disability to use ICT"

screen readers, magnifiers, braille display, color changes, voice controls, alternative inputs.

Ones I haven't heard of:
- Reading Assistance Software: combines advanced speech verification technology with scientifically-based interventions to help strengthen reading fluency, vocabulary and comprehension.
  - This might also include something like that app that shows you one word at a time in quick succession to help you read faster/reduce distractions.

### Accessibility vs. Section 508

THEY SAID THE GOOD THING: "Conformance with Section 508 Standards does not require or guarantee complete access with every AT product. In addition, Section 508 conformance does not necessarily mean all an individual’s accessibility needs will be met."

Apparently there are other laws like Section 504 that address some of those situations.

However, on the next page they equate complying with 508 to providing equal opportunities to people with disabilities.

## Your Responsibilities (as an employee of a government agency)

If you do any of the things above in your work as a government agent: procurement, development, or maintenance of ICT.

### Procuring

If you're procuring ICT that allows users to create other ICT like documents, Section 508 applies to the tool (MS Word) _and_ the users' ability to make accessible ICT. So, does MS Word follow the authoring tools accessibility guidelines? Does it allow users to build accessible documents?

Advice on including Section 508 standards in requirements for ICT contracts.

#### How to do market research

- Ask for product demonstrations and ask about 508 compliance
- In-house testing with a software trial
- Look for Section 508 in marketing materials
- Requests for Information (RFI)
- Accessibility Conformance Report (ACR)
  - Created using a template called a Voluntary Product Accessibility Template (VPAT)
  - The current VPAT is [Version 2.4Rev508 — February 2020](https://www.itic.org/dotAsset/b282ab06-0ab2-4540-adc2-78698058dfc3.doc). 

### Exceptions

- Legacy ICT (not been altered in any way since January 18th, 2018) isn't required to be modified to conform to section 508.
- National Security blanket exception
- ICT acquired by a contractor incidental to the contract (contractor's internal timecard service, maybe?)
- ICT functions location in maintenance or monitoring spaces
  - spaces only frequented by service personnel for maintenance, repair, or occasional monitoring of equipment. Like, status indicators and operable parts of a machine or wifi routers.

#### Undue Burden

This exemption is a high bar and should not be used casually.

One heuristic is if conformance would result in "a fundamental alteration in the nature of the ICT".

This exception must be fully documented:
- The non-availability of conforming ICT, including a description of market research performed and which provisions cannot be met
- the basis of determining that the ICT to be procured best meets the requirements in the Revised 508 Standards consistent with the agencies business needs.

It also doesn't exempt the agency from offering an accessible alternative, just from updating the existing thing.

"the agency shall provide individuals with disabilities access to and use of information and data by an alternative means that meets identified needs"

If a fully-compliant alternative is not available, the one that conforms best is required.

### Responsibilities when Developing

All federal employees and _federal contractors_. 

### All parts of the development team

Project Managers are responsible for ensuring 508 steps are taken, resources and training are provided to the project team. Ensure requirements are addressed in project planning, risk planning, disabled user needs analysis and requirements identification, solution engineering, alternatives analysis, acquisition activities (where applicable), design, development, testing, deployment, and operations & maintenance.

Requirements Analysts and Designers - address requirements through design

Developers need to learn how to build accessible software and do it. Use the tools that allow you to build accessibly.

Testers know how to test something for accessibility and do that.

Section 508 Subject Matter Experts support the others

### Dealing with an Accessibility Issue

It's not the job of employees with disabilities to determine conformance. If they run into accessibility issues, they should report them to their supervisors.

### Testing

When building ICT, obviously. Also when modifying ICT or using new ICT. Even when you upgrade hardware!

## Bonus Info

### Section 504

Section 504 is a part of the Rehabilitation Act of 1973 that prohibits job discrimination and requires employers to make reasonable accommodation for employees with disabilities. Its purpose is to make sure that qualified persons with disabilities are provided the tools, environmental modifications, or other adjustments that allow them to do their jobs.

Examples:
- Agency must provide a blind employee a screen reader required to do work on the computer
- VA required to provide sign language interpretation for deaf veterans in group counseling
- Modify office configuration so a wheelchair fits

### Section 508 Program Managers

It didn't mention this role until the course exam, which I already took. Also called Section 508 Coordinators, they are responsible for organizing and supporting the implementation of Section 508 within their assigned departments and agencies. 
