# Plotora — website build prompt

Build a polished, responsive real-estate discovery platform named **Plotora** for buyers, renters, property dealers, and admins. The product should feel trustworthy, calm, modern, and focused on property discovery. Use a refined forest-green and warm ivory palette with a restrained lime accent, excellent mobile layouts, accessible controls, and realistic Indian property examples and INR formatting.

## Main website
- Create a landing page with a prominent property search, Buy/Rent intent, location, category filters, featured/latest properties, verified dealers, and a “Post Your Requirement” call to action.
- Support residential, commercial, industrial, and agricultural properties, plus an Investment Zone for industrial/commercial investment, agricultural land, large parcels, and upcoming development areas.
- Property search filters: location, property type, buy/rent, price/budget, area, road width, road type, facing/direction, and residential/industrial zone.
- Property detail pages should include photos/video, city, price, map/location, total area, road connectivity, description, nearby places, and clear inquiry/contact actions.
- Include dealer profiles with agency name, photo, office address, mobile, RERA registration, experience, specialties, active listings, and customer reviews. Mark verification status clearly.
- Buyer requirement form captures location, property type, area, budget, road/facing preferences, and buy/rent intent.

## Accounts and dashboards
- Implement real signup/login, role-based access for buyer, dealer, and admin, secure sessions, validation, password reset, and logout.
- Dealers can create/edit/archive their listings and respond to buyer inquiries. Admins can manage users, dealers, verification, properties, inquiries, and buyer requirements.
- Buyers and dealers can see relevant inquiry conversations in their dashboards. Provide WhatsApp inquiry links as well as an in-site inquiry flow. Use an admin-configured WhatsApp number and prefilled property-specific messages.
- No checkout or online payment; the site is for inquiries and contact only.

## Engineering requirements
- Use a production-ready frontend and backend with persistent database storage, image upload, map integration, server-side validation, authorization checks, spam/rate limiting, and secure handling of personal data.
- Seed tasteful sample listings and clearly distinguish sample data from verified real inventory.
- Include loading, empty, error, and success states; mobile-first responsive behavior; keyboard-accessible dialogs and forms; SEO metadata; and deployment instructions with environment variables.
- Do not pretend browser-local demo authentication is secure or production-ready. Document any external services and credentials that the owner must configure.

Deliver complete, runnable source code, a database schema/migrations, setup instructions, and tests for authentication, listing permissions, search filters, and inquiry submission.