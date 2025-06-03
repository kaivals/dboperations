MYLittle 
 
 
 1. CLIENT ADMIN SIDE
Login to Admin Dashboard
→ Client logs into the admin panel via secure credentials.

Create Portal (e.g., trucks.com, bikes.com)
→ Admin sets up multiple classified portals with custom branding and domain mapping.

Add Dynamic Filters for Each Portal
→ Admin defines filter fields (e.g., Brand, KM Driven, Fuel Type) specific to the product type.
→ Admin chooses input types: Text, Dropdown, Checkbox, Range Slider.
→ Admin sets whether filters are Required or Optional.
→ Admin adds selectable options for dropdown/checkbox fields.

Create Subscription Plans
→ Plans: Basic, Premium, Elite.
→ Define upload limits, listing visibility level, and highlight status.
→ Example: Elite = unlimited uploads, top visibility, highlighted products.

Add & Manage Dealers
→ Assign dealer to specific portal (e.g., dealer.trucks.com).
→ Assign subscription plan to each dealer.
→ View dealer statistics: upload usage, active listings, rejected listings.
→ Enable/Disable dealer or specific listings.
→ Monitor dealer activity in real time.

🧑‍🔧 2. DEALER SIDE
Dealer Login
→ Dealer logs in via their assigned portal (e.g., dealer.trucks.com).
→ Authenticated to only access their own listings.

View Dealer Dashboard
→ Displays portal name, current plan, upload quota used (e.g., 12/50).
→ Option to upgrade plan (via request or auto-pay).

Sell Product – Dynamic Upload Form
→ Form generated based on client-defined filters.
→ Example Fields:

Brand: Text – Required

Fuel Type: Dropdown – Required

KM Driven: Range – Required

Features: Checkbox – Optional

Price: Range – Required

Description: Textarea – Required

Images: Multiple Uploads – Required
→ Dealer must fill all required fields before submission.

Image Upload Handling
→ Preview thumbnails before upload.
→ Support for JPG, PNG with file size restrictions.
→ Drag-and-drop or multi-select supported.

Submit Product Listing
→ Data stored in DB, images stored on server/cloud.
→ Product marked “Pending” (if moderation enabled).
→ Listing becomes visible upon approval.

Manage Product Listings
→ View all listings in a table: Product Name, Status, Views, Leads, Actions.
→ Edit, delete, or re-upload rejected listings.
→ Filter listings by status: Active, Pending, Rejected.

Subscription Management
→ Dealer sees current plan, remaining upload limit.
→ Upgrade plan if needed (via admin approval or payment).

Optional Features
→ Track listing views or buyer inquiries.
→ Auto-expire products after X days.
→ Dashboard graphs showing performance over time.

🌍 3. PUBLIC USER (BUYER) SIDE
Visit Portal (e.g., trucks.com)
→ Users land on a fast, responsive product listing site.

Dynamic Filter Sidebar
→ Filters generated from client-defined fields (e.g., Brand, Price, Fuel Type).
→ Users can search using:

Text inputs

Dropdowns (e.g., Brand, Fuel Type)

Range sliders (e.g., Price, KM Driven)

Checkboxes (e.g., Features)

Search Results Sorted by Priority
→ Elite listings shown at top → Premium → Basic.
→ Only listings matching filters are shown.
→ Instant filtering without page reload (AJAX/live updates).

View Product Details
→ Shows: Product title, specs, features, price, images, and dealer contact.
→ Buyers can contact dealer (via call/email/form submission).

Mobile-Friendly UI
→ Fully responsive on mobile, tablet, and desktop.
→ Lazy-loaded images, clean design for faster browsing.
