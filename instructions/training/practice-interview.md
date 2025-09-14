---
description: Technical Interview Practice and Preparation
globs:
alwaysApply: false
version: 1.0
encoding: UTF-8
---

# Interview Practice Workflow

## Overview

Simulate realistic technical interviews with comprehensive preparation, practice sessions, and detailed feedback to build confidence and competence.

<pre_flight_check>
  EXECUTE: @.agent-os/instructions/meta/pre-flight.md
</pre_flight_check>

<process_flow>

<step number="1" subagent="coding-mentor" name="interview_preparation_assessment">

### Step 1: Interview Preparation Assessment

Use the coding-mentor subagent to evaluate current interview readiness and create targeted preparation plan.

<readiness_assessment>
  **Technical Skills Evaluation**
  - Algorithm and data structure knowledge
  - System design understanding
  - Programming language proficiency
  - Problem-solving approach

  **Interview Skills Assessment**
  - Communication clarity
  - Problem breakdown ability
  - Code organization under pressure
  - Question asking and clarification

  **Confidence and Mindset**
  - Performance anxiety level
  - Self-presentation skills
  - Failure recovery ability
  - Professional demeanor
</readiness_assessment>

</step>

<step number="2" subagent="coding-mentor" name="mock_technical_screening">

### Step 2: Mock Technical Screening

Use the coding-mentor subagent to conduct realistic phone/video technical screening simulation.

<screening_format>
  **Duration**: 45-60 minutes
  **Format**: Live coding with screen sharing
  **Focus Areas**:
  - Basic programming concepts
  - Algorithm implementation
  - Code explanation and communication
  - Problem-solving process demonstration

  **Common Questions**:
  - Array/string manipulation problems
  - Basic data structure operations
  - Simple algorithm implementations
  - Code optimization discussions
</screening_format>

</step>

<step number="3" subagent="coding-mentor" name="on_site_coding_challenge">

### Step 3: On-site Coding Challenge

Use the coding-mentor subagent to simulate comprehensive on-site technical interview experience.

<coding_challenge_structure>
  **Problem Categories**:
  - Arrays and strings
  - Linked lists and trees
  - Dynamic programming
  - Graph algorithms
  - System design basics

  **Evaluation Criteria**:
  - Problem understanding
  - Solution approach
  - Code quality and style
  - Edge case consideration
  - Time and space complexity analysis
  - Communication throughout process
</coding_challenge_structure>

</step>

<step number="4" subagent="coding-mentor" name="system_design_interview">

### Step 4: System Design Interview

Use the coding-mentor subagent to conduct system design interview simulation for mid to senior level positions.

<system_design_framework>
  **Problem Types**:
  - Design a URL shortener
  - Design a social media feed
  - Design a chat system
  - Design a file storage system
  - Design a recommendation system

  **Evaluation Approach**:
  - Requirements gathering
  - High-level architecture
  - Database design
  - API design
  - Scalability considerations
  - Trade-off discussions
</system_design_framework>

</step>

<step number="5" subagent="coding-mentor" name="behavioral_interview_practice">

### Step 5: Behavioral Interview Practice

Use the coding-mentor subagent to practice behavioral questions and professional presentation.

<behavioral_question_categories>
  **Leadership and Initiative**
  - \"Tell me about a time you led a project\"
  - \"Describe a situation where you had to make a difficult decision\"
  - \"How do you handle conflicts in a team?\"

  **Problem Solving**
  - \"Describe a challenging technical problem you solved\"
  - \"Tell me about a time you failed and what you learned\"
  - \"How do you approach learning new technologies?\"

  **Communication and Teamwork**
  - \"Describe your ideal work environment\"
  - \"How do you handle feedback and criticism?\"
  - \"Tell me about a time you had to explain something technical to a non-technical person\"
</behavioral_question_categories>

<star_method_coaching>
  **STAR Framework**:
  - **Situation**: Set the context
  - **Task**: Describe your responsibility
  - **Action**: Explain what you did
  - **Result**: Share the outcome and learning

  **Practice Areas**:
  - Story development and refinement
  - Concise and compelling delivery
  - Connecting experiences to job requirements
  - Professional presentation skills
</star_method_coaching>

</step>

<step number="6" subagent="file-creator" name="create_interview_preparation_materials">

### Step 6: Create Interview Preparation Materials

Use the file-creator subagent to generate comprehensive interview preparation documentation and resources.

<preparation_materials>
  .agent-os/training/interview-prep/
  ├── technical-study-guide.md    # Algorithm and data structure review
  ├── coding-problems/           # Practice problem sets
  │   ├── easy/
  │   ├── medium/
  │   └── hard/
  ├── system-design/            # Design problem practice
  ├── behavioral-stories.md     # STAR method examples
  ├── company-research/         # Target company information
  └── mock-interview-feedback/  # Performance tracking
</preparation_materials>

</step>

<step number="7" subagent="coding-mentor" name="performance_feedback_and_coaching">

### Step 7: Performance Feedback and Coaching

Use the coding-mentor subagent to provide detailed performance analysis and improvement coaching.

<feedback_framework>
  **Technical Performance**
  - Problem-solving approach effectiveness
  - Code quality and organization
  - Algorithm and complexity understanding
  - Edge case consideration
  - Communication during coding

  **Interview Skills**
  - Question clarification ability
  - Structured thinking demonstration
  - Professional communication
  - Pressure handling
  - Recovery from mistakes

  **Improvement Recommendations**
  - Specific technical areas to strengthen
  - Communication skills development
  - Confidence building strategies
  - Interview strategy refinement
</feedback_framework>

</step>

<step number="8" subagent="project-manager" name="interview_readiness_assessment">

### Step 8: Interview Readiness Assessment

Use the project-manager subagent to evaluate overall interview preparedness and create final preparation plan.

<readiness_criteria>
  **Technical Readiness**
  - Can solve medium-level algorithm problems
  - Understands time/space complexity
  - Can design basic systems
  - Explains technical concepts clearly

  **Professional Readiness**
  - Has compelling behavioral stories
  - Demonstrates professional communication
  - Shows appropriate confidence level
  - Handles pressure situations well

  **Strategic Readiness**
  - Researched target companies
  - Prepared thoughtful questions
  - Understands compensation negotiation
  - Has follow-up strategy
</readiness_criteria>

</step>

</process_flow>

<post_flight_check>
  EXECUTE: @.agent-os/instructions/meta/post-flight.md
</post_flight_check>

## Interview Success Metrics

### **Technical Competency**
- Solves 80%+ of coding problems correctly
- Demonstrates clear problem-solving process
- Writes clean, efficient code under pressure
- Explains solutions clearly and confidently

### **Communication Excellence**
- Asks clarifying questions appropriately
- Explains thinking process clearly
- Handles feedback and hints well
- Maintains professional demeanor

### **Strategic Preparation**
- Researches companies thoroughly
- Prepares compelling behavioral stories
- Develops thoughtful questions
- Understands role requirements clearly

This interview practice workflow builds both technical competency and professional confidence essential for successful job acquisition in competitive technical markets.