# Biome, HTMLHint, Prettier for Linting & Formatting 
### Changed on 05/11/25 to include HTMLHint and Prettier to lint and format HTML, as Biome currently only supports Javascript and CSS.

### Feature
 - Biome acts as all-in-one tool that formats, lints code, and more
   - Written in Rust for high performance so reduces overall build and CI/CD pipeline times.
   - Catches early errors in code before sending to build to prevent errors
 - HTMLHint is specifically designed to lint HTML 
 - Prettier is a popular formatting tool with an easy-to-use VSCode integration, allowing us to format on save prior to running the build pipeline. 
# Pros:
- Code quality will be high with this enabled.
- We will have fewer errors in our production code
- The build and pipelines times will still stay low to allow for faster testing
# Cons
- Biome only supports JS and CSS, so we needed to introduce additional dependencies to lint and format HTML
- As it is a tool we have not used earlier, setup is trickier
- However, we have added it will ensure it works with test this week
### Date: 5/11/2025
