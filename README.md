# Online Shawarma Saga

An addictive web-based idle/clicker game where you build your Shawarma empire from a humble beginning to an interdimensional culinary force! Click your way to success, automate production, unlock powerful upgrades, and reach new heights through the prestige system.


## Current Status: beta0.1

  This project is currently in **Beta Stage** based on the version in `index.html`. This means:

*   The core gameplay loop is implemented.
*   Many features are functional but may contain bugs.
*   Balance (costs, production rates, bonuses) is preliminary and subject to significant change.
*   UI and features are actively being developed.

**Feedback and bug reports are highly encouraged!** Please use the [GitHub Issues]([Link to Your GitHub Issues Page]) section of this repository.

*(Note: The game's User Interface is currently in Chinese (简体中文). This README is in English.)*

## Gameplay & Features

*   **Core Clicking:** Manually produce Shawarma and earn cash by clicking the rotating spit.
*   **Upgrades:** Enhance your clicking power (SPC), click value (MPC), critical hit chance/damage, and overall efficiency with various upgrades.
*   **Auto-Makers:** Hire Apprentices, Chefs, Masters, and build Robots, Factories, Restaurants, and even dimensional Portals to automate Shawarma production (SPS) and income (MPS).
*   **Stats Tracking:** Monitor your progress with detailed statistics (Money, Total Shawarma, SPS, MPS, SPC, MPC, Crit Chance/Damage, Clicks, Play Time, Bonuses).
*   **Special Boosts:** Activate timed abilities like "Rush Hour" for significant temporary production/income multipliers.
*   **Achievement System:** Unlock dozens of achievements by reaching milestones. Each unlocked achievement grants a permanent bonus to production or other stats.
*   **Prestige System ("巅峰之路"):** Reset your progress (excluding achievements and prestige points) to earn Prestige Points (PP) based on your current cash. Each PP provides a permanent global production bonus, allowing you to reach further in subsequent runs.
*   **Save System:**
    *   Automatic saving to browser Cookies every 30 seconds.
    *   Manual Save option.
    *   Export/Import save data feature for backup or transferring progress.
*   **Settings:**
    *   Choose number formatting (Short Scale - K/M/B, Scientific, Long).
    *   Toggle visual animations.
*   **Responsive Design:** The interface adapts to different screen sizes (Desktop, Tablet, Mobile).

## Technical Details

This version (beta0.1) is built with:

*   **Vanilla JavaScript (ES6+):** All game logic, state management, calculations, and DOM manipulation are handled without external JS frameworks.
*   **HTML5:** Standard structure for the game content.
*   **CSS3:** Extensive use of modern CSS for layout (Flexbox/Grid), styling, theming (CSS Variables), and animations/transitions.
*   **Single File Structure:** Currently, all HTML, CSS, and JavaScript code resides within a single `index.html` file.
*   **Local Persistence:** Game state is saved locally using browser Cookies (Base64 encoded JSON).

## Screenshots

*(Add screenshots of the game interface here)*
*   Main clicking area
*   Stats panel
*   Upgrade section
*   Auto-maker section
*   Achievements list

## Contributing

Contributions are welcome! The best way to contribute right now is:

1.  **Play the game:** Find bugs, balance issues, or areas for improvement.
2.  **Report Bugs:** If you find a bug, please open an issue on the [GitHub Issues]([Link to Your GitHub Issues Page]) page. Include steps to reproduce, your browser/OS, and screenshots if possible.
3.  **Suggest Features:** Have ideas for new upgrades, producers, achievements, or mechanics? Open an issue to discuss them.
4.  **Code Contributions (Future):** Once the project structure stabilizes, pull requests might be considered. Please open an issue to discuss any planned code changes beforehand.

## License

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.

---

*Let the Shawarma spinning begin!*
