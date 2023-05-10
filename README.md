# Landing Page Generator 🚀

Landing Page Generator is a proof of concept that uses a JSON configuration with GPT-4 to create custom landing pages. This project showcases the potential for generating responsive and visually appealing landing pages for your product or service with ease. The generator offers a variety of sections, styles, and elements, allowing for a high degree of customization to suit your needs.

While it can successfully generate pages to spec, please keep in mind that it may not cover all aspects of a professional landing page. Check out a [sample page](https://vincefav.github.io/landing-page-generator/sample_page.html) generated using this script.

## Table of Contents

1. [Getting Started](#getting-started)
2. [Configuration](#configuration)
3. [Commands](#commands)
4. [Rules](#rules)
5. [User Preferences](#user-preferences)
6. [Init](#init)

## Getting Started

To start using the Landing Page Generator, simply paste the JSON into GPT-4 and the bot will ask you to configure it. For best results, edit the JSON to your liking beforehand (e.g., update your `meta`, `sections`, and `user_preferences`).

## Configuration

The JSON configuration includes various settings and options for your landing page:

- Meta: Contains information about the page title, description, favicon, and more.
- Sections: Define the different sections of your landing page, such as header, hero, features, etc.
- Commands: List of commands that the bot understands to perform various actions.
- Rules: Guidelines that the landing page builder must follow.
- User Preferences: The user's configuration/preferences for the Landing Page Builder.

## Commands

The Landing Page Generator understands the following commands:

- `/configure`: Prompt the user through the configuration process and output the configuration.
- `/preview`: Provide a preview of the landing page based on the user's configuration.
- `/generate`: Generate the final HTML, CSS, and JavaScript code for the landing page based on the user's configuration.
- `/reset`: Reset the configuration to the default settings.
- `/add_section`: Add a new section to the landing page based on the user's input.
- `/remove_section`: Remove a specified section from the landing page.
- `/modify_section`: Modify a specified section based on the user's input.

Of course, natural language works as well.

## Rules

The Landing Page Generator must follow these rules:

1. Follow the user's specified configuration for page elements and styles.
2. Create a responsive landing page based on the user's preferences.
3. Generate a preview of the landing page based on the user's configuration.
4. Generate the final code for the landing page (HTML, CSS, and JavaScript) based on the user's configuration.
5. Reset the configuration to the default settings if specified.
6. Inform the user about the changes in the configuration, if any.
7. Include JavaScript functions as specified by the user.
8. Write persuasive copy to sell the product.
9. Generate its own valid links when not supplied with them (e.g., for navigation).
10. Insert relevant iconography using FontAwesome or similar libraries.
11. Intelligently decide whether to omit the relevant code, guess what information should be used instead when provided with blank or generic information.
12. Utilize the preferred colors in the design, including the background, text, headings, and links.
13. Use different font sizes and weights for headings (h1, h2, h3, etc.) to create a clear visual hierarchy.
14. Ensure that all required elements are present in each section and that the formatting remains consistent with the chosen framework (e.g., Bootstrap) and user preferences.
15. Review the generated code to ensure it accurately reflects the user's JSON configuration, including all specified elements, styles, and formatting.
16. Ensure that elements such as buttons are horizontally aligned across different sections, particularly when the content above them has varying heights.

## User Preferences

The user's configuration/preferences for the Landing Page Builder include:

- Page Elements: Define the header, hero section, content sections, and footer.
- Page Styles: Specify the colors and fonts for the landing page.
- JavaScript Enabled: Enable or disable JavaScript functionality.
- JavaScript Functions: List of custom JavaScript functions to be included.
