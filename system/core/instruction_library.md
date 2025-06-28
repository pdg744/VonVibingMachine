# Instruction Library

## System Management Instructions

### UPDATE SYSTEM STATE
**Purpose**: Modify current_state, execution_log, instruction_queue
**Persona**: System Manager
**Template**: 
- Update current_state.md with new context
- Add entry to execution_log.md
- Modify instruction_queue.md as needed
**Success Criteria**: All system memory files updated accurately

### SWITCH PERSONA
**Purpose**: Change to appropriate persona for current task
**Persona**: System Manager
**Template**:
- Identify required persona for next task
- Update current_state.md with new persona
- Ensure persona skills match task requirements
**Success Criteria**: Correct persona active and ready for task

### PLAN INSTRUCTION QUEUE
**Purpose**: Determine next system actions
**Persona**: System Manager
**Template**:
- Review current state and project status
- Identify next priority actions
- Update instruction_queue.md with plan
**Success Criteria**: Clear next steps defined in queue

### MANAGE PROJECT CONTEXT
**Purpose**: Update project-specific context files
**Persona**: System Manager
**Template**:
- Update project's context.md file
- Track progress and milestones
- Maintain project status accuracy
**Success Criteria**: Project context reflects current reality

## Project Building Instructions

### ANALYZE REQUIREMENTS
**Purpose**: Understand what we're building and break it down
**Persona**: Project Coordinator
**Template**:
- Review user requirements and goals
- Break down into manageable features
- Identify technical requirements and constraints
- Create initial project plan
**Success Criteria**: Clear understanding of what needs to be built

### PROTOTYPE FEATURE
**Purpose**: Build working code quickly
**Persona**: Rapid Prototyper
**Template**:
- Implement minimal viable feature
- Focus on functionality over perfection
- Create working code that demonstrates concept
- Keep implementation simple and clear
**Success Criteria**: Feature works as intended

### TEST FUNCTIONALITY
**Purpose**: Verify it works and identify issues
**Persona**: Quality Validator
**Template**:
- Test feature functionality manually
- Identify bugs and issues
- Validate against user requirements
- Document any problems found
**Success Criteria**: Feature works correctly or issues clearly identified

### ITERATE IMPROVEMENT
**Purpose**: Improve based on feedback and testing
**Persona**: Rapid Prototyper
**Template**:
- Address identified issues
- Incorporate user feedback
- Improve functionality and usability
- Maintain working state
**Success Criteria**: Improvements implemented successfully

### CREATE DOCUMENTATION
**Purpose**: Make it user-friendly and clear
**Persona**: Quality Validator
**Template**:
- Create clear, simple documentation
- Include setup and usage instructions
- Document key features and functionality
- Make it accessible to target users
**Success Criteria**: Documentation is clear and helpful

## Hybrid Operations

### INITIALIZE PROJECT
**Purpose**: Set up project structure + update system context
**Persona**: Project Coordinator
**Template**:
- Create project directory structure
- Initialize project context file
- Set up basic project files
- Update system state with new project
**Success Criteria**: Project structure created and system updated

### UPDATE PROJECT STATUS
**Purpose**: Track progress + update system memory
**Persona**: Project Coordinator
**Template**:
- Update project progress in context.md
- Record completed milestones
- Update system execution log
- Plan next project steps
**Success Criteria**: Both project and system status current

### HANDLE USER INPUT
**Purpose**: Process user feedback + update system state
**Persona**: Project Coordinator
**Template**:
- Process user requirements or feedback
- Update project context accordingly
- Modify instruction queue based on input
- Update system state with new information
**Success Criteria**: User input processed and system updated

## Instruction Execution Guidelines
- Always update system state after instruction completion
- Choose appropriate persona for each instruction
- Track instruction success/failure for optimization
- Maintain focus on user project success 