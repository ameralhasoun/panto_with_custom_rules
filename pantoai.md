# Code Review Rules

When reviewing code in this repository, apply the following rules:

## 🔧 Error Handling
- Check that methods validate inputs and handle possible errors.
- If a method may fail or receive invalid data, ensure it uses proper error handling (e.g., validation or try-catch).
- Request changes if the code assumes inputs are always valid or could throw unhandled exceptions.

## 🧱 Naming Conventions
- All class names, method names, and public members in C# must follow **PascalCase**.
- Request changes if names use snake_case, camelCase, or inconsistent capitalization.

## 📝 Code Comments
- Public or important methods should have a short descriptive comment explaining their purpose.
- Request improvements when comments are missing, unclear, or unhelpful.

## 🖨️ Console Logging
- Console output should be meaningful and descriptive.
- If `Console.WriteLine` is used, ensure that the message clearly states what is being logged.
- Flag vague messages like: “Done”, “Here”, “Test”, or unclear outputs.

## ✨ Clean and Readable Code
- Code must remain clean, readable, and well formatted.
- Look for messy layout, confusing logic, poor indentation, or inconsistent spacing and request improvements.

## ♻️ Code Duplication
- Identify duplicate or repeated code across methods, classes, or files.
- Suggest extracting shared logic into reusable methods or services when duplication is found.
