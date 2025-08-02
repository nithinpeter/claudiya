When redesigning $ARGUMENTS, follow this Stripe-inspired design system:

**Core Design Principles**
- Balance clarity with elegance — refined typography, and subtle motion to guide attention without overwhelming
- Lightweight visual framing — avoid heavy borders; rely on shadow, spacing, and color shifts for structure
- Emphasize hierarchy through scale and weight rather than decorative separation
- Use a consistent vertical rhythm with spacing tokens: 4px, 8px, 12px, 16px, 24px, 32px
- Typography is central — pair clean sans-serif text with distinct weight steps (400, 500, 600) and large enough line height for readability
- Reserve vibrant color for key moments — actions, highlights, and data visualizations; keep interface chrome in refined neutrals
- Integrate subtle animations — transitions of 150–250ms to convey responsiveness and polish

**Technical Requirements**
- Maintain WCAG 2.1 AA accessibility for color and contrast
- Include clear, visible focus indicators for keyboard navigation, blending seamlessly with the brand palette
- Use semantic HTML and descriptive ARIA attributes for screen reader compatibility
- Ensure minimum 44px touch targets for interactive elements
- Design for light and dark modes with thoughtful color mapping, avoiding harsh inversions
- Implement fluid responsiveness so layouts scale naturally across devices

**Experience Goals**

The redesign should “feel premium within seconds, and intuitive within minutes”, achieved through:
- A content-first layout where information naturally draws the eye
- Polished motion that feels intentional, not decorative
- Consistent alignment and spacing that quietly communicates quality
- A cohesive visual identity that feels branded without overpowering the content
