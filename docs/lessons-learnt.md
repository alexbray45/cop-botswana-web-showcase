# 📚 Lessons Learned

## Overview

The Church of Pentecost Botswana Website has been more than a website development project—it has been an opportunity to apply software engineering principles to a real-world digital platform.

Throughout the project, valuable lessons have been learned in project planning, frontend architecture, documentation, version control, repository management, performance optimisation, and iterative software development.

These lessons continue to shape both the technical implementation of the platform and the overall engineering approach adopted throughout the project.

---

# Understanding the Problem Before Building

One of the earliest lessons was the importance of understanding the organisation's needs before writing code.

Rather than immediately designing web pages, time was invested in understanding:

- The church's communication goals.
- The needs of members and first-time visitors.
- How information should be organised.
- The long-term vision for the platform.

This reinforced that successful software begins with understanding the problem rather than selecting technologies.

---

# Planning Improves Development

Developing documentation before implementation significantly reduced uncertainty during development.

Creating artefacts such as:

- Business Analysis
- Software Requirements Specification (SRS)
- Information Architecture
- Sitemap
- Wireframes
- Design System

provided a clear roadmap that guided implementation and made future enhancements easier to plan.

This highlighted the value of planning as an integral part of software engineering rather than an optional activity.

---

# Incremental Delivery Creates Early Value

Rather than waiting until every planned feature was complete, the project adopted an incremental delivery strategy.

The first milestone focused on delivering a professional homepage that established the church's digital presence while additional pages and functionality continued to be developed.

This approach demonstrated that software can provide value long before every planned feature has been implemented.

It also allows continuous feedback, iterative improvement, and reduced project risk.

---

# Technology Decisions Should Support Business Goals

A significant lesson was that technology choices should be driven by project requirements rather than trends.

Choosing HTML5, CSS3, and Vanilla JavaScript for the initial release allowed the website to be delivered quickly, remain lightweight, and provide immediate value to members and visitors.

The project has been intentionally designed so that, as requirements evolve, the frontend can transition to React.js and integrate backend services without requiring a complete redesign.

This reinforced the importance of selecting technologies that align with the project's current objectives while supporting future scalability.

---

# Repository Optimisation and Version Control

One of the most valuable technical challenges involved optimising the project's Git repository.

As development progressed, the repository grew to more than **6 GB** due to a large collection of high-resolution gallery images. This significantly affected repository performance, making cloning, pushing, and maintaining the project slower and less efficient.

To address the issue:

- The repository was analysed to identify the source of the large file sizes.
- Gallery images were optimised for web delivery while maintaining visual quality.
- Git history was carefully rewritten to remove obsolete assets.
- The optimised assets were restored without disrupting ongoing development.

This experience demonstrated that maintaining a healthy repository is an essential aspect of software engineering and requires careful planning, risk management, and an understanding of version control best practices.

---

# Building Better Development Workflows

The repository optimisation process also provided an opportunity to improve the overall development workflow.

Several professional practices were introduced, including:

- GitHub Issues
- Feature branches
- Pull requests
- Code reviews
- Project milestones
- Automated GitHub workflows

These practices improved project organisation, simplified collaboration, and created a more structured development process.

This reinforced that effective software engineering extends beyond writing code to include well-defined development workflows and project management practices.

---

# Performance and User Experience Matter

The project emphasised that a successful website is measured not only by its appearance but also by its performance and usability.

Homepage optimisation activities included:

- Performance improvements
- Responsive design
- SEO enhancements
- Functional testing

These efforts demonstrated that user experience is closely tied to technical quality and should be considered throughout development rather than as a final step.

---

# Documentation is a Long-Term Investment

Maintaining comprehensive documentation throughout the project has proven invaluable.

Documentation captures architectural decisions, project requirements, design rationale, and future plans, making the project easier to maintain and evolve.

It also serves as a communication tool for future contributors and stakeholders while demonstrating a structured engineering approach.

---

# Software Engineering Extends Beyond Code

Perhaps the most significant lesson from this project is that software engineering involves much more than implementing application features.

It requires:

- Understanding business objectives.
- Analysing technical problems.
- Evaluating alternative solutions.
- Managing project risk.
- Maintaining development workflows.
- Writing clear documentation.
- Planning for future scalability.
- Continuously improving both the product and the development process.

The repository optimisation challenge clearly demonstrated that solving engineering problems often involves infrastructure, tooling, and process improvements in addition to writing code.

---

# Looking Ahead

The lessons learned during this project continue to influence future development.

Current work focuses on:

- Completing the remaining website pages.
- Implementing dynamic content.
- Integrating the Bible API.
- Supporting multiple languages.

Future development will expand the platform through:

- Backend APIs.
- Authentication.
- Content Management System (CMS).
- Member & Leaders Portal.
- Event Registration.
- Prayer Request Platform.
- React.js migration.

Each new phase builds upon the engineering practices established during the initial stages of the project.

---

# Key Takeaways

This project reinforced several important software engineering principles:

- Understand the problem before implementing the solution.
- Plan before building.
- Deliver value through incremental releases.
- Choose technologies based on project needs.
- Prioritise maintainability from the beginning.
- Treat version control as an engineering discipline.
- Invest in documentation throughout the project lifecycle.
- Continuously improve both the product and the development process.

---

# Conclusion

The Church of Pentecost Botswana Website has been a valuable software engineering experience that extends well beyond frontend development.

It has reinforced the importance of thoughtful planning, structured documentation, iterative delivery, repository management, performance optimisation, and professional development workflows.

Most importantly, the project has demonstrated that successful software engineering is about creating sustainable, maintainable, and scalable solutions that continue to deliver value as both technology and organisational needs evolve.
