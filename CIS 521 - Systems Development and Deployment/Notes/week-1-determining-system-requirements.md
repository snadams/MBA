# Week 1

## Chapter 6

### Systems Analyst Characteristics

* impertinence: question everything
* impartiality: consider all issues to find the best solution
* relax constraints: assume anything is possible and eliminate the infeasible
* attention to detail: every fact must fit with every other fact
* reframing: challenge yourself to look a the organization in new ways

### System Analyst Deliverables and Outcomes

* Business objectives **drive what and how work is done**.
* Data handled in support of jobs
  * How is that data transformed and stored (when, how, by whom)
  * Data handling dependencies and sequences.
* Policies and guidelines that describe the nature of the business and market and the environment it operates in
* Key events that affect data values and when they occur

## Traditional Methods for Determining Requirements

### Interviewing

#### Guidelines for Effective Interviewing

* Plan the interview.
* Listen carefully and take notes.
* Review notes within 48 hours of interview.
* Seek diverse views.
* Use interview questions.
  * **Open-ended questions**: questions that have no pre-specified answers
  * **closed-ended questions**: questions that have a set of specified responses

### Group Techniques

#### Nominal Group Technique (NGT)

* Group members work alone to generate ideas
* Ideas are pooled.
* Pooled ideas are discussed, primarily for clarification.
* Facilitator then tries to reduce the number of ideas carried forward for consideration.
* At some point, the facilitator and group end up with a tractable set of ideas.

There is some evidence that supports that the use of NGT helps generate a larger number and higher quality ideas than in unfacilitated group meetings.

### Directly Observing Users

* Typically have to find the behaviors of people through subjective (interviews) and objective (system records) means because people cannot be trusted to reliably interpret and report their own actions. But sometimes the numbers can only be explained by something that can only be found in first-hand accounts.

### Analyzing Procedures and Other Documents

What can the analysis of documents tell you about the requirements of a new system?

* Problems with existing systems (i.e. missing information or redundant steps)
* The reason why current systems are designed the way they are
* Data, rules for processing data, and principles by which the organization operates that must be enforced by the information system

There may be issues that come out of reviewing written procedures, like duplication of effort by two different parties or it is out-of-date, but those can only be fixed by management.

* These issues represent the difference between *formal systems* (the official way a system works as described in documentation) and *informal systems* (the way a system actually works due to work habits/preferences, inadequacies of formal procedures, resistance to control, etc.).

## Contemporary Methods for Determining System Requirements

### Joint Application Design (JAD)

* a structured process in which users, managers, and analysts work together for several days in a series of intensive meetings to specify or review system requirements
* It is different from a traditional group interview as all key people are together in one place and analysts control the sequence of questions answered by users.
* Usually conducted in a place at a location other than the place where the people involved normally work.

#### Roles

* *JAD session leader*: trained individual who plans and leads JAD sessions
* *Users*: key users of the system under consideration; have the clearest understanding of what it means to use the system on a daily basis
* *Managers*: managers of the work groups who uses the system in question; provide insight into organizational direction and impact of systems
* *Sponsor*: high-level executive who is sponsors the success of the system
* *Systems analysts*:  member of system analysts team; main role is to learn from users and managers, but not run or dominate process
* *Scribe*: person who takes detailed notes of the happenings at a JAD session
* *IS staff*: programmers, database analysts, IS planners, etc.; contribute on the technical feasibility of proposed ideas or technical limitations of current system

#### Process

1. Introduce corporate sponsor who talks about the organizational unit and the current system and the importance of upgrading to meet changing business conditions.
2. JAD session leader takes over. Yields floor to senior analyst who presents key problems with the current system that have already been identified.
3. Open up discussion to users and managers for further discussion.
4. Any questions that arise that can not be answered must be filed as a "to-do" item that is answered before the end of the JAD.
5. Scribe takes notes on all activities.
6. This is repeated until all requirements are met.

### Prototyping

* an iterative process of systems development in which requirements are converted to a working system that is continually revised through close collaboration between and analyst and users
* **Evolutionary prototyping** is when you begin modeling parts of the target system and, if the prototyping process is successful, you evolve the rest of the system from those parts (i.e. production pilot).
* **Throwaway prototyping** does not preserve the prototype that has been developed. There is never any intention to covert the prototype into a working system.
* Prototyping is most useful for requirements determination when:
  * user requirements are not clear or well-understood
  * one or a few users are stakeholders involved in the system
  * possible designs are complex and require concrete form to fully evaluate
  * tools and data are readily available to rapidly build working systems

### Radical Methods for Determining System Requirements

**business process reengineering (BPR)**: the search for, and implementation of, radical change in business processes to achieve breakthrough improvements in products and services

* The idea behind BPR is not just to improve each business process but reorganize the complete flow of data in major sections of the business to eliminate unnecessary steps, achieve synergies among previously separate steps, and become more responsive to future changes.
* Advocates for BPR suggest that radical improvement can not be done through tweaking existing processes but by thinking of how you would fulfill a process without the baggage of the old process.
* In an BPR effort, an organization must:
  * Understand what processes to change.
    * **key business processes**: the structured, measured set of activities designed to produce a specific output for a particular customer or market
  * Identify specific activities that can be radically improved through reengineering.

**disruptive technologies**: technologies that enable breaking long-held business rules that inhibit organizations from making radical business changes

### Requirements Determination Using Agile Methodologies

#### Continual User Involvement

* To combat against the criticism of traditional waterfall SDLC, where users are only allowed in early stages of analysis, continual user involvement includes for them the entire analysis and design process.

### Summary

* Two phases in system analysis phase of the systems development life cycle: requirements determination and requirements structuring.
* Requirements determination includes:
  * Interviews
  * observation
  * procedures
  * group interviews
