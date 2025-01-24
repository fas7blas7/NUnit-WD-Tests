# ExerciseWaits Solution

This repository contains a Visual Studio solution named **ExerciseWaits**, which includes multiple projects demonstrating various Selenium WebDriver wait strategies and interactions with web elements.

## Projects in the Solution

1. **SearchWithImlicitWait**
   - Demonstrates the use of **Implicit Waits** to handle dynamic web elements.
   
2. **SearchWithExplicitWait**
   - Utilizes **Explicit Waits** to wait for specific conditions before interacting with elements.
   
3. **WorkingWithWindows**
   - Covers handling multiple browser windows and tabs in Selenium.
   
4. **WorkingWithAlerts**
   - Demonstrates how to handle JavaScript alerts, confirmations, and prompts.
   
5. **WorkingWithIFrames**
   - Shows how to interact with elements inside iframes using Selenium.

## Prerequisites

Ensure you have the following installed before running the tests:

- Visual Studio (Version 17 or later)
- .NET SDK
- Chrome browser
- Chrome WebDriver
- NUnit and Selenium WebDriver NuGet packages

## Setup Instructions

1. **Clone the repository:**
   ```sh
   git clone https://github.com/your-username/ExerciseWaits.git
   cd ExerciseWaits
   ```

2. **Open in Visual Studio:**
   - Launch Visual Studio and open the `ExerciseWaits.sln` solution file.

3. **Restore dependencies:**
   ```sh
   dotnet restore
   ```

4. **Ensure `chromedriver.exe` is available** in your system PATH or project directory.

## Running the Tests

To run tests for a specific project:
```sh
   dotnet test --filter FullyQualifiedName~Namespace.TestClass
```

To execute all tests in the solution:
```sh
   dotnet test
```

## Contribution

Contributions are welcome! Feel free to submit pull requests to improve test coverage or optimize existing scripts.

---

This solution provides practical examples of handling web waits, alerts, windows, and iframes using Selenium WebDriver. 🚀

