# EmailUtility: Java Email Generator :email:

EmailUtility simplifies the process of generating email addresses with a specific syntax: `firstname.lastname@department.company.com`. You have the flexibility to customize the department name, change the password, set the mailbox capacity, and define an alternate email address. Additionally, it automatically generates a secure random password for each user.

## Table of Contents
- [How to Use the Email Generator](#how-to-use-the-email-generator)
- [Features](#features)
- [Getting Started](#getting-started)
- [Example Usage](#example-usage)
- [Contributing](#contributing)
- [License](#license)

## How to Use the EmailUtility :rocket:

1. **Download the Code**
   - Clone or download the project from the [EmailUtility Repository](https://github.com/footcricket05/EmailUtility).

2. **Explore the Code** :mag_right:

   - Open the project in your preferred Java IDE (e.g., IntelliJ IDEA, Eclipse).

3. **Running the Project** :arrow_forward:

   - Run the `EmailMainProgram.java` class to generate an example email.
   - Customize and extend the code as needed for your use case.

## Features :gear:

- Generate email addresses using the syntax: `firstname.lastname@department.company.com`.
- Select a department for each employee.
- Automatically generate a random password with a customizable length.
- Set mailbox capacity according to your preferences.
- Define an alternate email address for recovery.

## Getting Started :computer:

To use the Email Generator in your own Java project, you can follow these steps:

1. **Include the Code** :file_folder:

   - Copy the `EmailBackProgram.java` and `EmailMainProgram.java` files into your project.

2. **Instantiate the EmailBackProgram** :electric_plug:

   - Create an instance of the `EmailBackProgram` class and provide the first name and last name of the employee. The program will guide you to choose a department and generate a password.

3. **Customize and Extend** :wrench:

   - Modify the code to fit your requirements, such as integrating it into a larger HR or employee management system.

## Example Usage :computer:

Here's an example of how to use the Email Generator in your Java application:

```java
public static void main(String[] args) {
    EmailBackProgram email = new EmailBackProgram("Shaurya", "Srinet");
    System.out.println(email.showInfo());
}
```

This code will create an email address for "Shaurya Srinet" and display information about the email, including the company email, mailbox capacity, and more.

## Contributing :handshake:

Feel free to contribute to this project by opening issues, suggesting improvements, or submitting pull requests on the [EmailUtility Repository](https://github.com/footcricket05/EmailUtility). Your contributions are welcome!

## License :page_with_curl:

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

Simplify the process of generating and managing email addresses for your employees with the EmailUtility! :envelope:
