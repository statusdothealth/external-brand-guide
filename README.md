# Status.Health Brand and Style Guidelines

<img src="./assets/logo.png" alt="Status.Health Logo" width="160"/>

## Table of Contents

1. [Brand Overview](#brand-overview)
2. [Brand Elements](#brand-elements)
   - [Name Usage](#name-usage)
   - [Logo](#logo)
   - [Color Palette](#color-palette)
   - [Typography](#typography)
   - [Rainbow Elements](#rainbow-elements)
3. [Voice and Tone](#voice-and-tone)
   - [Brand Voice](#brand-voice)
   - [Tone Guidelines](#tone-guidelines)
   - [Language](#language)
   - [Taglines](#taglines)
4. [Design Elements](#design-elements)
   - [Buttons](#buttons)
   - [Cards](#cards)
   - [Navigation](#navigation)
   - [Layout](#layout)
5. [Accessibility](#accessibility)
6. [Content Guidelines](#content-guidelines)
7. [Contact](#contact)

## Brand Overview

Status.Health is a secure, privacy-focused platform designed to allow users to verify and share their STD testing status through a zero-knowledge proof system. The service enables individuals to confidentially verify their testing history without exposing sensitive medical information, while incentivizing regular testing through a gamified points system.

Our brand identity reflects our core values:
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

Our brand voice represents our personality and values in written form. It should be consistent across all communications.

#### Voice Attributes

- **Positive:** Focus on empowerment and solutions rather than fear or stigma
- **Inclusive:** Explicitly LGBTQ+ friendly and community-centered
- **Professional yet approachable:** Balance medical authority with warmth
- **Direct and clear:** Present information in straightforward language
- **Empowering:** Emphasize user autonomy and knowledge

#### Voice Examples

| ✅ DO | ❌ DON'T |
|-------|---------|
| "Regular testing helps build confidence in your sexual health" | "Get tested or risk dangerous infections" |
| "Our platform rewards you for making informed choices" | "Our platform will solve all your problems" |
| "We designed our verification system to protect your privacy" | "We use advanced technology that most people don't understand" |
| "Know your status—because confidence is the ultimate turn-on" | "Don't be irresponsible with your health" |

### Tone Guidelines

While our voice stays consistent, our tone may shift slightly depending on the context and medium. However, it should always remain within the parameters of our brand voice.

- **Website:** Informative and confident, with a focus on benefits and features
- **Email:** Friendly and direct, with clear calls to action
- **FAQs:** Straightforward and helpful, anticipating user questions
- **Error messages:** Empathetic and solution-oriented, never blaming the user
- **Legal/Privacy content:** Clear and transparent, avoiding unnecessary jargon

### Language

#### Words and Phrases to Use

- "Sexual health" instead of "sexual disease prevention"
- "Testing frequency" or "testing history" instead of "test results"
- "Privacy-preserving" or "zero-knowledge" instead of "hidden" or "secret"
- "Community" or "users" instead of "customers" or "clients"
- "Verify" or "verification" instead of "prove" or "proof"

#### Technical Terminology

When discussing technical aspects of our platform:

- Define terms clearly on first use
- Balance accuracy with accessibility
- Use analogies to explain complex concepts
- Avoid unnecessary jargon
- When using abbreviations, spell them out on first reference (e.g., "Zero-Knowledge Proofs (ZKPs)")

### Taglines

Use these established taglines to maintain brand consistency:

- "STD Tests Are Hot. Guesswork Is Not."
- "More Play, Less Delay"
- "be tested. be sexy. be rewarded. 🏳️‍🌈™"
- "Testing regularly leads to playing regularly."
- "With status.health, it's more hookups, less hangups."
- "Because your health should never be a gamble."

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

## Content Guidelines

### Structure

- Use clear, concise headings that describe the content
- Keep paragraphs short (3-5 sentences maximum)
- Use bulleted lists for unordered items
- Use numbered lists for sequential steps
- Lead with the most important information
- Create scannable content with descriptive section headings

### SEO Best Practices

Primary keywords to incorporate naturally:
- STD verification
- Sexual health verification
- Testing history
- Zero-knowledge proofs
- Privacy-preserving verification
- LGBTQ+ sexual health

### Inclusive Language

- Use gender-neutral language when addressing users collectively
- Avoid assumptions about gender or sexuality
- Use "partner" or "partners" rather than gendered terms
- Focus on testing frequency rather than results
- Avoid language that stigmatizes STIs or sexual behavior
- Frame privacy features as empowering rather than hiding or concealing

## Contact

For questions regarding these brand guidelines:

- Website: [stdverify.org](https://stdverify.org)
- Email: [support@stdverify.org](mailto:support@stdverify.org)
- Brand Guidelines Inquiries: [design@stdverify.org](mailto:design@stdverify.org)

© 2025 STD Verify, SPC. All rights reserved.