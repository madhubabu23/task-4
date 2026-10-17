
# Week 4 Task: Enhancing Web Page Performance and Accessibility

## Project Overview

This project focuses on improving the performance, accessibility, and usability of a static webpage using HTML5 and CSS3.

The webpage follows semantic HTML practices, supports keyboard navigation, uses responsive styling, and minimizes unnecessary resources to provide a better user experience across different devices.

## Objectives

- Improve webpage loading performance.
- Use semantic HTML elements.
- Follow web accessibility best practices.
- Support keyboard navigation and screen readers.
- Optimize CSS by reducing redundancy.
- Test performance and accessibility using browser tools.

## Technologies Used

- HTML5
- CSS3
- Visual Studio Code
- Google Chrome DevTools
- Lighthouse
- WAVE Accessibility Evaluation Tool
- axe DevTools
- WebPageTest (optional)

## Project Structure

```text
week4-performance-accessibility/
├── index.html
├── style.css
└── README.md
```

## Features Implemented

### 1. Performance Optimization

- Used lightweight HTML and CSS.
- Avoided unnecessary JavaScript and external libraries.
- Used system fonts instead of downloading external fonts.
- Reduced redundant CSS declarations.
- Used CSS Grid and flexible layouts for responsiveness.
- Avoided large image assets in the sample webpage.
- Added viewport metadata for mobile devices.

### 2. Accessibility Improvements

- Used semantic elements such as `header`, `nav`, `main`,
  `section`, `article`, and `footer`.
- Added a skip-to-main-content link.
- Maintained a logical heading hierarchy.
- Added accessible names to navigation and sections.
- Implemented visible keyboard focus indicators.
- Added labels and instructions to the email form.
- Used appropriate input types and native validation.
- Included reduced-motion support.
- Used ARIA attributes where they provide additional context.

### 3. Responsive Design

The webpage uses CSS Grid, flexible widths, relative units,
and media queries to adapt to desktop, tablet, and mobile screens.

## How to Run the Project

1. Download or clone the project.
2. Open the project folder in Visual Studio Code.
3. Make sure `index.html` and `style.css` are in the same folder.
4. Open `index.html` in a web browser.
5. Alternatively, use the Live Server extension in VS Code.

## Performance Testing

### Google Lighthouse

1. Open the webpage in Google Chrome.
2. Open Developer Tools using `F12`.
3. Select the Lighthouse tab.
4. Run the Performance and Accessibility audits.
5. Review the recommendations and address any issues found.

### WebPageTest

1. Host the webpage on a publicly accessible URL if required.
2. Open WebPageTest.
3. Enter the webpage URL.
4. Run a performance test.
5. Review loading time, resource requests, and page weight.

## Accessibility Testing

### WAVE

Use the WAVE browser extension or evaluation website to
identify accessibility errors and possible improvements.

### axe DevTools

Run an axe DevTools scan to identify common accessibility
issues, including missing labels and certain contrast problems.

### Manual Testing

- Navigate using `Tab` and `Shift + Tab`.
- Activate links using `Enter`.
- Check that keyboard focus is visible.
- Test the page at 200% browser zoom.
- Check layout on mobile and desktop.
- Verify text contrast using a contrast checker.
- Test with a screen reader where available.

## Expected Outcomes

- A lightweight and responsive webpage.
- Improved semantic structure.
- Better keyboard navigation.
- More accessible forms and page landmarks.
- Reduced unnecessary resource requests.
- A maintainable and organized CSS stylesheet.

## Limitations

- The signup form is for demonstration purposes and does not
  submit data to a backend service.
- Performance and accessibility scores depend on the
  browser, testing environment, and actual audit results.
- Automated tools cannot identify every accessibility issue;
  manual testing is also necessary.

## Conclusion

This project demonstrates how semantic HTML, optimized CSS,
responsive layouts, keyboard accessibility, and testing tools
can improve webpage performance and usability.

The task provides practical experience in building web pages
that are lightweight, maintainable, and more accessible to
users with different needs.

## Author

**Name:** Uradi Madhu Babu

**Task:** Week 4 - Enhancing Web Page Performance and Accessibility
