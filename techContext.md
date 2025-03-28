# Technical Context

This document contains technical details about the ServiceNow instance and development environment.

## Instance Information

### Primary Instance
- **Instance URL**: [URL of the primary development instance]
- **Instance Type**: [PDI/Sandbox/Dev/Test/Prod]
- **Version**: [ServiceNow version]
- **Patch Level**: [Current patch level]
- **Last Cloned From**: [If applicable, when this instance was last cloned]

### Related Instances
#### PDI
- **URL**: [PDI URL]
- **Purpose**: OOB behavior research and POC development
- **Notes**: [Any specific notes about the PDI]

#### Customer Sandbox
- **URL**: [Sandbox URL]
- **Purpose**: Customer-specific validation and testing
- **Last Cloned From**: [When it was last cloned from production]
- **Notes**: [Important customizations or configurations]

#### Development
- **URL**: [Dev instance URL]
- **Purpose**: Primary development environment
- **Notes**: [Development-specific configurations]

#### Test
- **URL**: [Test instance URL]
- **Purpose**: QA and UAT environment
- **Notes**: [Testing-specific configurations]

#### Production
- **URL**: [Production URL]
- **Purpose**: Live environment
- **Notes**: [Production-specific considerations]

## Development Environment

### Local Setup
- **Operating System**: [OS details]
- **Development Tools**:
  - Cursor IDE
  - [Other relevant tools]
- **Browser**: [Preferred browser for ServiceNow development]

### Version Control
- **Repository URL**: [GitHub repository URL]
- **Branch Strategy**: [Branch naming and management approach]
- **Update Set Strategy**: [How update sets are managed]

## Instance Configuration

### Custom Applications
1. [Application Name]
   - **Scope**: [Scope name]
   - **Purpose**: [Purpose of the application]
   - **Key Tables**: [Important tables]

### Key Customizations
1. [Customization Name]
   - **Type**: [Type of customization]
   - **Purpose**: [Purpose of the customization]
   - **Impact**: [Impact on development]

### Development Standards
- [ ] Update Set Naming Convention
- [ ] Code Review Process
- [ ] Testing Requirements
- [ ] Documentation Requirements

## Environment-Specific Considerations

### PDI Development
- Safe for experimentation
- OOB behavior reference
- No risk of affecting production data

### Sandbox Development
- Contains customer customizations
- Use for validating solutions
- Document any sandbox-specific issues
- Be cautious with modifications

### Development Environment
- Primary coding environment
- Part of SDLC chain
- Use update sets for deployment
- Follow development standards

### Testing Environment
- Validate changes
- Perform QA and UAT
- Document test results

### Production Environment
- Never modify directly
- Deploy via standard change process
- Require proper testing and approval

## Technical Dependencies

### External Systems
1. [System Name]
   - **Purpose**: [Purpose of integration]
   - **Integration Type**: [Type of integration]
   - **Status**: [Integration status]

### Internal Dependencies
1. [Dependency Name]
   - **Purpose**: [Purpose of dependency]
   - **Status**: [Dependency status]

## Notes
[Any additional technical notes or considerations] 