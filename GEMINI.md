--- Context from: ../../../../.gemini/GEMINI.md ---
## Gemini Added Memories
- In the svg-converter.html project, the correct method for converting SVG lines or polylines with arrowheads (marker-start/marker-end) to Draw.io is to use a 'two-cell' approach. This involves creating one mxCell for the line itself (without arrow styles) and a second, separate mxCell for the arrowheads. The second cell is an invisible edge that only carries the startArrow/endArrow styles, ensuring markers are rendered correctly in Draw.io.
--- End of Context from: ../../../../.gemini/GEMINI.md ---

## Project

-   **Name:** "QuickDevKit"
-   **Description:** "Lightning fast JSON formatter, validator and developer tools collection with multilingual support"
-   **Version:** "1.0.0"
-   **Domain:** "quickdevkit.tools"
-   **Repository:** "https://github.com/username/quickdevkit"

## Branding

-   **Name:** "QuickDevKit"
-   **Tagline:** "Lightning Fast Developer Tools"
-   **Logo:** "⚡" # Lightning bolt emphasizing speed
-   **Colors:**
    -   **Primary:** "#3b82f6" # Blue - trust and professionalism
    -   **Secondary:** "#f59e0b" # Amber - energy and speed
    -   **Accent:** "#10b981" # Green - success states
    -   **Dark:** "#1f2937" # Dark theme primary
    -   **Light:** "#f9fafb" # Light theme primary

## Tech Stack

-   **Frontend:** "HTML5 + Vanilla JavaScript + CSS3"
-   **Editor:** "CodeMirror 5.65.16"
-   **Styling:** "Custom CSS with Tailwind-inspired classes"
-   **Icons:** "Unicode emoji + Lucide React icons"
-   **Monetization:** "Google AdSense (ca-pub-2369255699430177)"
-   **Analytics:** "Google Analytics (to be added)"
-   **Deployment:** "GitHub Pages"

## Architecture

-   **Type:** "Collection of Single Page Applications (SPAs)"
-   **Structure:**
    ```
    /
    ├── index.html (main JSON tool)
    ├── svg-converter.html (SVG to Draw.io tool)
    └── ... (other tools as standalone HTML files)
    ```

## Features

-   **JSON Tool:**
    -   "Real-time JSON validation with precise error highlighting"
    -   "Smart formatting with proper indentation"
    -   "Comment support (// single-line and /* multi-line */)"
    -   "One-click copy and minify functions"
    -   "Sample data loading for quick testing"
-   **SVG to Draw.io Converter:**
    -   "Convert SVG files to editable Draw.io diagrams"
    -   "Batch processing of multiple files"
    -   "Live preview of uploaded SVGs"
    -   "Client-side conversion logic"
    -   "Options to preserve text, connections, groups, and colors"
    -   "Multiple output formats (.drawio, .xml, .library)"
-   **UI/UX:**
    -   "Dark/Light mode toggle with system preference detection"
    -   "Responsive design for mobile and desktop"
    -   "Professional CodeMirror editor with syntax highlighting"
    -   "Smooth transitions and hover effects"
    -   "Expandable guide sections with animations"
-   **Multilingual:**
    -   "Auto-detection based on browser language, timezone, and locale"
    -   "4 supported languages: English (en), 한국어 (ko), 日本語 (ja), 中文 (zh-CN)"
    -   "Intelligent fallback to English for unsupported languages"
    -   "Localized samples and error messages"

## Language Support

-   **Detection Methods:**
    -   "navigator.language and navigator.languages"
    -   "Intl.DateTimeFormat locale resolution"
    -   "Timezone-based region analysis (Asia/Seoul → ko, Asia/Tokyo → ja)"
    -   "Currency and number formatting patterns"
-   **Translation Structure:**
    ```javascript
    translations = {
      'language_code': {
        // Header elements
        devTools: 'Brand name',
        jsonTool: 'JSON Tool tab name',
        
        // Core functionality
        inputPlaceholder: 'Input editor placeholder',
        outputPlaceholder: 'Output editor placeholder',
        validJson: 'Success message',
        syntaxError: 'Error message title',
        
        // Guide and tutorial content
        jsonGuideTitle: 'Guide section title',
        // ... comprehensive translation keys
      }
    }
    ```

## Coding Conventions

-   **JavaScript:**
    -   "Use camelCase for variables and functions"
    -   "Use const/let instead of var"
    -   "Prefer arrow functions for inline callbacks"
    -   "Add error handling for all async operations"
    -   "Use meaningful variable names (inputEditor, outputEditor)"
    -   "Add comments for complex logic sections"
-   **CSS:**
    -   "Use BEM-inspired naming: .component-element--modifier"
    -   "Group related styles together"
    -   "Always include dark mode variants"
    -   "Use CSS custom properties for theme colors"
    -   "Follow mobile-first responsive design"
    -   "Transition animations should be 0.2s-0.3s ease"
-   **HTML:**
    -   "Use semantic HTML5 elements"
    -   "Include data-i18n attributes for translatable text"
    -   "Maintain accessibility with proper ARIA labels"
    -   "Use meaningful class names and IDs"

## File Structure

-   **Current:**
    ```
    /
    ├── index.html (JSON tool)
    ├── svg-converter.html (SVG to Draw.io Converter)
    ├── README.md (project documentation)
    ├── GEMINI.md (this file)
    └── CNAME (GitHub Pages custom domain)
    ```
-   **Planned Expansion:**
    ```
    /
    ├── index.html (JSON tools)
    ├── html/
    │   └── index.html (HTML formatter)
    ├── css/
    │   └── index.html (CSS formatter)
    ├── base64/
    │   └── index.html (Base64 encoder/decoder)
    ├── assets/
    │   ├── css/
    │   ├── js/
    │   └── images/
    └── api/
        └── endpoints for premium features
    ```

## Development Guidelines

-   **New Features:**
    -   "Always add multilingual support from the start"
    -   "Include both light and dark theme styles"
    -   "Test on mobile devices and different screen sizes"
    -   "Add loading states for async operations"
    -   "Include helpful error messages and user feedback"
    -   "Maintain consistent design patterns with existing features"
-   **Performance:**
    -   "Minimize dependencies (prefer vanilla JS over frameworks)"
    -   "Optimize for fast initial load time"
    -   "Use efficient DOM manipulation techniques"
    -   "Debounce user input for real-time validation"
    -   "Lazy load non-critical features"
-   **Accessibility:**
    -   "Support keyboard navigation"
    -   "Include proper ARIA labels and roles"
    -   "Maintain good color contrast ratios"
    -   "Provide alt text for all images"
    -   "Ensure functionality works without JavaScript (graceful degradation)"

## Monetization

-   **Current:**
    -   "Google AdSense automatic ads (ca-pub-2369255699430177)"
    -   "Strategic ad placement in content sections"
    -   "User-friendly ad integration"
-   **Future:**
    -   "Premium features (ad-free experience)"
    -   "API access for developers"
    -   "Advanced tools and integrations"
    -   "Team collaboration features"

## Expansion Roadmap

-   **Phase 1 (Current):**
    -   "✅ JSON formatter with comment support"
    -   "✅ SVG to Draw.io Converter"
    -   "✅ Multilingual interface (4 languages)"
    -   "✅ Dark/light theme"
    -   "✅ Google AdSense integration"
    -   "✅ Comprehensive guides and tutorials"
-   **Phase 2 (Next 3 months):**
    -   "HTML formatter and beautifier"
    -   "CSS formatter and minifier"
    -   "Base64 encoder/decoder"
    -   "URL encoder/decoder"
    -   "Hash generators (MD5, SHA256)"
-   **Phase 3 (Next 6 months):**
    -   "Regex tester and builder"
    -   "Color palette generator"
    -   "Lorem ipsum generator"
    -   "QR code generator"
    -   "Image optimization tools"
-   **Phase 4 (Long-term):**
    -   "API endpoints for programmatic access"
    -   "User accounts and saved preferences"
    -   "Team collaboration features"
    -   "Advanced JSON schema validation"
    -   "Custom tool builder"

## SEO Strategy

-   **Target Keywords:**
    -   **Primary:** ["json formatter", "json validator", "json beautifier"]
    -   **Secondary:** ["developer tools", "json online", "json parser", "quickdevkit"]
    -   **Long-tail:** ["json formatter with comments", "online json validator tool", "free json beautifier"]
-   **Content Strategy:**
    -   "Create comprehensive guides for each tool"
    -   "Include practical examples and use cases"
    -   "Maintain high-quality, original content"
    -   "Regular updates with new features and improvements"
    -   "Build backlinks through developer community engagement"

## Deployment

-   **Platform:** "GitHub Pages"
-   **Domain:** "quickdevkit.tools (custom domain via Namecheap)"
-   **SSL:** "Automatic via GitHub Pages (Let's Encrypt)"
-   **CDN:** "GitHub's global CDN"
-   **DNS Settings:**
    ```
    # Namecheap DNS Records:
    Type: A, Host: @, Value: 185.199.108.153
    Type: A, Host: @, Value: 185.199.109.153  
    Type: A, Host: @, Value: 185.199.110.153
    Type: A, Host: @, Value: 185.199.111.153
    Type: CNAME, Host: www, Value: username.github.io.
    ```

## Analytics and Monitoring

-   **Google Analytics:** "GA4 tracking (to be implemented)"
-   **Google Search Console:** "For SEO monitoring"
-   **AdSense Reports:** "Revenue and performance tracking"
-   **Uptime Monitoring:** "Service availability checks"

## Collaboration Guidelines

-   **Git Workflow:**
    -   "Use feature branches for new development"
    -   "Create pull requests for all changes"
    -   "Include tests for new functionality"
    -   "Update documentation with feature changes"
-   **Commit Messages:**
    -   **Format:** "type(scope): description"
    -   **Examples:**
        -   "feat(json): add syntax highlighting for errors"
        -   "fix(i18n): correct Japanese translation keys"
        -   "docs(readme): update installation instructions"
        -   "style(css): improve dark mode contrast"

## Testing Strategy

-   **Manual Testing:**
    -   "Test all features in both light and dark modes"
    -   "Verify functionality across all supported languages"
    -   "Check responsiveness on mobile and desktop"
    -   "Validate JSON parsing with various edge cases"
-   **Cross-Browser Testing:**
    -   "Chrome/Chromium (primary target)"
    -   "Firefox"
    -   "Safari (macOS and iOS)"
    -   "Edge"
    -   "Mobile browsers (Chrome Mobile, Safari Mobile)"

## Security Considerations

-   **Client-side:**
    -   "All JSON processing happens client-side (no server storage)"
    -   "No user data collection or storage"
    -   "CSP headers for XSS protection"
    -   "Sanitize all user input"
-   **Privacy:**
    -   "No tracking cookies beyond AdSense requirements"
    -   "No personal data collection"
    -   "Clear privacy policy (to be added)"
    -   "GDPR compliance for EU users"

## Quality Assurance

-   **Code Review Checklist:**
    -   "✅ Multilingual support implemented"
    -   "✅ Dark/light theme styles included"
    -   "✅ Mobile responsiveness verified"
    -   "✅ Accessibility standards met"
    -   "✅ Performance impact assessed"
    -   "✅ Error handling implemented"
    -   "✅ User feedback provided"

## Support and Maintenance

-   **User Feedback:**
    -   "GitHub Issues for bug reports and feature requests"
    -   "Social media monitoring for user mentions"
    -   "Analytics data for usage patterns"
-   **Regular Maintenance:**
    -   "Monthly dependency updates"
    -   "Quarterly feature additions"
    -   "Continuous SEO optimization"
    -   "Performance monitoring and optimization"

# Instructions for Gemini:
# This project is a multilingual developer tools website focusing on JSON processing
# with plans to expand to other developer utilities. When working on this project:
# 
# 1. Always maintain the existing architecture and coding patterns
# 2. Include multilingual support for any new features
# 3. Follow the established naming conventions and file structure
# 4. Test new features across all supported languages and themes
# 5. Prioritize performance and user experience in all implementations
# 6. Maintain the professional, developer-focused branding and design
# 7. Consider SEO impact of any content or structural changes
# 8. Ensure all new code follows accessibility best practices
