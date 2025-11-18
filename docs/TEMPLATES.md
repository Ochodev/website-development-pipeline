# 🎨 Website Development Templates

## Fitness Website Template Strategy

With 4 fitness websites in the pipeline (Big Day Fitness, ADAPT Training, BridgeFit, Create Fitness), we have an opportunity to create reusable components and templates.

## Common Fitness Website Components

### Hero Section
```jsx
// Engaging hero with CTA for gym membership
- Background video or dynamic imagery
- Compelling headline
- Subheadline with value proposition
- Primary CTA (Free Trial, Book Class, Get Started)
- Secondary CTA (Learn More, View Programs)
- Trust indicators (years in business, members served)
```

### Programs/Services Showcase
```jsx
// Grid or card layout for training programs
- Program name and category
- Brief description
- Key benefits (3-5 bullet points)
- Pricing information
- CTA button
- Testimonial snippet
- Before/after photos (where applicable)
```

### Class Schedule Display
```jsx
// Interactive schedule component
- Weekly calendar view
- Filter by class type
- Filter by instructor
- Filter by time/location
- Quick booking integration
- Real-time availability
- Mobile-friendly swipe navigation
```

### Trainer/Team Profiles
```jsx
// Bio cards for trainers
- Professional photo
- Name and title
- Specialties/certifications
- Brief bio
- Contact/social links
- Classes taught
- Booking link
```

### Pricing/Membership Section
```jsx
// Clear pricing tiers
- 3-tier structure (Starter, Standard, Premium)
- Feature comparison table
- Monthly vs. annual pricing
- Most popular highlight
- CTA for each tier
- FAQ section
- Money-back guarantee badge
```

### Testimonials Component
```jsx
// Social proof section
- Rotating testimonial carousel
- Client photo/name
- Star rating
- Quote
- Transformation story
- Video testimonials option
- Link to success stories page
```

### Contact/Location Section
```jsx
// Location and contact information
- Google Maps integration
- Address and hours
- Contact form
- Phone/email
- Social media links
- Parking information
- Public transit details
```

### Member Portal
```jsx
// If required - member dashboard
- Login/registration
- Class booking
- Schedule viewing
- Payment history
- Profile management
- Progress tracking
- Community features
```

---

## Agency Website Template (76x.ai)

### Components for Agency Site

#### Services Showcase
```jsx
// Service offering cards
- Service icon/illustration
- Service name
- Brief description
- Key deliverables
- Pricing indicator
- CTA to learn more
- Case study link
```

#### Portfolio Grid
```jsx
// Project showcase
- Project thumbnail
- Client name
- Project type/category
- Brief description
- Tech stack used
- Results/metrics
- View case study CTA
- Hover effects
```

#### Case Study Template
```jsx
// Detailed project case study
- Client overview
- Challenge/problem
- Solution approach
- Implementation details
- Tech stack
- Results and metrics
- Testimonial
- Screenshots/demos
- Call to action
```

#### Lead Capture Forms
```jsx
// Strategic form placement
- Above the fold option
- Exit intent popup
- Bottom of services pages
- Contact page form
- Fields: Name, Email, Company, Project Type, Budget, Message
- Progress indicators for multi-step
- Validation and error handling
```

---

## Personal Brand Website Template

### Components for Education Platform

#### Course Card
```jsx
// Course listing component
- Course thumbnail/cover
- Course title
- Instructor name/photo
- Brief description
- Duration and format
- Skill level
- Price
- Student count
- Rating stars
- CTA button
- Preview/demo option
```

#### Prompt Vault Browser
```jsx
// Searchable prompt library
- Search bar with filters
- Category tags
- Difficulty indicator
- Copy button
- Favorite/bookmark
- Rating system
- Use case examples
- Free vs. Premium badge
- Prompt details modal
```

#### Student Dashboard
```jsx
// Learning portal
- Progress overview
- Enrolled courses
- Continue learning section
- Certificates earned
- Bookmarked resources
- Discussion access
- Profile settings
- Billing information
```

#### Course Player
```jsx
// Video course interface
- Video player with controls
- Progress tracking
- Next/previous navigation
- Transcript toggle
- Notes section
- Resources download
- Discussion/comments
- Mark as complete
```

---

## Universal Components

### Navigation
```jsx
// Responsive header
- Logo
- Main navigation items
- Mobile hamburger menu
- CTA button (highlighted)
- Search (optional)
- User account/login
- Shopping cart (if e-commerce)
- Sticky on scroll
```

### Footer
```jsx
// Comprehensive footer
- Logo and tagline
- Quick links
- Services/Products
- Resources
- Contact information
- Social media icons
- Newsletter signup
- Legal links (Privacy, Terms)
- Copyright notice
```

### Newsletter Signup
```jsx
// Email capture component
- Compelling headline
- Value proposition
- Email input field
- Subscribe button
- Privacy notice
- Success message
- Integration with email service
```

### FAQ Section
```jsx
// Accordion-style FAQ
- Question categories
- Expandable answers
- Search functionality
- Contact CTA
- Related links
```

### Blog Post Template
```jsx
// Article layout
- Hero image
- Title and subtitle
- Author info and date
- Estimated read time
- Category tags
- Article content (formatted)
- Table of contents (for long posts)
- Related posts
- Social sharing
- Comments section
- CTA at end
```

### Contact Form
```jsx
// Standard contact form
- Name field
- Email field
- Phone (optional)
- Subject/Topic
- Message textarea
- File upload (optional)
- Submit button
- Success/error states
- Spam protection
```

---

## Page Templates

### Homepage Template
```jsx
Structure:
1. Hero section with primary CTA
2. Social proof (logos, testimonials)
3. Services/offerings overview
4. Feature highlights (3-column grid)
5. About/story section
6. Portfolio/case studies preview
7. Testimonials carousel
8. Blog posts preview
9. CTA section
10. Newsletter signup
11. Footer
```

### About Page Template
```jsx
Structure:
1. Hero with team photo
2. Mission/vision statement
3. Story/history
4. Values section
5. Team member grid
6. Achievements/milestones
7. Certifications/awards
8. CTA section
```

### Services Page Template
```jsx
Structure:
1. Hero with services overview
2. Service categories
3. Detailed service cards
4. Process/approach section
5. Pricing information
6. FAQ section
7. Case studies
8. Testimonials
9. CTA section
```

### Contact Page Template
```jsx
Structure:
1. Hero with headline
2. Contact form (prominent)
3. Contact information
4. Location map
5. Business hours
6. Social media links
7. FAQ section
```

---

## Design System Elements

### Color Palette Template
```css
/* Primary Brand Colors */
--primary: #[hex];
--primary-dark: #[hex];
--primary-light: #[hex];

/* Secondary Colors */
--secondary: #[hex];
--accent: #[hex];

/* Neutral Colors */
--gray-50: #f9fafb;
--gray-100: #f3f4f6;
--gray-200: #e5e7eb;
--gray-300: #d1d5db;
--gray-400: #9ca3af;
--gray-500: #6b7280;
--gray-600: #4b5563;
--gray-700: #374151;
--gray-800: #1f2937;
--gray-900: #111827;

/* Semantic Colors */
--success: #10b981;
--warning: #f59e0b;
--error: #ef4444;
--info: #3b82f6;
```

### Typography Scale
```css
/* Font Families */
--font-heading: 'Inter', sans-serif;
--font-body: 'Inter', sans-serif;
--font-mono: 'Fira Code', monospace;

/* Font Sizes */
--text-xs: 0.75rem;    /* 12px */
--text-sm: 0.875rem;   /* 14px */
--text-base: 1rem;     /* 16px */
--text-lg: 1.125rem;   /* 18px */
--text-xl: 1.25rem;    /* 20px */
--text-2xl: 1.5rem;    /* 24px */
--text-3xl: 1.875rem;  /* 30px */
--text-4xl: 2.25rem;   /* 36px */
--text-5xl: 3rem;      /* 48px */
--text-6xl: 3.75rem;   /* 60px */
```

### Spacing Scale
```css
/* Tailwind-inspired spacing */
--space-1: 0.25rem;   /* 4px */
--space-2: 0.5rem;    /* 8px */
--space-3: 0.75rem;   /* 12px */
--space-4: 1rem;      /* 16px */
--space-6: 1.5rem;    /* 24px */
--space-8: 2rem;      /* 32px */
--space-12: 3rem;     /* 48px */
--space-16: 4rem;     /* 64px */
--space-24: 6rem;     /* 96px */
```

---

## Animation Patterns

### Page Transitions
```jsx
// Framer Motion variants
const fadeIn = {
  initial: { opacity: 0 },
  animate: { opacity: 1 },
  exit: { opacity: 0 }
};

const slideUp = {
  initial: { opacity: 0, y: 20 },
  animate: { opacity: 1, y: 0 },
  transition: { duration: 0.6 }
};

const stagger = {
  animate: {
    transition: {
      staggerChildren: 0.1
    }
  }
};
```

### Button States
```css
/* Button hover and active states */
.btn {
  transition: all 0.2s ease;
}

.btn:hover {
  transform: translateY(-2px);
  box-shadow: 0 10px 20px rgba(0,0,0,0.1);
}

.btn:active {
  transform: translateY(0);
}
```

---

## Integration Patterns

### Email Marketing
```jsx
// ConvertKit/Mailchimp integration
- Newsletter signup forms
- Automated welcome sequence
- Segment subscribers by interest
- Course enrollment emails
- Abandoned cart recovery
- Re-engagement campaigns
```

### Payment Processing
```jsx
// Stripe integration
- One-time payments
- Subscription billing
- Payment links
- Checkout sessions
- Customer portal
- Invoice generation
- Refund handling
```

### Booking Systems
```jsx
// Class/appointment booking
- Mindbody API integration
- Zen Planner integration
- Custom booking system
- Calendar synchronization
- Email confirmations
- Reminder notifications
- Cancellation handling
```

---

## Reusability Strategy

### Create Component Library
1. Build shared component repository
2. Use Storybook for documentation
3. Version components properly
4. Share across projects
5. Maintain design consistency

### Template Projects
1. Create fitness website starter
2. Create agency website starter
3. Create education platform starter
4. Include common integrations
5. Document customization process

### Design Systems
1. Maintain Figma design system
2. Sync with code components
3. Document usage guidelines
4. Version control designs
5. Share with team/clients

---

*Last Updated: November 18, 2025*
