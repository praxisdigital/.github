---
applyTo: "**/*.{php,feature},amd/**/*.js,style/**/*.{css,scss}"
---

## Coding Standards & Practices
 
- Follow the Moodle core coding style, as defined by the version in version.php.
- Place all company-specific extensions inside the app/ folder.
- Write code that is simple, testable, and maintainable.
 
## Principles & Style
 
- Adhere to SOLID principles and the DRY coding style.
- Use English for all comments and documentation.
 
## Languages & Frameworks
 
- PHP is the primary backend language. Use the latest PHP version supported by Moodle (per version.php).
- JavaScript must use ES6+ modules. Do not use jQuery, RequireJS, or YUI.
- Match source JS files to compiled minified versions.
- SASS/SCSS is used for styling, compiled via Grunt.
 
## Testing & Quality
 
- Use PHPUnit and Behat for testing.
- Target full coverage of business logic with unit tests.
- Write fast unit tests and reinforce functionality with integration tests.
- For frontend, use Behat and ensure at least one test per repository.
- Don't use deprecated features.
