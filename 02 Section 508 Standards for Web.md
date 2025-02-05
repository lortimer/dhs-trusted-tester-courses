# Section 508 Standards for Web

## Functional Performance Criteria

These outline overarching requirements for providing access to information and communication technology (ICT) for people with broadly defined types of disabilities.

They're located in chapter 3 of revised Section 508 standards.

"In most situations, ICT purchasers, authors, developers, and accessibility testers must rely on the technical standards to ensure that ICT is accessible to people with disabilities."

"Technical standards" are different from functional performance criteria (FPT). FPT are applicable when:
1. the technical standards don't address the ICT's features and/or
2. The FPT are necessary to evaluate whether the ICT conforms via [equivalent facilitation](Glossary.md)

FPT are a fallback to provide guidance for accessibility as technology changes 


### Standard 302.1 Without Vision

302.1 Without Vision
: Where a visual mode of operation is provided, ICT shall provide at least one mode of operation that does not require user vision.

These sections contain information like the following paragraph, describing how people with certain kinds of disabilities experience and interact with ICT. I'm going to copy them here in block quotes for future reference, but this information is also contained in my CPACC and WAS study notes. I'll also make note in normal text of the information that was new or interesting to me.

 > People who have vision use it to perceive and understand information and data provided by ICT, and they use their hands, a mouse, or another pointing device to operate the ICT through a user interface. People who are without vision or "blind" cannot use a mouse because the location of the mouse pointer is unknown, as is the information around the mouse pointer. Consequently, they typically use an assistive technology (AT), such as a screen reader, to get audible or other alternative output for the information represented visually. To be able to navigate content, understand its structure and relationships, and understand its meaning based on graphics and images, the ICT must provide textual and programmatic cues in addition to that presented purely visually. When interacting with physical hardware interfaces, providing braille and/or audio cues can enable a user to understand and interact with the ICT without the use of vision.

### Standard 302.2 With Limited Vision

302.2 With Limited Vision
: Where a visual mode of operation is provided, ICT shall provide at least one mode of operation that enables users to make use of limited vision.

This doesn't apply if there is no visual mode of operation for the ICT (entirely by voice and audio?)

We must present content consistently and predictably. Users who use screen magnifiers may not notice alerts, warnings, or other content if it's presented outside a predictable pattern.

> People with limited vision or "low vision” may have widely different visual perceptions, ranging from very opaque but wide view to clear but very narrow view, to difficulty with seeing combinations of bright and dark objects, and more. Such individuals may use AT, such as screen readers or screen magnifiers, to help them understand and navigate electronic content or use ICT hardware. They may also use no AT and/or just corrective lenses (glasses). This Functional Performance Criterion only applies when a visual mode of operation exists for the ICT. For example, completely voice-operated ICT may not have a visual mode of operation, in which case this Functional Performance Criterion does not apply.

> In addition to the textual and programmatic cues necessary for AT, as described above, ICT must also present content consistently and predictably. Users who view content with magnifiers may not pick up alerts, warnings, or other content if it is presented outside of a consistent and predictable navigation pattern or if it is not itself viewable at large magnification. Additionally, content that becomes distorted when magnified can prevent some people with limited vision from being able to understand or interact with it. While people with limited vision can and sometimes do use screen readers (essentially using ICT without the use of any visual access), the solutions that work for people without vision are often not the optimal solution for those with limited vision.

### Standard 302.3 Without Perception of Color

302.3 Without Perception of Color
: Where a visual mode of operation is provided, ICT shall provide at least one visual mode of operation that does not require user perception of color.

> Some people who are without perception of color or "color blind" may not be able to perceive differences between some colors and therefore do not receive information conveyed by the colors (e.g., using gradients of color between red, yellow, and green to indicate an item’s status from poor to good). In such cases, ICT must provide additional information by an alternative means that conveys the same meaning (e.g., shapes and/or textual labels in addition to the color).

### Standard 302.4 Without Hearing

302.4 Without Hearing
: Where an audible mode of operation is provided, ICT shall provide at least one mode of operation that does not require user hearing.

> This Functional Performance Criterion addresses the needs of people who are without hearing or "deaf". When ICT provides information, instructions, or cues audibly, people who are without hearing will not receive the information. Some examples of specific ICT where this ismost important include online training videos, security briefings, and public service announcements, which often contain audio in addition to visual content. Without captions, people who are without hearing are not able to understand what is spoken, or other important sounds. Typically, providing the same information visibly (e.g., providing a warning light or textual dialog to accompany an audible warning sound) enables people who are deaf to get equivalent information.

### Standard 302.5 With Limited Hearing

302.5 With Limited Hearing
: Where an audible mode of operation is provided, ICT shall provide at least one mode of operation that enables users to make use of limited hearing.

> This Functional Performance Criterion addresses the needs of people with limited hearing, or are "hard-of-hearing". Some people cannot hear sounds below certain volumes or at certain frequencies and may not be able to hear certain audio outputs from ICT. Background noise can also be problematic for people with limited hearing. Providing modes of operation that enhance audio clarity (e.g., filtering out hisses and pops, blocking sounds at specific frequencies, normalizing voice volumes, removing constant tone patterns), increase the range of volume, increase volume at higher frequencies, and/or give users control over such settings can help people with limited hearing understand, navigate, and operate ICT. People with limited hearing may also benefit from some of the same methods used to provide information to people without hearing (described earlier).

### Standard 302.6 Without Speech

302.6 Without Speech
: Where speech is used for input, control, or operation, ICT shall provide at least one mode of operation that does not require user speech.

Speech-operated ICT is becoming more common, including phone-operated systems. Some, like CVS' phone system, prompt you to say something without explaining that you can also press buttons for each answer. They do allow pressing 1 for yes and 2 for no, but they should also tell the user that.

**There is no WCAG technical standard that addresses alternatives for speech inputs!**

> Some people have no vocal capability or can speak only with limited volume, clarity, or duration. Speech-enabled and speech-operated devices are becoming more commonplace in all forms of ICT. When people with limited or no vocal ability encounter speech input, they may not be able to interact with the ICT. Although there is no WCAG technical standard that specifically addresses alternatives for speech inputs, an alternative method must be provided to input information or perform the operation when ICT requires speech for input, control, or operation.

### Standard 302.7 With Limited Manipulation

302.7 With Limited Manipulation
: Where a manual mode of operation is provided, ICT shall provide at least one mode of operation that does not require fine motor control or simultaneous manual operations.

This one is also not strictly covered by WCAG, but the spirit is there. I already knew that requiring the user to hold buttons, press multiple at the same time, or click-hold-and-drag wasn't OK.

> Some people may not be able to perform actions that require fine motor control, path-dependent gestures, or simultaneous actions. Actions requiring fine motor control could include actions such as twisting a knob or clicking and dragging a portion of an object with a mouse to resize it. Path-dependent actions could include tracing the outline of an image with a mouse or finger or inputting a pattern-based passcode on a mobile device’s login screen. Simultaneous actions include those actions that require clicking multiple buttons at the same time to perform an action (e.g., CTL+ALT+DEL to lock a computer screen). Providing an alternative means to perform the same actions, such as entering the size specifications in an input field to resize an object or allowing sequential key entries, can enable people with limited manipulation to interact with the same content.

### Standard 302.8 With Limited Reach and Strength

302.8 With Limited Reach and Strength
: Where a manual mode of operation is provided, ICT shall provide at least one mode of operation that is operable with limited reach and limited strength.

> Some people may lack sufficient strength to perform actions that require a certain degree of hand strength, such as squeezing, grasping, or depressing a hardware control. Additionally, some people, including those in wheelchairs or of shorter stature, may not be able to reach controls that are placed too high or too far away from where they can access the device controls or interface. ICT designers and developers must consider a broad range of statures, strength and dexterity limitations, and the needs of people who use wheelchairs in order to provide interfaces that are operable with limited reach and/or strength. Although the Standards do not currently include a technical requirement related to particular touch gestures common among touch-input devices, another method must be provided to perform functions requiring reach and strength.

### Standard 302.9 With Limited Language, Cognitive, and Learning Abilities

302.9 With Limited Language, Cognitive, and Learning Abilities
: ICT shall provide features making its use by individuals with limited cognitive, language, and learning abilities simpler and easier.

> Some people require more time to process information, while others may find complicated instructions difficult to follow. Furthermore, some ICT content can distract or overwhelm users, preventing them from being able to interact with or understand other ICT content. This Functional Performance Criterion covers a very broad range of language, cognitive, and learning abilities. Some of the technical requirements included in the WCAG 2.0 Success Criteria are related to this Functional Performance Criterion, including:

    - 3.3.3 Error Suggestion
    - 3.3.6 Error Prevention
    - 2.2.1 Timing Adjustable
    - 2.2.2 Pause, Stop, Hide (distracting content)

