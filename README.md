# Supervision Hours Calculator

Calculate whether your supervision hours meet the requirements for your counselling training.

## About

This tool helps trainee counsellors determine if they have sufficient supervision hours to meet their training requirements. Simply enter your supervision ratio, client details, and supervision arrangements to see if you're meeting your training standards.

## Features

- **Flexible Ratio Configuration**: Set your own supervision-to-client hours ratio
- **Individual & Group Supervision**: Track both types with customizable group supervision percentages
- **Automatic Calculations**: Real-time results as you type
- **50-Minute Session Handling**: Automatically converts 50-minute sessions to therapeutic hours
- **Future Planning**: See what happens if you take on another client
- **Local Storage**: Your data is saved automatically and persists between visits
- **Privacy First**: All calculations happen in your browser - no data is sent to any server

## Usage

Simply open `index.html` in your web browser. The calculator will:

1. Load any previously saved data from your browser's local storage
2. Allow you to configure your supervision ratio (defaults to 6:1)
3. Enter your client details (number of clients per week and session length)
4. Add your supervision arrangements (individual or group)
5. Show you whether you have sufficient supervision hours

## Tech Stack

- **HTML5** - Structure
- **Alpine.js** - Reactive interactivity
- **Tailwind CSS** - Styling
- **LocalStorage API** - Data persistence

No build step required! Everything runs directly in the browser via CDNs.

## Live Demo

Visit the live version at: [https://supervisioncalculator.org/](https://supervisioncalculator.org/)

## Contributing

We welcome contributions! Here's how you can help:

### Reporting Issues

If you find a bug or have a feature request, please [open an issue](https://github.com/yourusername/supervision/issues) with:
- A clear description of the problem or feature
- Steps to reproduce (for bugs)
- Expected vs actual behavior
- Screenshots if applicable

### Contributing Code

1. **Fork the repository** on GitHub

2. **Clone your fork** locally:
   ```bash
   git clone https://github.com/yourusername/supervision.git
   cd supervision
   ```

3. **Create a new branch** for your feature or fix:
   ```bash
   git checkout -b feature/your-feature-name
   ```

   Use descriptive branch names like:
   - `feature/add-export-functionality`
   - `fix/calculation-error`
   - `docs/update-readme`

4. **Make your changes** and test thoroughly:
   - Open `index.html` in your browser
   - Test all calculations and interactions
   - Verify localStorage persistence works
   - Check responsive design on different screen sizes

5. **Commit your changes** with clear, descriptive messages:
   ```bash
   git add .
   git commit -m "Add feature: export results to PDF"
   ```

6. **Push to your fork**:
   ```bash
   git push origin feature/your-feature-name
   ```

7. **Submit a Pull Request**:
   - Go to the original repository on GitHub
   - Click "New Pull Request"
   - Select your fork and branch
   - Provide a clear description of your changes
   - Reference any related issues

### Code Style Guidelines

- Use meaningful variable and function names
- Add comments for complex logic
- Maintain the existing code structure and formatting
- Keep the single-file architecture (avoid adding build steps)
- Test across different browsers if possible

### What to Contribute

Ideas for contributions:
- Bug fixes
- UI/UX improvements
- Additional calculations or features
- Accessibility enhancements
- Documentation improvements
- Internationalization (i18n)
- Export/import functionality
- Print-friendly styling

## License

This project is licensed under the MIT License - see below for details:

```
MIT License

Copyright (c) 2025 Supervision Hours Calculator Contributors

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

## Support

If you find this tool helpful, please consider:
- ⭐ Starring the repository
- 🐛 Reporting bugs
- 💡 Suggesting new features
- 🔀 Contributing code

## Disclaimer

This calculator is a tool to help estimate supervision requirements. Always verify with your training organization's specific requirements, as ratios and rules may vary between different counselling training programs and regulatory bodies.
