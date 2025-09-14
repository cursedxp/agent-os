---
description: Comprehensive Code Review and Improvement Guidance
globs:
alwaysApply: false
version: 1.0
encoding: UTF-8
---

# Code Review Workflow

## Overview

Provide detailed code analysis, improvement suggestions, and mentorship through comprehensive code review sessions.

<pre_flight_check>
  EXECUTE: @.agent-os/instructions/meta/pre-flight.md
</pre_flight_check>

<process_flow>

<step number="1" subagent="coding-mentor" name="code_analysis_and_understanding">

### Step 1: Code Analysis and Understanding

Use the coding-mentor subagent to thoroughly analyze submitted code and understand its purpose, structure, and implementation.

<analysis_framework>
  **Code Comprehension**
  - Understand the problem being solved
  - Identify the approach and algorithms used
  - Analyze code structure and organization
  - Review functionality and behavior

  **Context Assessment**
  - Determine skill level of the author
  - Understand project requirements and constraints
  - Identify learning objectives
  - Assess code maturity and purpose
</analysis_framework>

</step>

<step number="2" subagent="coding-mentor" name="comprehensive_quality_assessment">

### Step 2: Comprehensive Quality Assessment

Use the coding-mentor subagent to evaluate code against professional standards and best practices.

<quality_dimensions>
  **Functionality**
  - Correctness and bug identification
  - Edge case handling
  - Error management and recovery
  - Performance characteristics

  **Readability**
  - Naming conventions
  - Code organization and structure
  - Comments and documentation
  - Consistent formatting

  **Maintainability**
  - Code modularity and separation
  - DRY principle adherence
  - SOLID principles application
  - Technical debt assessment

  **Security**
  - Input validation
  - Authentication and authorization
  - Data protection
  - Vulnerability assessment
</quality_dimensions>

</step>

<step number="3" subagent="coding-mentor" name="constructive_feedback_delivery">

### Step 3: Constructive Feedback Delivery

Use the coding-mentor subagent to provide balanced, constructive feedback that promotes learning and improvement.

<feedback_structure>
  **Positive Recognition**
  - Identify and highlight strengths
  - Acknowledge good practices and patterns
  - Recognize creative problem-solving
  - Celebrate progress and improvement

  **Critical Issues**
  - Identify bugs and functional problems
  - Highlight security vulnerabilities
  - Point out performance bottlenecks
  - Note maintenance challenges

  **Improvement Opportunities**
  - Suggest better algorithms or approaches
  - Recommend refactoring opportunities
  - Propose architectural improvements
  - Share industry best practices

  **Learning Points**
  - Connect to programming concepts
  - Explain the "why" behind suggestions
  - Provide educational context
  - Reference learning resources
</feedback_structure>

</step>

<step number="4" subagent="file-creator" name="create_detailed_review_report">

### Step 4: Create Detailed Review Report

Use the file-creator subagent to generate comprehensive review documentation with specific examples and recommendations.

<review_report_structure>
  .agent-os/training/code-reviews/[DATE]-[PROJECT]/
  ├── review-summary.md        # Executive summary
  ├── detailed-feedback.md     # Line-by-line analysis
  ├── refactored-examples/     # Improved code examples
  ├── learning-resources.md    # Additional study materials
  └── action-items.md         # Specific improvement tasks
</review_report_structure>

</step>

<step number="5" subagent="coding-mentor" name="interactive_improvement_session">

### Step 5: Interactive Improvement Session

Use the coding-mentor subagent to conduct collaborative refactoring and improvement exercises.

<improvement_methodology>
  **Collaborative Refactoring**
  - Work through improvements together
  - Explain reasoning for each change
  - Demonstrate alternative approaches
  - Show before/after comparisons

  **Teaching Moments**
  - Deep dive into specific concepts
  - Explain design pattern applications
  - Demonstrate testing strategies
  - Share professional experiences
</improvement_methodology>

</step>

</process_flow>

<post_flight_check>
  EXECUTE: @.agent-os/instructions/meta/post-flight.md
</post_flight_check>