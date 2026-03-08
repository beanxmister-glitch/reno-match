# LeadGen Pro - Interior Design Lead Generation Website

## Project Overview

**Project Name:** RenoMatch (Lead Generation Website)
**Type:** Single-page lead capture website
**Core Functionality:** Connect homeowners with verified interior design firms through a lead capture form
**Target Users:** Homeowners in Singapore looking for interior designers

---

## UI/UX Specification

### Layout Structure

**Sections (top to bottom):**
1. **Navigation Bar** - Fixed, transparent → solid on scroll
2. **Hero Section** - Full viewport, headline + subtext + CTA
3. **How It Works** - 3-step process cards
4. **Why Choose Us** - Trust badges/features
5. **Portfolio Gallery** - Grid of renovation project images
6. **Lead Capture Form** - Multi-step form (property → budget → contact)
7. **Testimonials** - Google reviews carousel
8. **FAQ Accordion** - Common questions
9. **Footer** - Links, contact info

**Responsive Breakpoints:**
- Mobile: < 768px (single column)
- Tablet: 768px - 1024px (2 columns)
- Desktop: > 1024px (full layout)

### Visual Design

**Color Palette:**
- Primary: `#1a1a2e` (Deep navy)
- Secondary: `#16213e` (Dark blue)
- Accent: `#e94560` (Coral red)
- Accent Light: `#ff6b6b` (Soft coral)
- Background: `#0f0f1a` (Near black)
- Surface: `#1f1f3a` (Card background)
- Text Primary: `#ffffff`
- Text Secondary: `#a0a0b8`
- Success: `#4ade80`

**Typography:**
- Headings: "Playfair Display", serif (elegant, trustworthy)
- Body: "DM Sans", sans-serif (clean, modern)
- Sizes:
  - H1: 56px / 3.5rem
  - H2: 40px / 2.5rem
  - H3: 24px / 1.5rem
  - Body: 16px / 1rem
  - Small: 14px / 0.875rem

**Spacing System:**
- Section padding: 100px vertical
- Container max-width: 1200px
- Card padding: 32px
- Element gap: 24px

**Visual Effects:**
- Glassmorphism cards (backdrop-blur: 12px)
- Gradient overlays on images
- Smooth hover transitions (0.3s ease)
- Subtle parallax on hero
- Floating animations on key elements
- Glow effects on accent buttons

### Components

**1. Navbar**
- Logo (text-based)
- Nav links: How It Works, Portfolio, FAQ
- CTA button "Get Quotes"
- States: transparent (top), solid (scrolled)

**2. Hero**
- Large headline with gradient text
- Subheadline
- Primary CTA button with glow
- Decorative floating shapes

**3. Step Cards**
- Number badge
- Icon
- Title
- Description
- Hover: lift + glow

**4. Feature Cards**
- Icon in accent color
- Title
- Description
- Glassmorphism background

**5. Portfolio Grid**
- Image cards with overlay on hover
- Category labels (HDB, Condo, etc.)
- Lazy loading placeholder

**6. Multi-Step Form**
- Progress indicator (3 steps)
- Step 1: Property Type (radio cards)
- Step 2: Budget Range (slider/select)
- Step 3: Contact Info (name, phone, email)
- Animated transitions between steps
- Success state with confetti

**7. Testimonial Cards**
- Star rating
- Quote text
- Reviewer name
- Property type badge

**8. FAQ Accordion**
- Question with toggle icon
- Expandable answer
- Smooth height animation

---

## Functionality Specification

### Core Features

1. **Smooth Scroll Navigation** - Click nav links to scroll to sections
2. **Navbar State Change** - Transparent → solid on scroll (after 100px)
3. **Multi-Step Lead Form**
   - Step 1: Select property type (HDB, Condo, Landed, Commercial)
   - Step 2: Select budget range (S$0-30K through S$100K+)
   - Step 3: Enter name, phone, email
   - Validation on each step
   - Submit → show success message
4. **Portfolio Gallery** - Display sample renovation projects
5. **FAQ Accordion** - Expand/collapse answers
6. **Scroll Animations** - Elements fade in on scroll

### User Interactions

- **CTA Buttons**: Hover glow effect, click ripple
- **Form Steps**: Next/Back navigation, validation feedback
- **Cards**: Hover lift effect
- **FAQ**: Click to expand/collapse

### Form Data Handling

- Store in localStorage for demo
- Console.log the submitted data
- Show success confirmation

---

## Acceptance Criteria

1. ✅ Page loads without errors
2. ✅ All sections visible and properly styled
3. ✅ Navigation smooth scrolls to sections
4. ✅ Form progresses through all 3 steps
5. ✅ Form validates required fields
6. ✅ Form shows success message on submission
7. ✅ FAQ accordion expands/collapses
8. ✅ Responsive on mobile/tablet/desktop
9. ✅ Animations are smooth (60fps)
10. ✅ All fonts load correctly
