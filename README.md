<p align="center">
  <img src="./img.png" alt="Project Banner" width="100%">
</p>

# HABITQUEST 🎯

## HabitQuest is a gamified self-growth web platform that transforms habit building into an interactive journey. It integrates habit tracking, learning goals, health tracking, and team collaboration within a single ecosystem.
The platform uses:
🔥 Streak-based rewards
🏆 XP progression system
🧬 Character evolution mechanism
🤝 Team accountability
By converting daily habits into a game-like experience, HabitQuest promotes sustained behavioural transformation rather than simple task completion

### Team Name: LOGIC LORDS

### Team Members
- Member 1: Nandana G - NSS College of Engineering Palakkad
- Member 2: Krishna J - NSS College of Engineering Palakkad

### Hosted Project Link
[mention your project hosted link here]

### Project Description
HabitQuest is a gamified web platform designed to make habit building engaging and sustainable.
Users earn XP, maintain streaks, and evolve their digital character as they consistently complete habits.
By combining health, learning, task management, and team collaboration, it transforms productivity into an interactive growth journey.

### The Problem statement
Most existing habit and productivity applications focus on tracking tasks rather than enabling long-term behavioural transformation. Users often lose motivation due to lack of engagement, emotional reinforcement, and accountability mechanisms. There is a need for a unified, gamified platform that promotes consistency and sustained self-growth through rewards, visual progress, and collaboration.

### The Solution
HabitQuest solves this problem by transforming habit tracking into a gamified experience. It introduces a streak-based reward system, XP progression, and character evolution to emotionally engage users and encourage consistency. By integrating habit tracking, health goals, learning tasks, and team collaboration in one platform, it builds accountability and promotes long-term behavioural change rather than simple task logging

---

## Technical Details

### Technologies/Components Used

**For Software:**
- Languages used: HTML5, CSS, JavaScript
- Frameworks used: Vannilla javascript and firebase as backend
- Libraries used: Firebase javascript SDK
- Tools used: VS Code , GIT ,GitHub

---

## Features

List the key features of your project:
- Feature 1:  Gamified Habit Tracking
Users complete daily habits to earn XP and track their consistency in an engaging way.
feature 2: Streak Maintenance System
Maintains daily streaks and rewards users for continuous habit completion to encourage discipline.
feature 3 : XP & Level Progression
Users gain experience points and level up, visually representing their personal growth.
feature 4:  Team Collaboration Mode
Allows users to join teams, track collective progress, and build accountability through shared goals.


---

## Implementation

### For Software:

#### Installation
git clone https://github.com/your-username/habitquest.git
cd habitquest
firebase login





#### Run
index.html
live server in VS code 

## Project Documentation

### For Software:

#### Screenshots (Add at least 3)

![Screenshot1](Add screenshot 1 here with proper name)
*Add caption explaining what this shows*

![Screenshot2](Add screenshot 2 here with proper name)
*Add caption explaining what this shows*

![Screenshot3](Add screenshot 3 here with proper name)
*Add caption explaining what this shows*

#### Diagrams

**System Architecture:**

![Architecture Diagram](docs/architecture.png)


**Application Workflow:**

![Workflow](docs/workflow.png)
*Add caption explaining your workflow*

---

## Additional Documentation

### For Web Projects with Backend:

#### API Documentation

**Base URL:** HabitQuest does not use a custom REST API with a base URL.
Instead, it integrates directly with Firebase services through the Firebase JavaScript SDK.
However, the Firebase service endpoints internally use :https://firestore.googleapis.com/v1/
https://identitytoolkit.googleapis.com/v1/


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
[Add your demo video link here - YouTube, Google Drive, etc.]

*Explain what the video demonstrates - key features, user flow, technical highlights*

### Additional Demos
[Add any extra demo materials/links - Live site, APK download, online demo, etc.]

---

## AI Tools Used (Optional - For Transparency Bonus)

If you used AI tools during development, document them here for transparency:

**Tool Used:** AI Tools Used (Transparency Declaration)
🔹 ChatGPT
🔹 Claude


**Purpose:** [What you used it for]
- Example: "speed up boilerplate code generation"
- Example: "Debugging assistance"
-
  - Example: "Code review and optimization suggestions and firebase assistance

**Key Prompts Used:**
Generate a Firebase authentication integration structure using HTML, CSS, and JavaScript.
Help debug Firebase login and Firestore data retrieval issues.
Design a streak-based XP reward logic for a gamified habit tracker.
Generate structured GitHub README sections including features and installation steps.

**Percentage of AI-generated code:**  %

**Human Contributions:**
- Conceptualized the idea and overall theme.
-Designed system logic and workflow.
-Structured the architecture and database.
-Integrated AI-generated code with custom logic.
-Created and customised the user interface.
-Tested functionality and finalised the working product.

*Note: Proper documentation of AI usage demonstrates transparency and earns bonus points in evaluation!*

---

## Team Contributions

 NANDANA G: Conceptualized idea , designed logic ,customized frontend , tested final product, developed prompts
 KRISHNA J : structured architecture, planned streak mechanism , implemented firebase mechanism , tested final product, developed prompts


---

## License

This project is licensed under the [LICENSE_NAME] License - see the [LICENSE](LICENSE) file for details.

**Common License Options:**
- MIT License (Permissive, widely used)
- Apache 2.0 (Permissive with patent grant)
- GPL v3 (Copyleft, requires derivative works to be open source)

---

Made with ❤️ at TinkerHub
