# Retro Terminal Portfolio

This project is an interactive **terminal-style portfolio** designed to showcase your professional information with a retro computer vibe. Users can type commands in a simulated command-line interface to explore your profile, skills, work experience, education, and more.

---

## **Features**

- **Retro Themed Terminal:**
  - Styled with a dark background, neon green text, and pixelated font (`Press Start 2P`).
  - Mimics an old-school computer terminal interface.

- **Interactive Commands:**
  - Users can type predefined commands (like `profile`, `skills`, or `help`) to access specific sections of your portfolio.

- **Dynamic and Engaging:**
  - Features a blinking cursor and animations to replicate a real terminal.
  - Fully responsive design for all devices.

---

## **Commands**

| Command     | Description                                                   |
|-------------|---------------------------------------------------------------|
| `help`      | Displays all available commands.                              |
| `profile`   | Shows personal details.                                       |
| `skills`    | Lists technical and soft skills.                              |
| `exp`       | Displays work experience.                                     |
| `certs`     | Shows certifications.                                         |
| `awards`    | Lists honors and awards.                                      |
| `motto`     | Displays your personal motto.                                 |
| `edu`       | Provides educational background.                              |
| `contact`   | Displays clickable contact information.                       |
| `ls`        | Lists all available commands (briefly).                       |
| `whoami`    | Displays user info.                                           |
| `clear`     | Clears the terminal history.                                  |

---

## **Setup Instructions**

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/your-username/retro-terminal-portfolio.git
   cd retro-terminal-portfolio
## Open in Browser

- Simply open the `index.html` file in your browser to view the portfolio.

## Customize

- Update the `data` object in the `<script>` section with your own:
  - Profile information
  - Skills
  - Work experience
  - Certifications, etc.

---

## Technologies Used

- **HTML**: For the structure of the portfolio.
- **CSS**: For styling and animations.
  - Includes Google Fonts for a retro aesthetic (`Press Start 2P`).
- **JavaScript**: For interactive command-line functionality.
  - Dynamic command processing via the `handleCommand()` function.

---

## How It Works

### Terminal Interface

- A `<div>` styled to look like a terminal with a header and input box.
- Users can type commands in the input box.

### Command Processing

- JavaScript listens for the "Enter" key.
- Matches the command to predefined actions in the `handleCommand()` function.
- Outputs relevant content dynamically in the "command history."

### Customization

- All portfolio data is stored in a `data` object in JavaScript.
- Add or modify commands in the `commands` object.

---

5. Demo :
   
https://github.com/user-attachments/assets/a13d190f-e653-48b5-b72f-b2a060484554

7. Exercises:

    Add New Commands: Extend the commands object to include new commands like projects or hobbies.
    Responsive Design: Modify the CSS to make the terminal responsive for mobile devices.
    Error Handling: Improve error messages for incorrect commands or add suggestions for typos.
    Save State: Implement a feature to save the state of the terminal (command history) using localStorage.

8. Advanced Topics:

    Security: Discuss how to safely handle user input to prevent XSS attacks in real-world applications.
    Accessibility: How to make this terminal CV accessible, considering screen readers and keyboard navigation.

Conclusion:

By the end of this guide, one should be able to build their own interactive CV or similar applications, understanding the integration of HTML for structure, CSS for style, and JavaScript for interactivity.****
