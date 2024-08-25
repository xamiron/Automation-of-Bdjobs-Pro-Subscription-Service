# Project Overview: Automation of Bdjobs Pro Subscription Service
The Bdjobs Pro Automation project, I developed to automate the interaction with the Bdjobs Pro subscription service on the bdjobs.com platform. This project utilized Selenium WebDriver in Java to simulate and automate various user actions, enhancing the efficiency and accuracy of repetitive tasks such as logging in, navigating the subscription process, and interacting with multiple UI elements.
- Check List: https://docs.google.com/spreadsheets/d/1tp0bAegwHls_ncKk86ZnCvp9rs8qqKBX2RR9jQ6QawY/edit?usp=sharing

# Key Features of the Automation Script
# 1. Login Automation:
- The script automates the login process, including handling user authentication by filling in the username and password fields and clicking the necessary buttons.
  
# 2. Bdjobs Pro Navigation:
- After logging in, the script navigates to the Bdjobs Pro section. It handles multiple windows and switches between them to ensure smooth navigation.
# 3. Package Selection and Interaction:
- The script navigates to the Bdjobs Pro subscription section and interacts with different subscription options, such as Quarterly, Yearly, and Monthly packages.
- It verifies and interacts with various package details and handles multiple panels and collapsible elements to simulate a user exploring different options.
  
# 4. Payment Method Verification:
- The script verifies that all payment methods (Bkash, Card, and others) are clickable and functional.
- It automates the process of selecting a payment method and proceeding to the payment confirmation step.
# 5. FAQ Interaction:
- The script loops through all FAQ panels on the page, automating the process of opening and closing each panel to ensure they function as expected.

# 6. Error Handling and Conditional Logic:
- The script includes error handling to manage scenarios where certain elements may not be immediately available or clickable, enhancing the robustness and reliability of the automation process.
  
# 7. JavaScript Execution for Enhanced Control:
- JavaScript was employed to scroll elements into view and perform clicks, particularly in scenarios where Selenium's native methods encountered issues like ElementClickInterceptedException.

# Technologies Used:
- Selenium WebDriver: For browser automation.
- Java: The primary programming language.
- WebDriverManager: For managing WebDriver binaries.
- ChromeOptions: To manage Chrome browser settings, including the use of extensions.
  
 This project showcases the automation of complex user interactions with a web-based service, improving efficiency in testing and verifying the functionality of Bdjobs Pro.
