# Code Contributions

## Before You Start Coding

Please follow these guidelines before starting to work on a feature or bugfix:

- If you're implementing a bugfix or feature from an existing issue, **comment on that issue** to let others know you're working on it. This helps avoid duplicate work and ensures better coordination.
- If you're working on a new feature that doesn't have an existing issue, **create a new issue first**. This allows the team to discuss and track the feature.
- For major feature implementations, be prepared to **maintain your code** in the future (e.g., fixing bugs or resolving merge conflicts).  
  You can also join our [Matrix channel](https://matrix.to/#/+freetube:matrix.org) for real-time collaboration and updates.

## Before Submitting a Pull Request

Please make sure to follow these guidelines before sending a pull request:

- By submitting a pull request, you agree that your code will be published under the [GNU Affero General Public License](https://www.gnu.org/licenses/agpl-3.0.html).
- Always **link the related issue** in your pull request.
- Do **not include non-free software or proprietary modules** in your code.
- Ensure your pull request is set up to **merge into the `development` branch**.
- Keep your branch **up to date** with the `development` branch before submitting your PR.
- Follow the **existing code style** in the project. Please review the current code to understand the style and conventions.
- Use **ES6 standards**:
  - Prefer `let` and `const` over `var`.
  - Use arrow functions: `(response) => {}` instead of `function(response) {}`.
- **Comment your code** where necessary. Follow the [JavaScript Documentation and Comments Standard](https://www.drupal.org/docs/develop/standards/javascript/javascript-api-documentation-and-comment-standards).
- Follow proper **Vue.js structure** when creating components. Refer to existing code and the [Vue.js Guide](https://vuejs.org/v2/guide/) for best practices.
- **Test your code thoroughly**:
  - Ensure that both new and existing features work.
  - Confirm compatibility with both the Local API and the Invidious API.
- Run `npm run lint` to check for style issues, and `npm run lint-fix` to fix minor problems automatically.
- Only add new Node modules if **absolutely necessary**. For example:
  - ✅ When a module is critical (e.g., `nedb` for database usage).
  - ✅ When it avoids reinventing functionality (e.g., `autolinker` for URL linking).
- Please try to **stay involved with the community** and maintain your code. FreeTube is developed by a small team of volunteers, and your continued help is appreciated.

## Setting Up Your Environment

Refer to our [Getting Started guide](https://docs.freetubeapp.io/development/getting-started/) on the wiki for instructions on setting up your development environment.
