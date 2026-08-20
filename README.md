# DevOps

This repository contains my coursework for **DevOps** at **Bellevue University**.

This course explored the principles, practices, and technologies used to improve collaboration between software development and operations while enabling faster, safer, and more reliable software delivery. Coursework covered topics throughout the software delivery lifecycle, including version control, continuous integration and delivery, automated testing, architecture, deployment practices, telemetry, security, change management, and continuous improvement.

The course combined concepts from *The DevOps Handbook* with practical assignments, presentations, technical research, and analysis of real-world DevOps practices.

---

## Repository Structure

Coursework is organized by module, with an additional `graphics` directory containing visual assets used in presentations and assignments.

```text
DevOps/
├── graphics/
│   ├── BU-template-logo.pptx
│   ├── bad_value_stream.png
│   ├── good_value_stream.png
│   └── lead_process_time.png
├── module-1/
│   ├── eckert-assignment-1-2.pptx
│   ├── eckert-assignment-1-3.docx
│   └── eckert-github-setup.docx
├── module-2/
│   └── eckert-assignment-2-2.docx
├── module-3/
│   └── eckert-assignment-3-2.docx
├── module-4/
│   ├── Nizam_TestPlan-Eckert_Review.docx
│   ├── Waters_TestPlan-Eckert_Review.docx
│   └── eckert_TestPlan.docx
├── module-5/
│   ├── current_state_vsm.png
│   └── eckert-assignment-5-2.docx
├── module-6/
│   └── eckert-assignment-6-2.docx
├── module-7/
│   ├── eckert-assignment-7-2.pptx
│   └── eckert-assignment-7-3.docx
├── module-8/
│   └── eckert-assignment-8-2.pptx
├── module-10/
│   └── eckert-assignment-10-2.pptx
├── module-11/
│   └── eckert-assignment-11-2.docx
└── README.md
```

The repository contains written assignments, technical presentations, test plans and reviews, diagrams, and other artifacts demonstrating DevOps concepts throughout the course.

---

## Topics Covered

Throughout this course, I studied DevOps practices across the software development and delivery lifecycle, including:

* DevOps principles and culture
* Development and operations collaboration
* Version control with Git and GitHub
* Continuous integration
* Continuous delivery and deployment
* Deployment pipelines
* Automated testing
* Test planning and peer review
* Value-stream mapping
* Lead time and process improvement
* Application architecture
* Monolithic and microservices architectures
* The Strangler Application Pattern
* Telemetry and observability
* A/B testing
* Infrastructure as Code
* Configuration management
* Change approval processes
* Continuous improvement
* Improvement Blitz and Kaizen practices
* ChatOps
* Internal technology conferences
* Chaos engineering
* Dependency scanning and software composition analysis
* Source code integrity
* Code signing
* Secure software development practices
* Continuous monitoring
* Continuous auditing
* DevOps performance and organizational practices

---

## Course Progression

### Foundations of DevOps

The beginning of the course introduced the principles behind DevOps and the problems it is intended to address.

Topics included collaboration between development and operations, software delivery workflows, version control, and the role of automation in creating repeatable development processes.

Git and GitHub were also used to organize and maintain coursework throughout the course.

---

## Testing and Quality

Testing was explored as an important part of building reliable software delivery pipelines.

Module 4 included the development of a software test plan along with peer reviews of other test plans.

```text
module-4/
├── Nizam_TestPlan-Eckert_Review.docx
├── Waters_TestPlan-Eckert_Review.docx
└── eckert_TestPlan.docx
```

This work provided experience with:

* Developing structured test plans
* Identifying testing requirements
* Considering expected and unexpected application behavior
* Reviewing technical documentation
* Providing peer feedback
* Connecting testing practices with software quality and delivery

---

## Value-Stream Mapping

The course examined value-stream mapping as a method for understanding how work moves through a software delivery process.

Module 5 included the creation and analysis of a current-state value-stream map.

```text
module-5/
├── current_state_vsm.png
└── eckert-assignment-5-2.docx
```

This work emphasized concepts such as:

* Lead time
* Process time
* Wait time
* Work handoffs
* Bottlenecks
* Waste
* Flow
* Opportunities for process improvement

Value-stream mapping demonstrated how DevOps extends beyond individual development tools by examining the entire process required to move software from development to production.

---

## Architecture and Deployment

Later coursework examined how software architecture affects the ability to develop, test, deploy, and maintain applications.

Topics included:

* Monolithic applications
* Microservices
* Loosely coupled architectures
* Deployment independence
* The Strangler Application Pattern
* Incremental modernization of legacy systems

These concepts demonstrated how architectural decisions can influence deployment frequency, system maintainability, team independence, and the ability to make changes safely.

---

## Telemetry and Experimentation

The course also examined the importance of collecting information from production systems and using that information to guide development decisions.

Topics included:

* Application telemetry
* Monitoring
* Observability
* Production feedback
* A/B testing
* Data-informed experimentation

These practices help development teams understand how applications behave after deployment rather than treating deployment as the end of the development process.

---

## Change Management and Continuous Improvement

Several assignments explored how organizations can improve software delivery processes while maintaining appropriate controls.

Topics included:

* Change approval processes
* Reducing unnecessary manual approvals
* Automated controls
* Continuous improvement
* Improvement Blitz and Kaizen practices
* Learning from production systems
* Internal technology conferences
* ChatOps

These concepts emphasized creating systems where teams can continuously learn and improve rather than relying solely on large, infrequent process changes.

---

## Infrastructure and Deployment Automation

The course examined infrastructure practices that support repeatable and reliable application environments.

Topics included:

* Infrastructure as Code
* Automated environment creation
* Configuration management
* Servers and virtual machines
* Deployment automation
* Repeatable infrastructure
* Environment consistency

Infrastructure as Code demonstrated how infrastructure configuration can be managed using many of the same versioning, testing, and automation principles used for application source code.

---

## Resilience and Chaos Engineering

Chaos engineering was studied as an approach for evaluating how systems behave under unexpected conditions.

Concepts included intentionally introducing controlled failures to identify weaknesses before those weaknesses cause larger production incidents.

Netflix's Chaos Monkey was examined as a well-known example of using controlled failure to improve confidence in distributed system resilience.

---

## DevSecOps and Software Supply Chain Security

Security was examined as an integrated part of the software delivery lifecycle rather than a separate activity performed only near the end of development.

Topics included:

* DevSecOps
* Dependency scanning
* Software Composition Analysis (SCA)
* Vulnerable third-party components
* Source code integrity
* Code signing
* Protected source code branches
* Secure software development practices
* Software supply chain security

Coursework also examined guidance from organizations and resources such as NIST, OWASP, GitHub, and industry research.

These practices demonstrated how automated security controls can be incorporated throughout development and delivery pipelines.

---

## Continuous Monitoring and Auditing

The final portion of the course examined how DevOps practices can support security monitoring, compliance, and auditing without unnecessarily slowing software delivery.

Topics included:

* Information Security Continuous Monitoring
* Continuous auditing
* Automated evidence collection
* Integrating auditors with DevOps teams
* Automated security and compliance controls
* Traceability
* Monitoring system changes
* Balancing delivery speed with governance requirements

These concepts demonstrated how auditing and compliance activities can become part of the development and delivery process instead of relying entirely on large manual reviews performed after development is complete.

---

## Technologies and Tools

Technologies, platforms, and practices explored throughout the course included:

* **Git**
* **GitHub**
* **Version Control**
* **Continuous Integration**
* **Continuous Delivery**
* **Deployment Pipelines**
* **Infrastructure as Code**
* **Automated Testing**
* **Telemetry and Monitoring**
* **Software Composition Analysis**
* **Value-Stream Mapping**
* **Microsoft Word**
* **Microsoft PowerPoint**

The course focused primarily on understanding and applying DevOps principles and practices rather than developing applications in a single programming language.

---

## Skills Developed

This course strengthened my understanding of:

* Applying DevOps principles throughout the software lifecycle
* Using version control as part of a collaborative development workflow
* Understanding continuous integration and delivery practices
* Designing and reviewing software test plans
* Analyzing software delivery processes using value-stream mapping
* Identifying bottlenecks and opportunities for process improvement
* Comparing monolithic and microservices architectures
* Understanding incremental application modernization
* Applying telemetry and observability concepts
* Understanding Infrastructure as Code
* Evaluating software resilience through chaos engineering concepts
* Integrating security earlier in the development lifecycle
* Understanding dependency and software supply chain risks
* Applying continuous monitoring concepts
* Understanding continuous auditing and automated compliance
* Evaluating the relationship between software delivery speed, stability, security, and organizational processes
* Researching and communicating technical concepts through professional written assignments and presentations

Overall, the course provided a broader understanding of DevOps as a combination of **culture, architecture, automation, measurement, security, and continuous learning**, rather than simply a collection of development tools.

---

## Author

**Wade Eckert**  
Bellevue University  
Bachelor of Science in Software Development and Mathematics
