# Status.Health Community Brand Guidelines

<img src="./assets/logo.png" alt="Status.Health Logo" width="160"/>

## Table of Contents

1. [About Status.Health](#about-statushealth)
2. [Brand Elements](#brand-elements)
   - [Name Usage](#name-usage)
   - [Logo](#logo)
   - [Color Palette](#color-palette)
   - [Typography](#typography)
   - [Rainbow Elements](#rainbow-elements)
3. [Voice and Tone](#voice-and-tone)
   - [Brand Voice](#brand-voice)
   - [Community Communication](#community-communication)
   - [Inclusive Language](#inclusive-language)
   - [Key Messages](#key-messages)
4. [Design Elements](#design-elements)
   - [Buttons](#buttons)
   - [Cards](#cards)
   - [Navigation](#navigation)
   - [Layout](#layout)
5. [Accessibility](#accessibility)
6. [Contributing](#contributing)
7. [Community Resources](#community-resources)

## About Status.Health

Status.Health is an open, privacy-focused platform designed to allow users to verify and share their STD testing status through a zero-knowledge proof system. Our platform enables individuals to confidentially verify their testing history without exposing sensitive medical information, while incentivizing regular testing through a gamified points system.

Our community values:
- **Privacy**: Zero-knowledge proofs ensure medical data is never stored or shared
- **Community**: Explicitly LGBTQ+ friendly and community-centered
- **Empowerment**: Supporting user autonomy and informed choices
- **Transparency**: Clear communication about how our technology works
- **Inclusivity**: Creating a stigma-free approach to sexual health

## Brand Elements

### Name Usage

| Brand Name | Format | Usage |
|------------|--------|-------|
| **status.health** | Always lowercase | Product name; use when referring to the platform, app, or service |
| **STD Verify** | Proper case | Parent company name; use for corporate communications |

**Example Usage:**
- "status.health helps you privately share your verification status"
- "STD Verify is the company behind the status.health platform"

### Logo

Our logo consists of a distinctive circular emblem with a rainbow aura effect that reinforces the brand's connection to the LGBTQ+ community.

**Logo Usage Guidelines:**
- Always maintain the logo's circular shape
- Preserve the rainbow aura effect when possible
- Maintain adequate clear space around the logo (minimum 10px padding)
- Minimum size: 35px × 35px

**Logo Variations:**
- Primary Logo: Full color with rainbow aura for hero sections
- Navigation Logo: Smaller version with preserved rainbow effect
- Monochrome: For single-color applications when necessary

### Color Palette

#### Primary Colors

| Color Name | Hex Code | RGB | Usage |
|------------|----------|-----|-------|
| Brand Blue | `#4a90e2` | rgb(74, 144, 226) | Primary accent color, icons, interactive elements |
| Text Dark | `#333333` | rgb(51, 51, 51) | Primary text |
| Text Medium | `#555555` | rgb(85, 85, 85) | Secondary text |
| Text Light | `#777777` | rgb(119, 119, 119) | Tertiary text |
| Background Light | `#ffffff` | rgb(255, 255, 255) | Main background |
| Background Off-White | `#f8f8f8` | rgb(248, 248, 248) | Secondary background |

#### Rainbow Gradient

The signature rainbow gradient is a key brand element used for accents, buttons, and decorative elements:

```css
background: conic-gradient(
    rgba(255, 200, 200, 0.8), 
    rgba(255, 230, 200, 0.8), 
    rgba(255, 255, 200, 0.8), 
    rgba(200, 255, 200, 0.8), 
    rgba(200, 230, 255, 0.8), 
    rgba(220, 200, 255, 0.8), 
    rgba(255, 200, 230, 0.8),
    rgba(255, 200, 200, 0.8)
);
```

This gradient should be used for:
- Logo aura effects
- Button backgrounds
- Section underlines
- Feature card accents

### Typography

#### Font Families

- **Primary Font:** 'Inter', sans-serif
  - Used for all body text, headings, and UI elements
  - Weights: 300 (light), 400 (regular), 600 (semibold), 700 (bold)

- **Accent Font:** 'League Script', cursive
  - Used sparingly for special headings like "Coming Soon"

#### Type Scale

| Element | Font Size | Font Weight | Line Height | Color |
|---------|-----------|-------------|-------------|-------|
| h1 | 2.5rem | 700 | 1.2 | #333333 |
| h2 | 2.2rem | 600 | 1.3 | #333333 |
| h3 | 1.8rem | 600 | 1.3 | #333333 |
| h4 | 1.4rem | 600 | 1.4 | #333333 |
| Body Large | 1.2rem | 300 | 1.6 | #555555 |
| Body | 1rem | 300/400 | 1.6 | #555555 |
| Small | 0.9rem | 400 | 1.5 | #777777 |

#### Typography Rules

- Left-align text in most cases for better readability
- Center-align text for headlines and key messages on the homepage
- Limit paragraph width to 750px for optimal readability
- Use 300 weight for body text to maintain a light, modern feel
- Use 600 weight for headings rather than 700 to keep a softer appearance

### Rainbow Elements

#### Rainbow Underline

The rainbow underline is used to highlight section headings.

```css
.rainbow-underline {
  height: 3px;
  width: 100%;
  margin-bottom: 30px;
  background: linear-gradient(
    to right,
    rgba(255, 200, 200, 0.7), 
    rgba(255, 230, 200, 0.7), 
    rgba(255, 255, 200, 0.7), 
    rgba(200, 255, 200, 0.7), 
    rgba(200, 230, 255, 0.7), 
    rgba(220, 200, 255, 0.7), 
    rgba(255, 200, 230, 0.7)
  );
  filter: blur(1px);
  opacity: 0.7;
}
```

#### Logo Aura

The logo aura creates a rainbow halo effect around our logo.

```css
.aura-flow {
  position: absolute;
  width: 150%;
  height: 150%;
  top: -25%;
  left: -25%;
  background: conic-gradient(
    rgba(255, 200, 200, 0.8), 
    rgba(255, 230, 200, 0.8), 
    rgba(255, 255, 200, 0.8), 
    rgba(200, 255, 200, 0.8), 
    rgba(200, 230, 255, 0.8), 
    rgba(220, 200, 255, 0.8), 
    rgba(255, 200, 230, 0.8),
    rgba(255, 200, 200, 0.8)
  );
  opacity: 0.7;
  filter: blur(15px);
}
```

## Voice and Tone

### Brand Voice

Our community voice represents our shared values and should be consistent across all communications.

#### Voice Attributes

- **Positive:** Focus on empowerment and solutions rather than fear or stigma
- **Inclusive:** Explicitly LGBTQ+ friendly and community-centered
- **Approachable:** Welcoming to both technical and non-technical contributors
- **Direct and clear:** Present information in straightforward language
- **Empowering:** Emphasize user autonomy and knowledge-sharing

#### Voice Examples

| ✅ DO | ❌ DON'T |
|-------|---------|
| "Regular testing helps build confidence in your sexual health" | "Get tested or risk dangerous infections" |
| "Our platform rewards users for making informed choices" | "Our platform will solve all your problems" |
| "We designed our verification system to protect privacy" | "We use advanced technology that most people don't understand" |
| "Know your status—because confidence is the ultimate turn-on" | "Don't be irresponsible with your health" |
| "Let's collaborate to make this feature more accessible" | "This is the only correct way to implement this feature" |

### Community Communication

When communicating within the Status.Health community, our tone should be:

- **Inclusive**: Welcoming to everyone regardless of background or identity
- **Supportive**: Encouraging to new contributors and users
- **Educational**: Explaining concepts clearly without being condescending
- **Transparent**: Open about processes, decisions, and challenges
- **Constructive**: Providing helpful feedback and solutions

### Inclusive Language

Our community values inclusive language that respects all individuals:

- "Sexual health" instead of "sexual disease prevention"
- "Testing frequency" or "testing history" instead of "test results"
- "Privacy-preserving" or "zero-knowledge" instead of "hidden" or "secret"
- "Community members" or "users" instead of "customers" or "clients"
- "Verify" or "verification" instead of "prove" or "proof"

### Technical Communication

When discussing technical aspects of our platform:

- Define terms clearly on first use
- Balance accuracy with accessibility
- Use analogies to explain complex concepts
- Avoid unnecessary jargon
- When using abbreviations, spell them out on first reference (e.g., "Zero-Knowledge Proofs (ZKPs)")
- Share knowledge generously but respectfully

### Key Messages

Our community emphasizes these core messages:

- Privacy and security are fundamental rights in healthcare
- Technology should empower individuals to take control of their health
- Breaking stigma around STD testing creates healthier communities
- Open-source collaboration leads to better, more accessible solutions
- Inclusive design benefits everyone

## Design Elements

### Buttons

#### Primary Button

Used for main call-to-action elements, featuring our signature rainbow gradient.

```css
.primary-button {
  display: inline-block;
  background: linear-gradient(45deg, rgba(255, 182, 193, 0.7), rgba(255, 222, 173, 0.7), rgba(255, 255, 173, 0.7), rgba(173, 255, 182, 0.7), rgba(173, 216, 255, 0.7), rgba(216, 173, 255, 0.7));
  color: #333;
  border: none;
  padding: 12px 30px;
  border-radius: 30px;
  font-weight: 600;
  font-size: 1rem;
  cursor: pointer;
  text-decoration: none;
  transition: transform 0.2s, box-shadow 0.2s;
  box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
}
```

#### Secondary Button

Used for less prominent actions or alternatives to the primary action.

```css
.secondary-button {
  display: inline-block;
  background-color: white;
  color: #333;
  border: 1px solid #ddd;
  padding: 12px 30px;
  border-radius: 30px;
  font-weight: 600;
  font-size: 1rem;
  text-decoration: none;
  transition: all 0.2s;
  box-shadow: 0 2px 10px rgba(0, 0, 0, 0.05);
}
```

### Cards

#### Feature Card

Highlight key product features with a distinctive left rainbow border.

```css
.feature-card {
  background: #fff;
  border-radius: 12px;
  padding: 25px;
  box-shadow: 0 4px 15px rgba(0, 0, 0, 0.06);
  position: relative;
  overflow: hidden;
}

.feature-card::before {
  content: '';
  position: absolute;
  top: 0;
  left: 0;
  width: 5px;
  height: 100%;
  background: linear-gradient(
    to bottom, 
    rgba(255, 200, 200, 0.7), 
    rgba(255, 230, 200, 0.7), 
    rgba(255, 255, 200, 0.7), 
    rgba(200, 255, 200, 0.7), 
    rgba(200, 230, 255, 0.7), 
    rgba(220, 200, 255, 0.7), 
    rgba(255, 200, 230, 0.7)
  );
  opacity: 0.8;
}
```

### Navigation

The navigation bar is fixed at the top of every page with a subtle shadow effect.

**Key Specifications:**
- Height: 70px
- Background: white
- Box shadow: `0 2px 10px rgba(0,0,0,0.1)`
- Z-index: 1000

**Structure:**
1. Left section: Logo + site name + dropdown menus
2. Right section: Call-to-action button + optional contact link
3. Mobile: Hamburger menu that expands to full-height side menu

### Layout

- **Container Width:** 900px maximum
- **Column System:** Flexbox and CSS Grid
- **Card Grid:** `grid-template-columns: repeat(auto-fit, minmax(280px, 1fr))`
- **Spacing System:** Consistent spacing with 5px, 10px, 15px, 25px, and 40px increments

**Responsive Breakpoints:**
- Mobile: < 480px
- Tablet Small: < 768px
- Tablet Large: < 900px
- Desktop: > 900px

## Accessibility

Status.Health is committed to WCAG 2.1 AA compliance. All digital products should:

- Use semantic HTML elements for proper document structure
- Maintain a minimum contrast ratio of 4.5:1 for normal text and 3:1 for large text
- Ensure all interactive elements have visible focus states
- Provide text alternatives for non-text content
- Support keyboard navigation for all functionality
- Respect user preferences with the `prefers-reduced-motion` media query

## Accessibility

Status.Health is committed to creating an accessible platform for all users. We follow WCAG 2.1 AA standards and encourage the community to help maintain these practices:

- Use semantic HTML elements for proper document structure
- Maintain a minimum contrast ratio of 4.5:1 for normal text and 3:1 for large text
- Ensure all interactive elements have visible focus states
- Provide text alternatives for non-text content
- Support keyboard navigation for all functionality
- Respect user preferences with the `prefers-reduced-motion` media query

### Inclusive Communication

- Use gender-neutral language when addressing users collectively
- Avoid assumptions about gender or sexuality
- Use "partner" or "partners" rather than gendered terms
- Focus on testing frequency rather than results
- Avoid language that stigmatizes STIs or sexual behavior
- Frame privacy features as empowering rather than hiding or concealing
- Consider international audiences and avoid US-centric terminology

### Community Standards

When contributing to Status.Health, remember:

- Be respectful and considerate in all communications
- Provide constructive feedback
- Focus on solutions rather than problems
- Help create a safe space for all community members
- Follow our [Code of Conduct](CODE_OF_CONDUCT.md)

## Contributing

We welcome community contributions to Status.Health! Here's how you can get involved:

### Code Contributions
- Fork this repository
- Create a feature branch (`git checkout -b feature/amazing-feature`)
- Commit your changes (`git commit -m 'Add some amazing feature'`)
- Push to the branch (`git push origin feature/amazing-feature`)
- Open a Pull Request

### Design Contributions
- Follow the brand guidelines when creating designs
- Share design concepts or improvements in the Discussions section
- Consider accessibility in all designs

### Documentation
- Help improve these guidelines
- Create tutorials or guides for using Status.Health
- Translate documentation into other languages

## Community Resources

- **Website**: [stdverify.org](https://stdverify.org)
- **GitHub Repository**: [github.com/stdverify/status.health](https://github.com/stdverify/status.health)
- **Community Forum**: [github.com/stdverify/status.health/discussions](https://github.com/stdverify/status.health/discussions)
- **Issue Tracker**: [github.com/stdverify/status.health/issues](https://github.com/stdverify/status.health/issues)

---

Released under MIT License. See [LICENSE](LICENSE) for details.

Status.Health is a project maintained by STD Verify, SPC.