# CI-CD Jenkins Project

## Project Overview
This project demonstrates **Continuous Integration (CI) and Delivery (CD)** using Jenkins.  
Automated tests are executed for a web application and API whenever code is committed to GitHub.

---

## Project Structure
CI-CD-Jenkins-Project/
├─ Jenkinsfile ← Jenkins pipeline configuration
├─ .gitignore
├─ README.md ← Project instructions
└─ Jenkins_AI/ ← Maven project
├─ pom.xml
├─ src/
│ ├─ main/java/... ← Application code
│ └─ test/java/LoginTest.java ← Selenium WebDriver test
└─ ... (other Maven files)


---

## Tools & Technologies

- **Jenkins** – CI/CD automation
- **Java 25** – Programming language
- **Maven 3.9.9** – Build automation
- **Selenium WebDriver** – Web automation testing
- **TestNG** – Test execution & reporting
- **Postman** – API testing
- **Git & GitHub** – Version control

---

## How to Run

### 1. Clone the Repository
```bash
git clone https://github.com/Nidhi-J-Shah/CI-CD-Jenkins-Project.git

2. Set Up Project
- Open the project in IntelliJ IDEA.
- Make sure ChromeDriver path is correctly set in LoginTest.java.
- Maven will automatically download dependencies from pom.xml.

3. Run Tests Locally (Optional)
- mvn clean test

4. Jenkins Pipeline
- Configure a new Pipeline Job in Jenkins.
- Connect it to the GitHub repository.
- Use the Jenkinsfile in the root of the repository.
- Pipeline automatically builds project and runs tests on each commit.

Test Scenarios
Selenium Login Test:
- Valid login
- Invalid login
- Empty fields

Postman API Test:
- User authentication endpoint testing (e.g., https://reqres.in/api/login)

Results
- Jenkins pipeline builds successfully.
- TestNG reports available in Jenkins.
- Pipeline executes automatically on every Git commit.

Notes
- Ensure Maven and Java paths are set correctly on your machine.
- ChromeDriver must match the installed Chrome version.
- Remove target/ and .idea/ folders from Git repository before submission.


---

💡 **Tip:**  
- Tame README.md ma screenshots add kari shako jethi build success/failure clear thai jai.  
- Commit & push pachhi tamaro repo fully submission-ready thai jai.  

---

Jo tame chaho to hu **IntelliJ ma step-by-step README.md banavva ni full command sequence** pan aapi dau.  

Chho hu aapuu?
