<p align="center">
  <img src="./img.png" alt="Project Banner" width="100%">
</p>

# project name:JanVaani(The Voice of People)🎯

## Basic Details

### Team Name: Code duo

### Team Members
- Member 1: [Fathima S] - [LBSITW]
- Member 2: [Jeniffer Jerald J N] - [LBSITW]

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


---

## Features

List the key features of your project:
- Feature 1: single complaint portal(one app/web portal for all civic complaints)
- Feature 2: AI-Based Auto Routing(AI automatically classifies complaints and forwards them to the correct department)
- Feature 3: SLA Enforcement Engine(Time-bound resolution with automated reminders,escalation,and penalties for delays.)
- Feature 4: Real-Time Tracking(Citizens can track complaint status (Registered-> In progress->Resolved).
- Feature 5: Smart Analytics Dashboard(Government officials view trends,department performance,and bottlenecks)
- Feature 6:Citizen Feedback and rating.

---

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
```

### For Hardware:

#### Components Required
[List all components needed with specifications]

#### Circuit Setup
[Explain how to set up the circuit]

---

## Project Documentation-JanVaani

### For Software:

#### Screenshots (Add at least 3)

![Screenshot1] ![WhatsApp Image 2026-02-14 at 6 09 30 AM](https://github.com/user-attachments/assets/0663c7db-1366-4030-bfeb-a529ffa548a0)

*Add caption explaining what this shows*


![Screenshot2](Add screenshot 2 here with proper name)
*Add caption explaining what this shows*

![Screenshot3](Add screenshot 3 here with proper name)
*Add caption explaining what this shows*

#### Diagrams

**System Architecture:**

![Architecture Diagram](docs/architecture.png)
*Explain your system architecture - components, data flow, tech stack interaction*

**Application Workflow:**

![Workflow](docs/workflow.png)
*Add caption explaining your workflow*

---

### For Hardware:

#### Schematic & Circuit

![Circuit](Add your circuit diagram here)
*Add caption explaining connections*

![Schematic](Add your schematic diagram here)
*Add caption explaining the schematic*

#### Build Photos

![Team](Add photo of your team here)

![Components](Add photo of your components here)
*List out all components shown*

![Build](Add photos of build process here)
*Explain the build steps*

![Final](Add photo of final product here)
*Explain the final build*

---

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
```

---

### For Hardware Projects:

#### Bill of Materials (BOM)

| Component | Quantity | Specifications | Price | Link/Source |
|-----------|----------|----------------|-------|-------------|
| Arduino Uno | 1 | ATmega328P, 16MHz | ₹450 | [Link] |
| LED | 5 | Red, 5mm, 20mA | ₹5 each | [Link] |
| Resistor | 5 | 220Ω, 1/4W | ₹1 each | [Link] |
| Breadboard | 1 | 830 points | ₹100 | [Link] |
| Jumper Wires | 20 | Male-to-Male | ₹50 | [Link] |
| [Add more...] | | | | |

**Total Estimated Cost:** ₹[Amount]

#### Assembly Instructions

**Step 1: Prepare Components**
1. Gather all components listed in the BOM
2. Check component specifications
3. Prepare your workspace
![Step 1](images/assembly-step1.jpg)
*Caption: All components laid out*

**Step 2: Build the Power Supply**
1. Connect the power rails on the breadboard
2. Connect Arduino 5V to breadboard positive rail
3. Connect Arduino GND to breadboard negative rail
![Step 2](images/assembly-step2.jpg)
*Caption: Power connections completed*

**Step 3: Add Components**
1. Place LEDs on breadboard
2. Connect resistors in series with LEDs
3. Connect LED cathodes to GND
4. Connect LED anodes to Arduino digital pins (2-6)
![Step 3](images/assembly-step3.jpg)
*Caption: LED circuit assembled*

**Step 4: [Continue for all steps...]**

**Final Assembly:**
![Final Build](images/final-build.jpg)
*Caption: Completed project ready for testing*

---

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
[Add your demo video link here - 
*Explain what the video demonstrates - key features, user flow, technical highlights*

---

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


---

## Team Contributions

- [Jeniffer Jerald JN]:  Frontend development, API integration.
- [Fathima S]:  Backend development, Database design.
- [Jenifer and Fathima ]:  UI/UX design, Testing, Documentation, etc.]


Made with ❤️ at TinkerHub
