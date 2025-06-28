# Instruction Library

## Instruction Categories

### System Instructions (SYS-*)
**SYS-001: System Health Check**
- **Purpose**: Verify system integrity and memory files
- **Input**: None
- **Output**: System status report
- **Success Criteria**: All memory files accessible and valid

**SYS-002: Persona Switch**
- **Purpose**: Change active persona for different tasks
- **Input**: Target persona name
- **Output**: Updated current_state.md with new persona
- **Success Criteria**: Persona successfully switched and logged

### Project Instructions (PROJ-*)
**PROJ-001: Project Initialization**
- **Purpose**: Create new project structure
- **Input**: Project name, type, requirements
- **Output**: Project directory with basic structure
- **Success Criteria**: Project directory created with essential files

**PROJ-002: Requirements Analysis**
- **Purpose**: Analyze and document project requirements
- **Input**: User requirements description
- **Output**: Structured requirements document
- **Success Criteria**: Clear, actionable requirements defined

**PROJ-003: Architecture Design**
- **Purpose**: Design project architecture
- **Input**: Requirements, project type
- **Output**: Architecture diagram and technical decisions
- **Success Criteria**: Clear architecture defined and documented

### Development Instructions (DEV-*)
**DEV-001: Component Creation**
- **Purpose**: Create individual code components
- **Input**: Component specification
- **Output**: Working code component
- **Success Criteria**: Component functions as specified

**DEV-002: Feature Implementation**
- **Purpose**: Implement complete features
- **Input**: Feature requirements
- **Output**: Working feature with tests
- **Success Criteria**: Feature works and passes tests

### Testing Instructions (TEST-*)
**TEST-001: Unit Test Creation**
- **Purpose**: Create unit tests for components
- **Input**: Component to test
- **Output**: Unit test suite
- **Success Criteria**: Tests pass and cover key functionality

### Deployment Instructions (DEPLOY-*)
**DEPLOY-001: Environment Setup**
- **Purpose**: Set up deployment environment
- **Input**: Deployment requirements
- **Output**: Configured deployment environment
- **Success Criteria**: Environment ready for deployment

## Instruction Template
```
**INSTRUCTION-ID: Instruction Name**
- **Purpose**: What this instruction accomplishes
- **Input**: What information/parameters needed
- **Output**: What is produced
- **Success Criteria**: How to know it's complete
- **Persona**: Which persona should execute this
``` 