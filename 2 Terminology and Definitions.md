# 2. Terminology and Definitions

Created by: Shane Evans
Created time: September 18, 2024 3:23 PM

---

**2. Terminology and Definitions**

To ensure clarity and a shared understanding of the concepts, processes, and techniques involved in automated testing for video games, this section provides precise definitions for key terms. These definitions form the foundation for interpreting and implementing the standard, helping industry professionals navigate and adopt the guidelines effectively.

---

**2.1 Automated Testing**

**Definition:**

The process of using software tools and scripts to execute test cases on a game without human intervention, to validate its functionality, performance, and compatibility across different platforms and environments.

**Explanation:**

Automated testing in video games allows for the execution of repetitive and complex test scenarios, reducing the need for manual testing while enhancing the speed, consistency, and coverage of tests. It includes a range of testing types, from unit and integration testing to system-level testing such as performance and compatibility tests.

---

**2.2 Test Case**

**Definition:**

A set of conditions or variables under which a tester will determine whether a game feature or function is working as expected.

**Explanation:**

In automated testing, test cases are scripts or instructions that describe specific actions to be performed by the test automation tool. Each test case is designed to verify particular game elements, such as in-game mechanics, physics, or graphical rendering, ensuring they function as intended.

---

**2.3 Test Framework**

**Definition:**

A structured set of guidelines and tools designed to create and execute automated test cases, facilitating the systematic testing of a video game’s components.

**Explanation:**

A test framework provides a consistent and reusable architecture for creating, running, and managing tests. It typically includes tools for writing test scripts, executing them, and reporting results. Examples include data-driven frameworks (where test data is separated from scripts) and behavior-driven frameworks (which emphasize user-centric behavior testing).

---

**2.4 Unit Testing**

**Definition:**

A type of testing where individual components or pieces of a game’s code are tested in isolation to ensure they function correctly.

**Explanation:**

Unit tests are typically automated and target specific game modules (e.g., character movement, sound effects). The aim is to detect bugs at an early stage of development by isolating and verifying that each component works independently.

---

**2.5 Integration Testing**

**Definition:**

A testing method that ensures different modules or components of a game work together as expected when integrated.

**Explanation:**

Integration tests focus on the interaction between different elements of the game (e.g., the interaction between the game engine and the user interface). Automated integration testing verifies that these combined components perform seamlessly, minimizing issues in later stages of development.

---

**2.6 Performance Testing**

**Definition:**

A process of evaluating the responsiveness, stability, and scalability of a game under specific conditions or workloads.

**Explanation:**

Automated performance testing assesses how the game performs under various conditions, such as during peak user load or intense graphical processing. It helps identify potential performance bottlenecks, such as lag, dropped frames, or excessive CPU and memory usage.

---

**2.7 Regression Testing**

**Definition:**

A type of testing that ensures that changes or updates in the game (e.g., patches or new features) do not introduce new defects or reintroduce previously resolved bugs.

**Explanation:**

Automated regression testing is essential in agile game development, where frequent updates occur. By automatically re-running previously passed tests after every change, developers can ensure new code does not compromise the game’s functionality.

---

**2.8 Compatibility Testing**

**Definition:**

The process of verifying that a game works consistently across various platforms, devices, operating systems, and hardware configurations.

**Explanation:**

Automated compatibility testing helps ensure that games run smoothly on different consoles, PCs, and mobile devices, as well as across different versions of operating systems and hardware (e.g., graphics cards). This testing type ensures that no platform-specific issues arise post-release.

---

**2.9 User Interface (UI) Testing**

**Definition:**

Testing the game’s graphical user interface (GUI) to ensure that menus, buttons, and other UI elements behave as expected.

**Explanation:**

Automated UI testing checks the visual and interactive elements of a game to confirm they are functional and responsive across all screens and input methods (e.g., controllers, keyboards, touchscreens).

---

**2.10 Test Script**

**Definition:**

A sequence of automated instructions or code designed to perform specific test actions and validate a game’s behavior.

**Explanation:**

Test scripts are the backbone of automated testing. They can be written in various programming or scripting languages, depending on the test framework in use. The scripts execute test cases, simulate player actions, and validate game states or outputs.

---

**2.11 Test Coverage**

**Definition:**

A metric that indicates the proportion of the game’s features, code, or functionality that has been tested, either manually or through automation.

**Explanation:**

Test coverage is a critical indicator of how thoroughly a game has been tested. High test coverage implies that most, if not all, major functions and game mechanics have been verified through tests, reducing the risk of undetected bugs or performance issues.

---

**2.12 Continuous Integration (CI)**

**Definition:**

A development practice where code changes are automatically tested and integrated into the game’s build system frequently (often several times a day).

**Explanation:**

CI systems automatically trigger test suites whenever new code is committed to the version control system. Automated tests ensure that the game remains stable as developers continually push updates. This reduces the likelihood of "game-breaking" bugs reaching later stages of development.

---

**2.13 Build Verification Test (BVT) / Smoke Test**

**Definition:**

A type of automated test designed to verify the stability of a game’s build by checking that the most critical functions work.

**Explanation:**

BVTs or smoke tests are often the first set of tests run after a new game build is generated. They quickly identify severe issues that would prevent further testing or development, ensuring that the build is stable enough for deeper testing.

---

**2.14 Defect**

**Definition:**

A bug or error in the game that causes it to behave unexpectedly or incorrectly. This can occur from 

**Explanation:**

Automated testing seeks to detect defects during the development cycle. These may include issues like gameplay mechanics not functioning as intended, graphical glitches, performance drops, or crashes.

---

**2.15 Test Automation Framework Maintenance**

**Definition:**

The process of updating and refining an automation framework to accommodate new tests, changes in game mechanics, or modifications to the game’s engine or features.

**Explanation:**

As the game evolves, so too must the test automation framework. Maintenance ensures that automated tests remain relevant and continue to deliver accurate results throughout the development lifecycle.

---

By defining these key terms, this standard provides a common language for all stakeholders in game development, ensuring consistency and precision in the implementation of automated testing procedures.