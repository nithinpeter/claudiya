# Product Requirement Prompt (PRP) Generator

You are an expert technical product manager and software architect. Your task is to analyze the provided specification document and generate a comprehensive Product Requirement Prompt (PRP) that Claude can use to implement the specified feature effectively.

`spec_doc`: $ARGUMENTS

## Your Role
Transform the given spec document into a detailed, actionable prompt that provides Claude with maximum context and clear implementation guidance, then save it as a markdown file.

## Input Analysis
First, carefully analyze the provided specification document to understand:
- **Core Feature Requirements**: What exactly needs to be built
- **Technical Constraints**: Any limitations or requirements mentioned
- **User Experience Goals**: How users should interact with the feature
- **Integration Points**: How this connects to existing systems
- **Success Criteria**: What defines a successful implementation

## PRP Structure
Generate a PRP following this comprehensive structure:

### 1. CONTEXT & BACKGROUND
```
**Project Context:**
- Brief description of the overall system/application
- Where this feature fits in the bigger picture
- Key stakeholders and their needs

**Technical Environment:**
- Current tech stack and architecture
- Existing patterns and conventions to follow
- Dependencies and integrations
```

### 2. FEATURE SPECIFICATION
```
**Core Requirements:**
- Primary functionality that must be implemented
- User stories and acceptance criteria
- Business logic and rules

**Technical Requirements:**
- Performance expectations
- Security considerations
- Scalability needs
- Compatibility requirements
```

### 3. IMPLEMENTATION GUIDANCE
```
**Code Analysis Instructions:**
"Before implementing, you must:
1. Examine the existing codebase thoroughly
2. Identify and document current patterns for [relevant areas]
3. Look for similar implementations to use as reference
4. Understand the current architecture and data flow
5. Review existing error handling and validation patterns"

**Pattern Adherence:**
"Follow these specific patterns from the existing codebase:
- [Specific pattern 1 based on spec]
- [Specific pattern 2 based on spec]
- [Naming conventions]
- [File structure conventions]
- [API design patterns]"

**Context Requirements:**
"Provide extensive context by:
- Showing relevant existing code snippets
- Explaining how your implementation fits with current architecture
- Demonstrating consistency with existing patterns
- Providing before/after comparisons where applicable"
```

### 4. DETAILED IMPLEMENTATION STEPS
```
**Step-by-Step Process:**
1. **Discovery Phase:**
   - Analyze [specific files/components] to understand current implementation
   - Document existing patterns for [relevant functionality]
   - Identify integration points with [specific systems]

2. **Planning Phase:**
   - Design the implementation following existing patterns
   - Plan data flow and state management
   - Consider edge cases and error scenarios

3. **Implementation Phase:**
   - [Specific implementation steps based on spec]
   - [Testing requirements]
   - [Documentation needs]

4. **Integration Phase:**
   - [Integration steps]
   - [Validation requirements]
   - [Deployment considerations]
```

### 5. QUALITY STANDARDS
```
**Code Quality Requirements:**
- Follow existing code style and formatting
- Maintain consistency with current error handling
- Include comprehensive comments and documentation
- Implement proper testing coverage
- Handle edge cases and error scenarios

**Review Criteria:**
- Code integrates seamlessly with existing codebase
- Follows established patterns and conventions
- Includes proper error handling and validation
- Provides clear documentation and comments
- Meets performance and security requirements
```

### 6. DELIVERABLES
```
**Required Outputs:**
- Complete implementation with full context
- Explanation of design decisions
- Documentation of any new patterns introduced
- Testing approach and coverage
- Integration and deployment notes
```

## PRP Generation Instructions

Based on the provided spec document, generate a PRP that:

1. **Extracts Key Information**: Pull out all relevant details from the spec
2. **Provides Maximum Context**: Include extensive background and technical context
3. **Emphasizes Pattern Following**: Strongly emphasize following existing patterns
4. **Includes Specific Examples**: Where possible, reference specific parts of the codebase
5. **Covers Edge Cases**: Address potential issues and error scenarios
6. **Ensures Integration**: Focus on how the feature integrates with existing systems

## Output Format
Present the PRP as a complete, ready-to-use prompt that can be directly given to Claude for implementation, including:
- Clear, actionable instructions
- Specific context requirements
- Step-by-step implementation guidance
- Quality standards and expectations
- Deliverable requirements

## File Output Instructions

After generating the PRP, save it to a markdown file with the following specifications:
- **Filename**: `{feature_name}.md`
- **Location**: `prps/` folder
- **Format**: Markdown (.md)
- **Content**: The complete PRP ready for use with Claude

## Usage Instructions

To use this PRP generator:

```
Generate a PRP for the following:
- Feature Name: [feature-name]
- Spec Document: [paste or reference your spec document]
```

The generator will:
1. Analyze your spec document
2. Generate a comprehensive PRP following the framework above
3. Save the output to `prps/[feature-name].md`
4. Provide a ready-to-use prompt for Claude implementation

---

**Please provide the feature name and specification document to generate the PRP.**
