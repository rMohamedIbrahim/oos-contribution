# 🚀 My Open Source Contributions

Welcome to my open source contributions repository! This documents my journey and contributions to various open source projects.

## 👨‍💻 About Me

Hi! I'm Mohamed Ibrahim, a passionate developer contributing to open source projects. I believe in giving back to the community and learning through collaboration.

## 🎯 Contribution Goals

- Learn new technologies and best practices
- Help improve projects I use and love
- Build connections within the developer community
- Enhance my coding skills through code reviews

## 📈 Contributions Overview

### 2025 Contributions

| Project                                                 | Issue                                                           | Description                                  | Status       | PR Link                                                       | Skills Used              |
| ------------------------------------------------------- | --------------------------------------------------------------- | -------------------------------------------- | ------------ | ------------------------------------------------------------- | ------------------------ |
| [Checkmate](https://github.com/bluewave-labs/Checkmate) | [#2701](https://github.com/bluewave-labs/Checkmate/issues/2701) | Fix text alignment in FilterHeader component | ✅ Submitted | [#2703](https://github.com/bluewave-labs/Checkmate/pull/2703) | React, CSS, Flexbox, MUI |

## 🛠️ Technologies & Skills

**Languages:** JavaScript, HTML, CSS
**Frameworks:** React, Node.js
**Tools:** Git, GitHub, VS Code
**UI Libraries:** Material-UI (MUI)
**Concepts:** Responsive Design, Component Architecture

## 📚 Detailed Contributions

### 1. Checkmate - Filter Header Alignment Fix

**Project:** [Checkmate](https://github.com/bluewave-labs/Checkmate) - A comprehensive server monitoring and alerting platform

**Issue:** [#2701 - Fix text alignment in FilterHeader component](https://github.com/bluewave-labs/Checkmate/issues/2701)

**Problem:** The Type, Status, and State filter headers in the monitoring dashboard were not properly aligned vertically, causing a poor user experience.

**Solution:**

- Implemented CSS flexbox layout for proper vertical alignment
- Used `display: flex` and `alignItems: center` for consistent positioning
- Refactored code to follow DRY principles based on code review feedback
- Extracted shared styling into reusable constants

**Technical Details:**

```javascript
const flexCenterStyles = {
  display: "flex",
  alignItems: "center",
};

// Applied to FormControl components for consistent alignment
<FormControl sx={{ minWidth: "10%", ...flexCenterStyles }}>
```

**Code Review Response:**

- Addressed CodeRabbit feedback for better code quality
- Removed redundant styling and improved maintainability
- Followed React and MUI best practices

**Files Modified:**

- `client/src/Components/FilterHeader/index.jsx`

**Impact:** Improved user experience by ensuring consistent visual alignment across filter components.

---

## 🎯 Future Contribution Plans

- [ ] Continue contributing to Checkmate project
- [ ] Explore contributions to other React-based projects
- [ ] Work on documentation improvements
- [ ] Contribute to beginner-friendly projects to help other newcomers

## 📫 Connect With Me

- **GitHub:** [rMohamedIbrahim](https://github.com/rMohamedIbrahim)
- **Email:** [rmohamedibrahim1@gmail.com]

## 🙏 Acknowledgments

Thanks to all the maintainers and communities that welcome new contributors and provide helpful feedback for learning and growth!

---

⭐ **Star this repository if you find it helpful!**
