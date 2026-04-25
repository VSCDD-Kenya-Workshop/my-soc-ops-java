---
name: workspace-instructions
---

# Workspace Instructions

## Development Checklist
- [ ] Install Java 21 JDK
- [ ] Build the project using Maven (`./mvnw clean package`)
- [ ] Run the development server (`./mvnw spring-boot:run`)
- [ ] Verify the application at `http://localhost:8080`
- [ ] Ensure all tests pass (`./mvnw test`)

## Project Overview
This is a Spring Boot project for the Soc Ops application. It includes:
- Java backend services
- Thymeleaf templates for frontend rendering
- Custom CSS utilities for styling

## CSS Utilities
The project uses custom utility classes defined in `src/main/resources/static/css/app.css`. These classes provide consistent styling similar to Tailwind CSS.

### Examples
- **Layout:** `.flex`, `.grid`, `.items-center`
- **Spacing:** `.p-1`, `.mb-2`, `.gap-1`
- **Colors:** `.bg-white`, `.text-gray-500`

## Frontend Design Principles
- Use distinctive fonts and cohesive color themes.
- Avoid generic aesthetics (e.g., overused fonts, clichéd color schemes).
- Incorporate animations for micro-interactions.
- Match design complexity to the aesthetic vision.

## Instructions for Agents
- Follow the development checklist before making changes.
- Use the CSS utilities and design principles to maintain consistency.
- Ensure all changes are tested and documented.

---

For more details, refer to the [CSS Utilities Instructions](../.github/instructions/css-utilities.instructions.md) and [Frontend Design Instructions](../.github/instructions/frontend-design.instructions.md).