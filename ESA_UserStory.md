# User Story: ESA Certificate Request Submission

**As a** pet owner  
**I want to** submit my ESA certificate request through the platform  
**So that** I can get connected with a licensed mental health professional for my evaluation

---

## Acceptance Criteria

### Form Navigation
**Given** I am a logged-in pet owner on the platform  
**When** I navigate to "Request ESA Certificate"  
**Then** I should see a multi-step form to submit my request

### Step 1: Personal Information
**Given** I am filling out the ESA request form  
**When** I complete Step 1 (Personal Information)  
**Then** I must provide:
- Full name
- Email address
- Phone number
- State of residence

**And** all fields should validate in real-time  
**And** I cannot proceed without completing required fields

### Step 2: Pet Information
**Given** I am on Step 2 (Pet Information)  
**When** I enter my pet details  
**Then** I must provide:
- Pet name
- Pet type (dog/cat/other)
- Pet breed (optional)
- Upload pet photo (optional, max 5MB, jpg/png)

**And** the form should auto-save my progress

### Step 3: Health Background
**Given** I am on Step 3 (Health Background)  
**When** I answer screening questions  
**Then** I must pro
