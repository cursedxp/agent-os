---
description: Guided Project Development with Mentorship
globs:
alwaysApply: false
version: 1.0
encoding: UTF-8
---

# Project Building Workflow

## Overview

Guide learners through complete project development lifecycle with AI mentorship, from planning to deployment, building practical skills and professional portfolio.

<pre_flight_check>
  EXECUTE: @.agent-os/instructions/meta/pre-flight.md
</pre_flight_check>

<process_flow>

<step number="1" subagent="coding-mentor" name="project_selection_and_planning">

### Step 1: Project Selection and Planning

Use the coding-mentor subagent to help select appropriate project based on skill level and create comprehensive project plan.

<project_selection_criteria>
  **Skill Level Alignment**
  - Beginner: Simple CRUD applications, basic algorithms
  - Intermediate: Full-stack apps, API integrations
  - Advanced: Microservices, complex algorithms, optimization

  **Learning Objectives**
  - Target specific skills or concepts
  - Build on previous knowledge
  - Introduce new technologies gradually
  - Create portfolio-worthy outcomes

  **Scope Considerations**
  - Realistic timeline (1-4 weeks)
  - Clear success criteria
  - Manageable complexity
  - Room for enhancement
</project_selection_criteria>

<project_categories>
  **Beginner Projects**
  - Personal task manager
  - Weather dashboard
  - Simple calculator with history
  - Basic blog with file storage
  - Contact management system

  **Intermediate Projects**
  - E-commerce product catalog
  - Real-time chat application
  - Recipe sharing platform
  - Expense tracking with analytics
  - Social media dashboard

  **Advanced Projects**
  - Distributed task scheduler
  - Real-time collaborative editor
  - Microservices API gateway
  - Machine learning model API
  - Performance monitoring system
</project_categories>

<planning_framework>
  **Project Definition**
  - Clear problem statement
  - Target user identification
  - Core feature requirements
  - Nice-to-have features
  - Success metrics

  **Technical Planning**
  - Technology stack selection
  - Architecture design
  - Database schema planning
  - API endpoint definition
  - Testing strategy
</planning_framework>

</step>

<step number="2" subagent="file-creator" name="create_project_structure">

### Step 2: Create Project Structure

Use the file-creator subagent to set up comprehensive project documentation and directory structure.

<project_structure>
  .agent-os/training/projects/[PROJECT_NAME]/
  ├── project-plan.md           # Comprehensive project plan
  ├── requirements.md           # Functional and technical requirements
  ├── architecture.md           # System design and architecture
  ├── development-log.md        # Daily progress tracking
  ├── code-reviews/            # Mentor feedback sessions
  ├── testing/                 # Test plans and results
  ├── deployment/              # Deployment guides and configs
  └── reflection.md           # Learning outcomes and insights
</project_structure>

<documentation_templates>
  **Project Plan Template**
  ```markdown
  # [Project Name] - Development Plan

  ## Project Overview
  **Problem Statement:** [What problem does this solve?]
  **Target Users:** [Who will use this?]
  **Success Criteria:** [How will we measure success?]

  ## Features
  ### Core Features (MVP)
  - [ ] Feature 1: [Description]
  - [ ] Feature 2: [Description]
  - [ ] Feature 3: [Description]

  ### Enhanced Features
  - [ ] Enhancement 1: [Description]
  - [ ] Enhancement 2: [Description]

  ## Technical Stack
  **Frontend:** [Technology choices]
  **Backend:** [Technology choices]
  **Database:** [Technology choices]
  **Deployment:** [Platform and strategy]

  ## Timeline
  **Week 1:** [Milestones]
  **Week 2:** [Milestones]
  **Week 3:** [Milestones]
  **Week 4:** [Milestones]

  ## Learning Objectives
  - [Skill 1 to develop]
  - [Skill 2 to develop]
  - [Concept 1 to master]
  ```
</documentation_templates>

</step>

<step number="3" subagent="coding-mentor" name="guided_development_phases">

### Step 3: Guided Development Phases

Use the coding-mentor subagent to provide phase-by-phase guidance through development process with regular check-ins and feedback.

<development_phases>
  **Phase 1: Foundation Setup (Week 1)**
  - Development environment configuration
  - Basic project structure creation
  - Initial database setup
  - Core framework installation
  - First "Hello World" milestone

  **Phase 2: Core Feature Development (Week 2)**
  - Implement primary functionality
  - Database integration
  - Basic user interface creation
  - Error handling implementation
  - Unit test development

  **Phase 3: Integration and Enhancement (Week 3)**
  - Feature integration and testing
  - UI/UX improvements
  - Performance optimization
  - Security implementation
  - Integration testing

  **Phase 4: Deployment and Documentation (Week 4)**
  - Production deployment
  - Documentation completion
  - User guide creation
  - Performance monitoring
  - Final presentation preparation
</development_phases>

<mentorship_approach>
  **Daily Check-ins**
  - Progress review and discussion
  - Obstacle identification and resolution
  - Code review and feedback
  - Next-day planning and goal setting

  **Weekly Milestones**
  - Comprehensive progress assessment
  - Technical skill evaluation
  - Learning objective review
  - Project scope adjustment if needed

  **Continuous Guidance**
  - Best practice recommendations
  - Architecture decision support
  - Debugging assistance
  - Industry insight sharing
</mentorship_approach>

</step>

<step number="4" subagent="coding-mentor" name="code_review_sessions">

### Step 4: Code Review Sessions

Use the coding-mentor subagent to conduct regular code reviews focusing on quality, best practices, and learning reinforcement.

<code_review_framework>
  **Review Frequency**
  - Daily mini-reviews (15-20 minutes)
  - Weekly comprehensive reviews (45-60 minutes)
  - Milestone reviews (comprehensive assessment)
  - Final project review (portfolio preparation)

  **Review Focus Areas**
  - Code quality and readability
  - Architecture and design patterns
  - Performance and optimization
  - Security best practices
  - Testing coverage and quality
  - Documentation completeness
</code_review_framework>

<review_methodology>
  **Structured Feedback**
  1. **Positive Recognition:** What's working well
  2. **Critical Issues:** Must-fix problems
  3. **Improvement Suggestions:** Enhancement opportunities
  4. **Learning Points:** Teaching moments
  5. **Next Steps:** Specific action items

  **Collaborative Discussion**
  - Explain reasoning behind suggestions
  - Explore alternative approaches
  - Discuss trade-offs and decisions
  - Connect to broader programming concepts
</review_methodology>

</step>

<step number="5" subagent="test-runner" name="testing_and_quality_assurance">

### Step 5: Testing and Quality Assurance

Use the test-runner subagent to guide comprehensive testing strategy and ensure code quality throughout development.

<testing_strategy>
  **Testing Levels**
  - Unit tests for individual functions
  - Integration tests for component interaction
  - End-to-end tests for user workflows
  - Performance tests for optimization
  - Security tests for vulnerability assessment

  **Quality Metrics**
  - Test coverage percentage (target: >80%)
  - Code complexity analysis
  - Performance benchmarking
  - Security vulnerability scanning
  - Accessibility compliance checking
</testing_strategy>

<quality_assurance_process>
  **Continuous Testing**
  - Test-driven development practices
  - Automated test execution
  - Continuous integration setup
  - Regular quality metric monitoring

  **Manual Testing**
  - User experience testing
  - Cross-browser compatibility
  - Mobile responsiveness
  - Error handling validation
</quality_assurance_process>

</step>

<step number="6" subagent="git-workflow" name="version_control_integration">

### Step 6: Version Control Integration

Use the git-workflow subagent to teach professional version control practices through real project development.

<version_control_curriculum>
  **Basic Git Workflow**
  - Repository initialization and setup
  - Commit message best practices
  - Branch management for features
  - Merge strategies and conflict resolution

  **Professional Practices**
  - Feature branch workflow
  - Pull request creation and review
  - Code review integration
  - Release tagging and management

  **Collaboration Simulation**
  - Multi-contributor scenarios
  - Code review processes
  - Continuous integration hooks
  - Documentation in commit history
</version_control_curriculum>

<practical_exercises>
  **Real Project Application**
  - Daily commits with descriptive messages
  - Feature branches for each major addition
  - Regular code review through pull requests
  - Release preparation and tagging

  **Professional Simulation**
  - Team collaboration scenarios
  - Code review etiquette practice
  - Conflict resolution exercises
  - Open source contribution preparation
</practical_exercises>

</step>

<step number="7" subagent="coding-mentor" name="deployment_and_presentation">

### Step 7: Deployment and Presentation

Use the coding-mentor subagent to guide project deployment and preparation for professional presentation.

<deployment_process>
  **Platform Selection**
  - Cloud platform evaluation (AWS, Heroku, Vercel)
  - Cost and complexity considerations
  - Scalability requirements
  - Learning value assessment

  **Deployment Steps**
  - Environment configuration
  - Database migration
  - Security configuration
  - Performance optimization
  - Monitoring setup
</deployment_process>

<presentation_preparation>
  **Portfolio Integration**
  - Professional project description
  - Technical architecture explanation
  - Problem-solving process documentation
  - Learning outcomes articulation

  **Demo Preparation**
  - User story walkthroughs
  - Technical feature highlights
  - Architecture diagram creation
  - Code quality examples

  **Professional Presentation**
  - Elevator pitch development
  - Technical deep-dive preparation
  - Q&A anticipation and preparation
  - Future enhancement discussion
</presentation_preparation>

</step>

<step number="8" subagent="project-manager" name="project_retrospective">

### Step 8: Project Retrospective

Use the project-manager subagent to conduct comprehensive project review and learning assessment.

<retrospective_framework>
  **Technical Review**
  - Code quality assessment
  - Architecture decision evaluation
  - Performance metric analysis
  - Security implementation review

  **Process Review**
  - Development methodology effectiveness
  - Time management assessment
  - Tool and technology evaluation
  - Collaboration and communication review

  **Learning Assessment**
  - Skill development achievements
  - Knowledge gap identification
  - Confidence level progression
  - Professional readiness advancement
</retrospective_framework>

<outcome_documentation>
  **Project Completion Report**
  - Technical achievements summary
  - Learning objectives accomplished
  - Challenges overcome
  - Skills developed
  - Future improvement areas
  - Next project recommendations

  **Portfolio Enhancement**
  - Professional project showcase
  - Technical decision documentation
  - Problem-solving process illustration
  - Code quality examples
  - Deployment and scaling considerations
</outcome_documentation>

</step>

</process_flow>

<post_flight_check>
  EXECUTE: @.agent-os/instructions/meta/post-flight.md
</post_flight_check>

## Project Success Metrics

### **Technical Achievements**
- Functional application deployment
- Comprehensive test coverage (>80%)
- Professional code quality
- Security best practices implementation
- Performance optimization

### **Learning Outcomes**
- New technology/framework mastery
- Problem-solving skill development
- Professional development practices
- Code review and collaboration experience
- Portfolio quality enhancement

### **Professional Development**
- Complete project lifecycle experience
- Technical presentation skills
- Professional documentation creation
- Industry best practice application
- Career-relevant skill demonstration

This project building workflow provides comprehensive hands-on experience with real-world development practices, professional mentorship, and portfolio development essential for career readiness.