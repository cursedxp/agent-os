---
description: Professional Developer Training Workflow
globs:
alwaysApply: false
version: 1.0
encoding: UTF-8
---

# Professional Developer Training Workflow

## Overview

Transform individuals into professional developers through structured, hands-on learning with AI mentorship, real-world projects, and industry best practices.

<pre_flight_check>
  EXECUTE: @.agent-os/instructions/meta/pre-flight.md
</pre_flight_check>

<process_flow>

<step number="1" subagent="coding-mentor" name="comprehensive_skill_assessment">

### Step 1: Comprehensive Skill Assessment

Use the coding-mentor subagent to conduct thorough evaluation of current technical skills, learning preferences, and career goals.

<assessment_framework>
  <technical_evaluation>
    - Programming language familiarity
    - Data structures and algorithms knowledge
    - Software engineering concepts
    - Database and API understanding
    - Version control experience
    - Testing methodology awareness
  </technical_evaluation>
  <learning_profile>
    - Preferred learning style (visual, hands-on, reading, auditory)
    - Time availability and commitment level
    - Previous education/training background
    - Specific career interests (web, mobile, backend, etc.)
  </learning_profile>
  <goal_setting>
    - Short-term objectives (3-6 months)
    - Long-term career aspirations
    - Target companies or roles
    - Salary and location preferences
  </goal_setting>
</assessment_framework>

<skill_levels>
  - **Absolute Beginner**: No programming experience
  - **Novice**: Basic syntax knowledge, simple programs
  - **Beginner**: Basic concepts, small projects completed
  - **Intermediate**: Data structures, algorithms, object-oriented programming
  - **Advanced**: Design patterns, architecture, complex applications
  - **Professional Ready**: Industry practices, team collaboration, production experience
</skill_levels>

</step>

<step number="2" subagent="context-fetcher" name="gather_industry_context">

### Step 2: Gather Industry Context

Use the context-fetcher subagent to retrieve relevant industry standards, job requirements, and current technology trends for the learner's target career path.

<context_sources>
  - Job market analysis for target role
  - Technology stack requirements
  - Salary benchmarks and growth projections
  - Required vs preferred qualifications
  - Industry best practices and standards
</context_sources>

</step>

<step number="3" subagent="file-creator" name="create_personalized_learning_path">

### Step 3: Create Personalized Learning Path

Use the file-creator subagent to generate comprehensive learning documentation tailored to the individual's assessment results and career goals.

<learning_path_structure>
  .agent-os/training/
  ├── assessment-results.md         # Detailed skill evaluation
  ├── learning-path.md             # Personalized roadmap
  ├── progress-tracker.md          # Milestone tracking
  ├── career-roadmap.md            # Professional development plan
  └── resources/                   # Curated learning materials
      ├── fundamentals/
      ├── intermediate/
      ├── advanced/
      └── professional/
</learning_path_structure>

<learning_phases>
  **Phase 1: Foundations (Weeks 1-8)**
  - Programming fundamentals
  - Basic data structures
  - Problem-solving methodology
  - Development environment setup

  **Phase 2: Core Skills (Weeks 9-16)**
  - Advanced data structures and algorithms
  - Object-oriented programming
  - Database fundamentals
  - Version control mastery

  **Phase 3: Application Development (Weeks 17-24)**
  - Full-stack development
  - API design and integration
  - Testing methodologies
  - Project architecture

  **Phase 4: Professional Practices (Weeks 25-32)**
  - Code review processes
  - Team collaboration
  - Deployment and DevOps
  - Performance optimization

  **Phase 5: Specialization (Weeks 33-40)**
  - Domain-specific skills
  - Advanced frameworks
  - System design
  - Leadership and mentoring
</learning_phases>

</step>

<step number="4" subagent="coding-mentor" name="foundational_concept_teaching">

### Step 4: Foundational Concept Teaching

Use the coding-mentor subagent to deliver core programming concepts through interactive teaching, practical examples, and hands-on exercises.

<teaching_methodology>
  **EDUCA Method Application:**
  - **E**xplain: Clear, jargon-free explanations with analogies
  - **D**emonstrate: Working code examples and live coding
  - **U**nderstand: Comprehension checks and Q&A
  - **C**onnect: Relate to real-world applications
  - **A**pply: Guided practice exercises
</teaching_methodology>

<core_concepts>
  **Programming Fundamentals**
  - Variables and data types
  - Control structures (loops, conditionals)
  - Functions and scope
  - Error handling and debugging

  **Data Structures**
  - Arrays and lists
  - Hash tables and dictionaries
  - Trees and graphs
  - Stacks and queues

  **Algorithms**
  - Sorting and searching
  - Recursion
  - Dynamic programming
  - Time and space complexity

  **Software Engineering**
  - Clean code principles
  - Design patterns
  - SOLID principles
  - Testing strategies
</core_concepts>

</step>

<step number="5" subagent="file-creator" name="create_practice_projects">

### Step 5: Create Practice Projects

Use the file-creator subagent to generate progressive project assignments that build skills incrementally while creating a professional portfolio.

<project_progression>
  **Beginner Projects**
  - Calculator application
  - Todo list with persistence
  - Simple web scraper
  - Basic CRUD application

  **Intermediate Projects**
  - REST API with authentication
  - Real-time chat application
  - E-commerce product catalog
  - Data visualization dashboard

  **Advanced Projects**
  - Microservices architecture
  - Full-stack social media app
  - Real-time multiplayer game
  - Machine learning integration

  **Capstone Project**
  - Original application solving real problem
  - Complete development lifecycle
  - Production deployment
  - Documentation and presentation
</project_progression>

<project_structure>
  .agent-os/training/projects/
  ├── phase-1-beginner/
  │   ├── calculator/
  │   ├── todo-app/
  │   └── web-scraper/
  ├── phase-2-intermediate/
  │   ├── rest-api/
  │   ├── chat-app/
  │   └── ecommerce-catalog/
  ├── phase-3-advanced/
  │   ├── microservices/
  │   ├── social-media/
  │   └── multiplayer-game/
  └── capstone/
      └── [custom-project]/
</project_structure>

</step>

<step number="6" subagent="coding-mentor" name="interactive_coding_sessions">

### Step 6: Interactive Coding Sessions

Use the coding-mentor subagent to conduct live coding sessions, pair programming exercises, and interactive problem-solving.

<session_types>
  **Live Coding Demonstrations**
  - Step-by-step implementation
  - Thought process explanation
  - Common pitfall identification
  - Best practice highlighting

  **Pair Programming**
  - Collaborative problem solving
  - Real-time code review
  - Knowledge sharing
  - Communication skill development

  **Code Review Sessions**
  - Critical analysis of submitted code
  - Improvement suggestions
  - Pattern recognition
  - Industry standard comparison

  **Debugging Workshops**
  - Systematic debugging approach
  - Tool utilization
  - Error pattern recognition
  - Prevention strategies
</session_types>

</step>

<step number="7" subagent="test-runner" name="skill_validation_and_testing">

### Step 7: Skill Validation and Testing

Use the test-runner subagent to evaluate code quality, run automated tests, and validate skill progression through practical assessments.

<validation_framework>
  **Code Quality Metrics**
  - Coding standard compliance
  - Test coverage percentage
  - Cyclomatic complexity analysis
  - Performance benchmarking

  **Skill Assessments**
  - Algorithm implementation challenges
  - System design exercises
  - Code review evaluations
  - Debugging problem solving

  **Project Evaluations**
  - Functionality completeness
  - Code architecture quality
  - Documentation standards
  - User experience design
</validation_framework>

<progression_gates>
  **Phase Completion Criteria**
  - All concept quizzes passed (80%+ score)
  - Project requirements met
  - Code review approval received
  - Peer feedback incorporated

  **Professional Readiness Indicators**
  - Portfolio of 5+ substantial projects
  - Demonstrated debugging ability
  - Clean, well-documented code
  - Understanding of software lifecycle
</progression_gates>

</step>

<step number="8" subagent="git-workflow" name="version_control_mastery">

### Step 8: Version Control Mastery

Use the git-workflow subagent to teach professional git workflows, collaboration practices, and code management strategies.

<git_curriculum>
  **Basic Git Operations**
  - Repository initialization and cloning
  - Staging and committing changes
  - Branch creation and merging
  - Remote repository management

  **Advanced Git Workflows**
  - Feature branch workflow
  - Git flow methodology
  - Conflict resolution strategies
  - Interactive rebase and history editing

  **Collaboration Practices**
  - Pull request creation and review
  - Code review etiquette
  - Continuous integration setup
  - Release management
</git_curriculum>

<practical_exercises>
  - Multi-contributor project simulation
  - Merge conflict resolution scenarios
  - Code review process participation
  - Open source contribution practice
</practical_exercises>

</step>

<step number="9" subagent="coding-mentor" name="interview_preparation">

### Step 9: Interview Preparation

Use the coding-mentor subagent to simulate technical interviews, provide feedback, and build confidence for job applications.

<interview_components>
  **Technical Coding Challenges**
  - Algorithm and data structure problems
  - System design discussions
  - Code optimization exercises
  - Debugging scenarios

  **Behavioral Interviews**
  - STAR method practice
  - Career story development
  - Technical experience articulation
  - Team collaboration examples

  **Portfolio Presentation**
  - Project demonstration skills
  - Technical decision explanation
  - Problem-solving process description
  - Future enhancement discussions
</interview_components>

<mock_interview_process>
  1. Pre-interview preparation and research
  2. Technical screening simulation
  3. On-site interview experience
  4. Detailed feedback and improvement areas
  5. Follow-up practice sessions
</mock_interview_process>

</step>

<step number="10" subagent="project-manager" name="professional_readiness_assessment">

### Step 10: Professional Readiness Assessment

Use the project-manager subagent to evaluate overall progress, assess job readiness, and create a transition plan to professional development roles.

<readiness_evaluation>
  **Technical Competency**
  - Programming language proficiency
  - Framework and library knowledge
  - Database and API integration skills
  - Testing and debugging capabilities

  **Professional Skills**
  - Code review and collaboration
  - Project management understanding
  - Communication and documentation
  - Continuous learning mindset

  **Portfolio Quality**
  - Project diversity and complexity
  - Code quality and documentation
  - Deployed application examples
  - Open source contributions
</readiness_evaluation>

<transition_planning>
  **Job Search Strategy**
  - Target company identification
  - Application customization
  - Networking opportunities
  - Interview scheduling

  **Continuing Education**
  - Advanced topic exploration
  - Industry certification pursuit
  - Conference and community participation
  - Mentoring junior developers
</transition_planning>

<graduation_criteria>
  ✓ Completed all learning phases
  ✓ Built portfolio of 8+ projects
  ✓ Passed technical assessments
  ✓ Demonstrated collaboration skills
  ✓ Received positive code reviews
  ✓ Successfully completed mock interviews
  ✓ Created professional online presence
  ✓ Identified target job opportunities
</graduation_criteria>

</step>

</process_flow>

<post_flight_check>
  EXECUTE: @.agent-os/instructions/meta/post-flight.md
</post_flight_check>

## Success Metrics

### **Quantitative Measures**
- Code quality scores (>85%)
- Test coverage (>80%)
- Project completion rate (100%)
- Interview success rate (>70%)

### **Qualitative Indicators**
- Confidence in problem-solving
- Ability to explain technical concepts
- Collaborative coding skills
- Professional communication

### **Career Outcomes**
- Job placement within 6 months
- Competitive salary offers
- Positive employer feedback
- Continued skill development

## Support Structure

### **Continuous Mentorship**
- Weekly one-on-one sessions
- On-demand help and guidance
- Career advice and planning
- Industry insights and trends

### **Peer Learning**
- Coding study groups
- Project collaboration
- Code review exchanges
- Interview practice partnerships

### **Community Integration**
- Open source project participation
- Developer meetup attendance
- Online community engagement
- Conference and workshop participation

This workflow transforms motivated individuals into job-ready professional developers through systematic skill building, practical project experience, and comprehensive career preparation.