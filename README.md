<p align="center">
  <img src="./img.png" alt="Project Banner" width="100%">
</p>

# project name:JanVaani(The Voice of People)🎯

## Basic Details

### Team Name: Code duo

### Team Members
- Member 1: Fathima S - LBSITW
- Member 2: Jeniffer Jerald J N - LBSITW

### Hosted Project Link
[mention your project hosted link here]

### Project Description
unified citizens grievance tracking platform.

### The Problem statement
Citizens Complaints are currently scattered across multiple departments like the Municipal Corporation, Kerala Water Authority, and KSEB, resulting in delays.
There is no centralized tracking system, making it difficult for citizens to know the status of their complaints.
Lack of accountability and SLA enforcement causes prolonged resolution times.
Citizens face poor transparency, repeated follow-ups, and frustration.
This fragmentation leads to inefficient governance, unresolved civic issues, and low public trust.
### The Solution
JanVaani, An AI-powered unified grievance platform that allows citizens to register and track complaints across departments such as Municipal Corporation of Thiruvananthapuram, Kerala Water Authority, and Kerala State Electricity Board, from a single digital interface, with strict SLA enforcement.

## Technical Details
Frontend
Framework: React.js
Routing: react-router-dom for multi-page navigation
UI: HTML, CSS, simple responsive design, optional Tailwind/Material UI
Features:
Aadhaar-based login
Complaint registration (text + voice + photo/video)
Real-time complaint tracking
AI / Smart Routing
NLP Classifier to detect complaint category and department:
Example: “No water supply” → Kerala Water Authority
Example: “Streetlight not working” → Municipal Corporation
Priority Levels set automatically based on urgency.
Dashboard & Analytics
Citizen Dashboard: View complaint status, assigned officer, estimated resolution
Department Dashboard: View pending complaints, SLA adherence, performance stats
Public Transparency: Heatmaps, complaint statistics, average resolution times
Optional Features
GPS-based location tagging of complaints

### Technologies/Components Used

**For Software:**
- Languages used:  JavaScript,HTML
- Frameworks used: React.js
- Libraries used: firebase
- Tools used:  VS Code, Git, node.js

## Features
List the key features of your project:
- Feature 1: single complaint portal(one app/web portal for all civic complaints)
- Feature 2: AI-Based Auto Routing(AI automatically classifies complaints and forwards them to the correct department)
- Feature 3: SLA Enforcement Engine(Time-bound resolution with automated reminders,escalation,and penalties for delays.)
- Feature 4: Real-Time Tracking(Citizens can track complaint status (Registered-> In progress->Resolved).
- Feature 5: Smart Analytics Dashboard(Government officials view trends,department performance,and bottlenecks)
- Feature 6:Citizen Feedback and rating.

## Implementation
JanVaani is a React.js web app with Firebase backend.
Citizens login via Aadhaar and submit complaints with text, voice, photo/video, and GPS location.
AI/keyword-based routing assigns complaints to the correct department automatically.
SLA timers enforce resolution deadlines with automatic escalation if delayed.
Dashboards provide real-time tracking, analytics, and heatmaps for citizens and department heads.
Tech Stack: React.js, Firebase (Auth, Firestore, Storage), Browser APIs, optional Tailwind/Material UI.

### For Software:

#### Installation
```bash
[# Install Node.js and npm
node -v
npm -v

# Install Git (optional for version control)
git --version

# Create and setup React app
npx create-react-app janvaani
cd janvaani

# Install required packages
npm install firebase react-router-dom]
```

#### Run
[npm start]


## Project Documentation-JanVaani

### For Software:

#### Screenshots (Add at least 3)
![WhatsApp Image 2026-02-14 at 6 09 30 AM (1)](https://github.com/user-attachments/assets/72b4a16c-1a40-4e83-92e9-d46c9c4b3b65)
*Add caption explaining what this shows*![WhatsApp Image 2026-02-14 at 7 44 02 AM](https://github.com/user-attachments/assets/6d2635f3-b1c4-48f5-9096-6055200aa9d9)



![Screenshot2](Add screenshot 2 here with proper name)
*Add caption explaining what this shows*

![Screenshot3](Add screenshot 3 here with proper name)
*Add caption explaining what this shows*

#### Diagrams

**System Architecture:**

Architecture Diagram--![WhatsApp Image 2026-02-14 at 7 44 02 AM](https://github.com/user-attachments/assets/6d2635f3-b1c4-48f5-9096-6055200aa9d9)




**Application Workflow:**

![Workflow](docs/workflow.png)
*Add caption explaining your workflow*


## Additional Documentation

### For Web Projects with Backend:

#### API Documentation

**Base URL:** `https://api.yourproject.com`

##### Endpoints

**GET /api/endpoint**
- **Description:** [What it does]
- **Parameters:**
  - `param1` (string): [Description]
  - `param2` (integer): [Description]
- **Response:**
```json
{
  "status": "success",
  "data": {}
}
```

**POST /api/endpoint**
- **Description:** [What it does]
- **Request Body:**
```json
{
  "field1": "value1",
  "field2": "value2"
}
```
- **Response:**
```json
{
  "status": "success",
  "message": "Operation completed"
}
```

[Add more endpoints as needed...]

---

### For Mobile Apps:

#### App Flow Diagram

![App Flow](docs/app-flow.png)
*Explain the user flow through your application*

#### Installation Guide

**For Android (APK):**
1. Download the APK from [Release Link]
2. Enable "Install from Unknown Sources" in your device settings:
   - Go to Settings > Security
   - Enable "Unknown Sources"
3. Open the downloaded APK file
4. Follow the installation prompts
5. Open the app and enjoy!

**For iOS (IPA) - TestFlight:**
1. Download TestFlight from the App Store
2. Open this TestFlight link: [Your TestFlight Link]
3. Click "Install" or "Accept"
4. Wait for the app to install
5. Open the app from your home screen

**Building from Source:**
```bash
# For Android
flutter build apk
# or
./gradlew assembleDebug

# For iOS
flutter build ios
# or
xcodebuild -workspace App.xcworkspace -scheme App -configuration Debug



### For Scripts/CLI Tools:
-
#### Command Reference

**Basic Usage:**
```bash
python script.py [options] [arguments]
```

**Available Commands:**
- `command1 [args]` - Description of what command1 does
- `command2 [args]` - Description of what command2 does
- `command3 [args]` - Description of what command3 does

**Options:**
- `-h, --help` - Show help message and exit
- `-v, --verbose` - Enable verbose output
- `-o, --output FILE` - Specify output file path
- `-c, --config FILE` - Specify configuration file
- `--version` - Show version information

**Examples:**

```bash
# Example 1: Basic usage
python script.py input.txt

# Example 2: With verbose output
python script.py -v input.txt

# Example 3: Specify output file
python script.py -o output.txt input.txt

# Example 4: Using configuration
python script.py -c config.json --verbose input.txt
```

#### Demo Output

**Example 1: Basic Processing**

**Input:**
```
This is a sample input file
with multiple lines of text
for demonstration purposes
```

**Command:**
```bash
python script.py sample.txt
```

**Output:**
```
Processing: sample.txt
Lines processed: 3
Characters counted: 86
Status: Success
Output saved to: output.txt
```

**Example 2: Advanced Usage**

**Input:**
```json
{
  "name": "test",
  "value": 123
}
```

**Command:**
```bash
python script.py -v --format json data.json
```

**Output:**
```
[VERBOSE] Loading configuration...
[VERBOSE] Parsing JSON input...
[VERBOSE] Processing data...
{
  "status": "success",
  "processed": true,
  "result": {
    "name": "test",
    "value": 123,
    "timestamp": "2024-02-07T10:30:00"
  }
}
[VERBOSE] Operation completed in 0.23s
```

---

## Project Demo

### Video

https://github.com/user-attachments/assets/279589ee-71cf-4434-a334-125d37359fc8

Brief Description:

Citizens can submit complaints through a simple form.

The system uses AI to analyze and classify the complaint automatically.

Complaints are routed to the correct department based on content.

It includes SLA (Service Level Agreement) monitoring to ensure timely resolution.

Users can track the status of their complaint in real time.

Administrators can view complaints through a dashboard interface.

## AI Tools Used (Optional - For Transparency Bonus)

If you used AI tools during development, document them here for transparency:

**Tool Used:** ChatGPT

**Purpose:** 
- Example: "Debugging assistance for async functions"
- Example: "Code review and optimization suggestions"

**Key Prompts Used:**
- "Create a REST API endpoint for user authentication"
- "Debug this async function that's causing race conditions"
- "Optimize this database query for better performance"

**Percentage of AI-generated code:* 60%

**Human Contributions:**
- Architecture design and planning
- Custom business logic implementation
- Integration and testing
- UI/UX design decisions

## Team Contributions

- Jeniffer Jerald JN:  Frontend development, API integration.
- Fathima S:  Backend development, Database design.
- Jeniffer and Fathima :  UI/UX design, Testing, Documentation, etc.


Made with ❤️ at TinkerHub
