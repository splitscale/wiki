# Standard Naming Guide

This guide provides recommendations for naming conventions in software development. These conventions are intended to improve code readability, consistency, and maintainability.

## Naming Conventions

### Packages

- Use lowercase letters.
- Use a hierarchical naming convention, with words separated by dots.
- Avoid using abbreviations or acronyms.

Example: `com.splitscale.myproject.mypackage`

### Classes and Interfaces

- Use PascalCase.
- Use nouns or noun phrases to name classes.
- Use uppercase letters to start each word in the name.

Example: `public class MyClass`

### Methods

- Use camelCase.
- Use verbs or verb phrases to name methods.
- Use lowercase letters to start the first word, and uppercase letters for subsequent words.

Example: `public void myMethod()`

### Variables

- Use camelCase.
- Use descriptive names that convey the purpose of the variable.
- Use lowercase letters to start the first word, and uppercase letters for subsequent words.

Example: `int myVariable;`

### Constants

- Use uppercase letters.
- Use underscores to separate words.
- Use descriptive names that convey the purpose of the constant.

Example: `public static final int MAXIMUM_NUMBER = 100;`

### Folders

- Use the package naming convention.
- Use a hierarchical folder structure, with folders named after each level of the package name.
- Use lowercase letters.

Example:

```
src/
└── main/
    └── java/
        └── com/
            └── splitscale/
                └── myproject/
                    └── mypackage/
                        └── MyClass.java
```


## Conclusion

By following these naming conventions, you can create code that is more readable, consistent, and maintainable. Adopting these conventions across your organization can help to improve collaboration and make it easier for developers to understand each other's code.
