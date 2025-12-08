# 1. Executive Summary

### What it is: A high-level overview of the project and what the client wants to achieve.

### What you should do:

- [ ] Make sure you clearly understand the client’s objectives.

The client's objective is to have all their data accessible in one single full-stack technological solution.

- [ ] Prepare an internal summary aligned with the client’s definition of success.

The client, **Retail Nova S.A.**, has all it's data about customers scattered across many other sources (CRM, POS, e-commerce platforms, mobile apps, 
other anaytical tools). This project has the objective of centralizing all this data into a **single full-stack technological solution**. With this,
the client also wants to display essential KPIs for customer behaviors, dynamic segmentation through various filters, basic predictive analytics
capabilities and scalability, observability, security and GDPR compliance.


# 2. Background & Context

### What it is: Information about the client’s company, current situation, challenges, and motivation for the project.

### What you should do:

- [ ] Identify the client’s pain points.

Right now, having information about their customers segmented in many areas, such as CRM, POS systems, e-commerce platforms, etc. makes it really 
complicated to have a complete and transparent view about each individual. Furthermore, making presonalized campaign for each customer, based on
what they need, can become tiresome to an extent. Predictive analytics can also be hindered because of such segmentation.
    
- [ ] Adapt your proposal to show you understand their industry and real challenges.

With the solution provided by this response, the client will be able to overcome standard problems encountered in the retail industry, such as:
- not being able to have personalized advertisements based on the history of what the customer bought in the past
- not being able to obatin a 360 view of their customers wants and needs
- not having predictive analytics on what the customer migth buy and making custom offers and bundles for them

# 3. Project Scope

### What it is: What the project includes (and sometimes what it excludes): deliverables, areas of work, components.

### What you should do:

- [ ] Confirm you can cover the full scope.

The presented solution can cover all the needs that the client has requested from us:
- unifying all the customer information into a single source of truth
- interactive components for seeing customer information and trends
- predictive analytical capabilities
- a good level of scalability, security, observability and GDPR compliance

- [ ] Identify risks, dependencies, and questions you need to clarify.

WIP

- [ ] Align your offer with the defined deliverables.

WIP

# 4. Functional Requirements

### What it is: The functionalities or capabilities the solution must provide.

### What you should do:

- [ ] Explain how your solution meets each requirement.

We chose to leverage the compatibility between React and Node.js/Express to build our app. This solution ensures 
the following:
- visualizations of KPIs can be done in a modern and organized way
- filters can be added in order to build custom segments
- capability of exporting reports and segments

We decided to use Airflow with Snowflake in order to be able to ingest and store data from multiple sourcs.

OpenID Connect will be the standard used for authentication purposes, as it will integrate with the corporate SSO.

Prometheus for metrics and ELK for logs, leveraging Grafana for visualization of both data types.

GitHub Actions for the CI/CD pipelines and GitHub for easy cooperation on the project.

- [ ] Provide optional enhancements without going outside the defined scope.

Additional enhancements we envision:
- being able to sort the data and the KPIs as they are shown
- 

# 5. Technical Requirements

### What it is: Technologies, integrations, standards, or technical constraints.

### What you should do:

- [ ] Clearly demonstrate technical compatibility.

Technical compatibility as in technologies working with each other or the team having knowledge in the tech used?

- [ ] Detail architecture, tools, and methodologies.

Architecture:

The architecture that will be used will be client-server, since there will be one point of access in the application
(frontend), which will communicate with a single API.

Tools:

- cooperation, versioning, CI/CD: GitHub
- communication: Teamns and Outlook
- cloud platform: AWS
- integrated development environment, text editor: Visual Studio Code 

Methodologies:
- OOP
- SOLID
- AGILE

- [ ] Ask for clarification if any essential technical detail is missing.

WIP

# 6. Evaluation Criteria

### What it is: The criteria the client will use to score proposals (price, quality, experience, methodology…).

### What you should do: -> I think these are already included in the slides?

- [ ] Tailor your narrative to maximize scoring in the highest-weight criteria.



- [ ] Highlight experience in similar projects.



- [ ] Provide measurable success stories.


# 7. Timeline

### What it is: Key dates: proposal submission, Q&A sessions, demos, award date, project start and duration.
12th of January
### What you should do:

- [ ] Prepare your internal planning accordingly.

We propose to start the project on the 12th of January, once the new year begins and after the holidays period. The project will 
take around two months to complete. Sprints will take two weeks and after each one there will be a demo to showcase what 
has been achieved until that point. If there will be no complications or cooperation issues, the client will have the project 
ready for production by the 12th of March 2026.

- [ ] Confirm you can meet the client’s schedule. -> What does this mean? Schedule for project deadline or day-to-day schedule for
continuous cooperation?

- [ ] Include realistic milestones and dependencies in your proposal.

Milestones:
- functional API for requests
- functional GUI
- preparing the data ingestion from multiple sources
- integrating authetication inside the app
- ?

# 8. Vendor Instructions

### What it is: How the client wants proposals to be submitted: structure, format, page limits, attachments, submission portal, etc.

### What you should do:

- [ ] Follow the instructions strictly (failure can lead to disqualification).

- [ ] Verify the required delivery method (portal upload, PDF, email…).

# 9. Commercial & Legal Terms

### What it is: Contract conditions, SLAs, payment terms, penalties, IP rights, confidentiality.

### What you should do:

- [ ] Review potential legal or financial risks.

- [ ] Indicate exceptions or terms that need negotiation.

- [ ] Ensure you can comply with the requested service levels.

