# Back-End Developer Portfolio Project Rules

This project is a portfolio for employment as a back-end developer in the UK.

## Coding Restrictions

To maintain high-quality code and ensure consistency throughout the project, the following rules are established:

### Commit Message Rules

1. **Structure**: Follow the conventional commit style:
   - `feat`: A new feature
   - `fix`: A bug fix
   - `docs`: Documentation changes
   - `style`: Code style changes (formatting, missing semi colons, etc.)
   - `refactor`: Code refactoring
   - `test`: Adding or modifying tests
   - `chore`: Changes to the build process or auxiliary tools and libraries
2. **Message Format**:
   - Use the present tense ("Add feature" not "Added feature")
   - Use the imperative mood ("Move cursor to..." not "Moves cursor to...")
   - Limit the first line to 72 characters or less
   - Reference issues and pull requests liberally after the first line

### Commit Size Rules

1. **Small Commits**: Keep commits small and focused on a single issue or feature.
2. **Atomic Commits**: Each commit should represent a complete and functional change.
3. **Frequent Commits**: Commit often to record progress and allow for easier rollbacks if needed.

### Testing Rules

1. **Test Coverage**: Aim for at least 80% test coverage for all code.
2. **Unit Tests**: Write unit tests for all functions and methods.
3. **Integration Tests**: Ensure all modules work together as expected with integration tests.
4. **Test Automation**: Use continuous integration tools to automate testing.

### Language Rules

1. **Primary Language**: The primary language for this project is Java.
2. **Framework**: Use Spring Framework for application development.
3. **Style Guide**: Follow the Google Java Style Guide.
4. **Comments**: Write clear and concise comments. Document all classes and methods with Javadoc.
5. **Language Use**: All code, comments, and documentation must be written in English.

### OOP Rules

1. **Encapsulation**: Use private and protected access modifiers to restrict access to class attributes.
2. **Inheritance**: Prefer composition over inheritance unless a clear hierarchy is present.
3. **Polymorphism**: Use interfaces or abstract base classes to define methods that derived classes must implement.

### Git Branch Rules

1. **Branching Model**: Follow Git Flow or a similar branching model.
   - `main`: Production-ready code
   - `develop`: Latest development changes
   - `feature/*`: New features
   - `bugfix/*`: Bug fixes
   - `release/*`: Release preparation
   - `hotfix/*`: Hotfixes for production
2. **Branch Naming**: Use descriptive names (e.g., `feature/login-page`, `bugfix/user-authentication`).
3. **Pull Requests**: All changes must go through pull requests with code reviews before merging.

### SOLID Rules

1. **Single Responsibility Principle (SRP)**: A class should have one, and only one, reason to change.
2. **Open/Closed Principle (OCP)**: Software entities should be open for extension but closed for modification.
3. **Liskov Substitution Principle (LSP)**: Objects of a superclass should be replaceable with objects of a subclass without affecting the correctness.
4. **Interface Segregation Principle (ISP)**: Many client-specific interfaces are better than one general-purpose interface.
5. **Dependency Inversion Principle (DIP)**: Depend on abstractions, not on concretions.

By adhering to these rules, we aim to ensure a high standard of code quality, maintainability, and collaboration throughout the project. Let's create something great together!

---

Feel free to suggest any additional rules or modifications to better suit our project's needs.
