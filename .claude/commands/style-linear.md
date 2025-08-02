When redesigning $ARGUMENTS, follow this Linear-inspired design system:

**Core Design Principles:**
- Minimize visual noise by avoiding unnecessary decorative elements, heavy borders, and card-style containers
- Use subtle backgrounds and borders instead of prominent visual containers
- Prioritize content hierarchy over visual embellishment
- Align all elements (icons, labels, interactive components) to consistent grid systems
- Use spacing patterns of 2px, 4px, 8px, 12px, 16px, 24px for consistent rhythm
- Apply neutral grays for chrome elements, reserving color for status and actions only
- Use font weights consistently: 400 (normal), 500 (medium), 600 (semibold)
- Keep UI text sizes readable: 12px, 13px, 14px for interface elements

**Technical Requirements:**
- Maintain WCAG 2.1 AA contrast ratios for accessibility
- Provide clear focus indicators for keyboard navigation
- Use semantic HTML with proper ARIA labels
- Ensure touch targets are minimum 44px
- Support screen readers with descriptive text
- Implement subtle contrast variations for light/dark mode support
- Code in TypeScript when creating React components

Create a redesigned $ARGUMENTS that users "feel after a few minutes" through reduced visual noise and precise alignment rather than flashy visual effects. Focus on content-first design with purposeful, minimal styling.
