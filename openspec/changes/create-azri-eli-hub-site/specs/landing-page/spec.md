## ADDED Requirements

### Requirement: Landing Page Structure
The landing page SHALL display a single-page Hebrew RTL layout with logo, hero section, feature descriptions, and call-to-action button.

#### Scenario: Page loads successfully
- **WHEN** a user visits the landing page
- **THEN** they see the עזרי-אלי logo at the top
- **AND** the hero tagline "הבית של הקהילה הדתית במתחם עזריאלי. מידע, חיזוק וחיבור בין המגדלים."
- **AND** two feature cards describing the bulletin board and WhatsApp group
- **AND** a CTA button for accessing resources

### Requirement: Feature Cards Display
The page SHALL display two feature cards describing available community resources.

#### Scenario: Bulletin board feature shown
- **WHEN** the page renders
- **THEN** a card with 📢 icon displays "לוח מודעות דיגיטלי"
- **AND** describes "עדכונים שוטפים על מניינים, שיעורים וחדשות המתחם"

#### Scenario: WhatsApp group feature shown
- **WHEN** the page renders
- **THEN** a card with 📱 icon displays "קבוצת WhatsApp שקטה"
- **AND** describes "כל מה שחשוב לדעת, בלי הודעות מיותרות (רק אנחנו מפרסמים)"

### Requirement: Social Sharing Meta Tags
The page SHALL include OpenGraph meta tags for professional link previews on WhatsApp and social media.

#### Scenario: WhatsApp link preview
- **WHEN** a user shares the page URL on WhatsApp
- **THEN** the preview shows title "עזרי-אלי"
- **AND** description "עזרי-אלי: קבוצת עדכונים שקטה ולוח מודעות לעובדים דתיים במתחם עזריאלי, מידטאון והסביבה. מניינים, כשרות וקהילה."

### Requirement: Mobile Responsive Design
The page SHALL be fully responsive and display correctly on mobile devices.

#### Scenario: Mobile viewport
- **WHEN** viewing on a mobile device
- **THEN** the layout adapts to the screen width
- **AND** all content remains readable and accessible
