---
description: Comprehensive Skill Assessment for Developer Training
globs:
alwaysApply: false
version: 1.0
encoding: UTF-8
---

# Skill Assessment Workflow

## Overview

Conduct comprehensive evaluation of programming skills, learning preferences, and career goals to create personalized development path.

<pre_flight_check>
  EXECUTE: @.agent-os/instructions/meta/pre-flight.md
</pre_flight_check>

<process_flow>

<step number="1" subagent="coding-mentor" name="technical_skills_evaluation">

### Step 1: Technical Skills Evaluation

Use the coding-mentor subagent to assess current programming knowledge through interactive questioning and practical exercises.

<evaluation_framework>
  **Programming Fundamentals**
  - Variable types and declarations
  - Control structures (if/else, loops)
  - Function definition and calling
  - Basic data structures (arrays, objects)

  **Intermediate Concepts**
  - Object-oriented programming principles
  - Error handling and debugging
  - File I/O operations
  - API consumption basics

  **Advanced Topics**
  - Algorithm complexity analysis
  - Design patterns recognition
  - Database design principles
  - System architecture understanding
</evaluation_framework>

<assessment_method>
  **Interactive Questioning (30 minutes)**
  - Concept explanation requests
  - Code reading comprehension
  - Problem-solving approach discussion
  - Best practice identification

  **Practical Coding (45 minutes)**
  - Simple algorithm implementation
  - Debug broken code samples
  - Refactor poorly written code
  - Write unit tests for given functions
</assessment_method>

</step>

<step number="2" subagent="coding-mentor" name="learning_style_analysis">

### Step 2: Learning Style Analysis

Use the coding-mentor subagent to understand how the individual learns best and their preferred learning environment.

<learning_preferences>
  **Learning Modalities**
  - Visual learner (diagrams, flowcharts)
  - Auditory learner (explanations, discussions)
  - Kinesthetic learner (hands-on practice)
  - Reading/writing learner (documentation, notes)

  **Pace Preferences**
  - Fast-paced intensive learning
  - Steady consistent progress
  - Deep dive focused sessions
  - Broad overview then details

  **Environment Factors**
  - Solo vs group learning
  - Structured vs flexible schedule
  - Immediate feedback vs self-paced
  - Theory-first vs practice-first
</learning_preferences>

</step>

<step number="3" subagent="context-fetcher" name="career_goal_gathering">

### Step 3: Career Goal Gathering

Use the context-fetcher subagent to understand career aspirations, timeline, and constraints.

<career_exploration>
  **Target Roles**
  - Frontend developer
  - Backend developer
  - Full-stack developer
  - Mobile app developer
  - DevOps engineer
  - Data scientist/engineer

  **Industry Preferences**
  - Startup vs enterprise
  - Remote vs on-site
  - Specific sectors (fintech, healthcare, etc.)
  - Company size preferences

  **Timeline and Constraints**
  - Available study hours per week
  - Target job application date
  - Financial considerations
  - Family/work obligations
</career_exploration>

</step>

<step number="4" subagent="file-creator" name="create_assessment_results">

### Step 4: Create Assessment Results

Use the file-creator subagent to document comprehensive assessment results and recommendations.

<assessment_output>
  .agent-os/training/
  ├── assessment-results.md      # Detailed evaluation
  ├── skill-gaps-analysis.md    # Areas for improvement
  ├── learning-recommendations.md # Personalized approach
  └── career-pathway.md          # Professional development plan
</assessment_output>

<results_template>
  # Skill Assessment Results

  > Assessment Date: [CURRENT_DATE]
  > Duration: [ASSESSMENT_TIME]
  > Evaluator: AI Coding Mentor

  ## Current Skill Level: [SKILL_LEVEL]

  ### Technical Competencies
  **Strengths:**
  - [IDENTIFIED_STRENGTHS]

  **Areas for Improvement:**
  - [IMPROVEMENT_AREAS]

  **Knowledge Gaps:**
  - [CRITICAL_GAPS]

  ### Learning Profile
  **Preferred Style:** [LEARNING_STYLE]
  **Optimal Pace:** [LEARNING_PACE]
  **Best Environment:** [LEARNING_ENVIRONMENT]

  ### Career Alignment
  **Target Role:** [CAREER_GOAL]
  **Timeline:** [TARGET_DATE]
  **Key Requirements:** [JOB_REQUIREMENTS]

  ## Recommended Learning Path

  **Phase 1 (Weeks 1-X):** [FOUNDATIONAL_TOPICS]
  **Phase 2 (Weeks X-Y):** [CORE_SKILLS]
  **Phase 3 (Weeks Y-Z):** [ADVANCED_CONCEPTS]
  **Phase 4 (Weeks Z+):** [SPECIALIZATION]

  ## Next Steps
  1. [IMMEDIATE_ACTION_1]
  2. [IMMEDIATE_ACTION_2]
  3. [IMMEDIATE_ACTION_3]
</results_template>

</step>

<step number="5" subagent="coding-mentor" name="personalized_recommendations">

### Step 5: Personalized Recommendations

Use the coding-mentor subagent to create specific learning recommendations based on assessment results.

<recommendation_categories>
  **Learning Resources**
  - Books suited to learning style
  - Online courses and tutorials
  - Practice platforms and challenges
  - Community forums and groups

  **Project Suggestions**
  - Beginner-appropriate starter projects
  - Progressive skill-building exercises
  - Portfolio-worthy applications
  - Open source contribution opportunities

  **Study Schedule**
  - Weekly time allocation recommendations
  - Daily practice suggestions
  - Milestone checkpoints
  - Review and reinforcement cycles
</recommendation_categories>

</step>

</process_flow>

<post_flight_check>
  EXECUTE: @.agent-os/instructions/meta/post-flight.md
</post_flight_check>

## Assessment Criteria

### **Skill Level Definitions**

**Absolute Beginner (0-1 months experience)**
- No programming experience
- Unfamiliar with development tools
- Needs foundational computer science concepts

**Novice (1-6 months experience)**
- Basic syntax knowledge in one language
- Can write simple programs with guidance
- Limited debugging skills

**Beginner (6-12 months experience)**
- Comfortable with basic programming constructs
- Can complete small projects independently
- Understanding of fundamental data structures

**Intermediate (1-2 years experience)**
- Proficient in at least one language
- Understanding of object-oriented programming
- Can design and implement medium-sized applications

**Advanced (2+ years experience)**
- Multiple language proficiency
- Understanding of design patterns and architecture
- Can mentor others and lead technical decisions

### **Learning Path Customization**

Based on assessment results, the system creates one of several learning tracks:

**Accelerated Track (Advanced beginners)**
- Faster pace through fundamentals
- Early introduction to frameworks
- Focus on practical application

**Foundation Track (Absolute beginners)**
- Thorough coverage of basics
- Heavy practice and repetition
- Gradual complexity increase

**Specialization Track (Career changers)**
- Targeted skill development
- Industry-specific technologies
- Professional practice emphasis

This assessment workflow ensures every learner receives a training program perfectly matched to their current abilities, learning preferences, and career objectives.