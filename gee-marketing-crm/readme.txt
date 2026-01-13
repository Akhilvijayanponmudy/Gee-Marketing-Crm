=== CRM Marketing, Mail & Analytics for WooCommerce ===
Contributors: geestacklabs
Tags: crm, marketing, email, analytics, woocommerce, email-marketing, customer-relationship-management, segmentation, campaigns
Requires at least: 5.0
Tested up to: 6.9
Stable tag: 1.0.0
Requires PHP: 7.4
License: GPLv2 or later
License URI: https://www.gnu.org/licenses/gpl-2.0.html
Network: false

Customer Relationship Management, Email campaigns, contact segmentation, analytics and marketing for your Woo store—with easy form integration.

== Description ==

CRM Marketing, Mail & Analytics for Woo is a comprehensive WordPress plugin that provides powerful customer relationship management, email marketing campaigns, contact segmentation, and analytics for WooCommerce stores.

This plugin helps you build and maintain strong relationships with your customers through targeted email campaigns, intelligent contact segmentation, and detailed analytics. Perfect for WooCommerce store owners who want to take their marketing to the next level.

= Key Benefits =

* **Complete CRM Solution** - Manage all your customer contacts in one centralized location
* **Email Marketing** - Create and send beautiful, targeted email campaigns to your customers
* **Smart Segmentation** - Segment contacts by tags, purchase history, and custom conditions
* **GDPR Compliant** - Built-in marketing consent management and secure unsubscribe functionality
* **Easy Integration** - Simple REST API for integrating with contact forms and other plugins
* **WooCommerce Sync** - Automatically sync customer data from your WooCommerce store
* **Analytics Dashboard** - Track campaign performance and contact growth with visual charts
* **Template Library** - 6 ready-to-use email templates to get you started quickly

== Features ==

* Contact Management - Manage all your customer contacts in one place
* Email Campaigns - Create and send targeted email campaigns
* Email Templates - Beautiful, customizable email templates with visual editor
* Contact Segmentation - Segment contacts by tags, purchase history, and more
* Analytics Dashboard - Track campaign performance and contact growth
* Marketing Consent - GDPR-compliant marketing consent management
* Secure Unsubscribe - Token-based secure unsubscribe links
* Form Integration - Easy integration with contact forms via REST API
* WooCommerce Integration - Automatic sync with WooCommerce customers
* Batch Email Processing - Queue-based email sending for heavy loads
* Predefined Templates - 6 ready-to-use email templates

== Installation ==

1. Upload the plugin files to the `/wp-content/plugins/crm-marketing-woo` directory, or install the plugin through the WordPress plugins screen directly.
2. Activate the plugin through the 'Plugins' screen in WordPress.
3. Navigate to 'Gee Woo CRM' in your WordPress admin menu to access the dashboard.
4. Go to Settings to configure API keys, email templates, and other options.
5. Start by syncing your WooCommerce contacts or importing contacts via CSV.
6. Create email templates and campaigns to begin marketing to your customers.

= Requirements =

* WordPress 5.0 or higher
* PHP 7.4 or higher
* WooCommerce (recommended for full functionality)

== Frequently Asked Questions ==

= Is this plugin compatible with WooCommerce? =

Yes, this plugin is designed specifically for WooCommerce stores and automatically syncs customer data from your WooCommerce orders and customer accounts.

= Does this plugin support GDPR compliance? =

Yes, the plugin includes marketing consent management and secure token-based unsubscribe functionality to help with GDPR compliance. You can track consent dates and manage opt-in/opt-out preferences.

= Can I customize email templates? =

Yes, the plugin includes a visual editor (WordPress TinyMCE) for creating and customizing email templates with full support for HTML, variables, and styling. You can also use predefined templates as starting points.

= How does the email sending work for large campaigns? =

The plugin uses a queue-based batch processing system that sends emails in batches via WP Cron, ensuring reliable delivery even for large contact lists. This prevents server timeouts and ensures emails are sent efficiently.

= Can I integrate this with my contact forms? =

Yes, the plugin provides REST API endpoints and ready-to-use JavaScript code snippets for easy integration with any contact form, including Contact Form 7, WPForms, and custom forms.

= What email sending method does this plugin use? =

The plugin uses WordPress's built-in `wp_mail()` function, which uses your WordPress site's configured email settings. For better deliverability, we recommend using an SMTP plugin.

= Can I segment contacts by purchase history? =

Yes, the plugin allows you to create segments based on various criteria including tags, purchase history, contact source, and custom conditions using AND/OR logic.

= Is there a limit on the number of contacts or campaigns? =

No, there are no hard limits. The plugin is designed to handle large contact lists and multiple campaigns efficiently using batch processing.

= Can I import contacts from a CSV file? =

Yes, the plugin includes a CSV import feature that allows you to import contacts with their names, emails, and other data.

= How do I unsubscribe contacts? =

Contacts can unsubscribe using secure token-based links in email campaigns. You can also manually update marketing consent in the contact management interface.

== Screenshots ==

1. Dashboard with analytics and statistics - View your contact growth, campaign performance, and key metrics at a glance
2. Contact management interface - Manage all your contacts, view their details, assign tags, and update marketing consent
3. Email campaign creation - Create targeted email campaigns with subject lines, content, and recipient selection
4. Visual email template editor - Design beautiful email templates using the WordPress visual editor with variable support
5. Contact segmentation - Create smart segments using tags, purchase history, and custom conditions
6. Settings and form integration - Configure API keys, email settings, and get code snippets for form integration
7. Tags and segments management - Organize your contacts with tags and create dynamic segments
8. Analytics dashboard - Track campaign opens, clicks, and contact growth with visual charts

== Changelog ==

= 1.0.0 =
* Initial release
* Contact management system with WooCommerce integration
* Email campaign creation and sending with queue-based batch processing
* Visual email template editor with WordPress TinyMCE editor support
* Contact segmentation by tags, purchase history, and custom conditions with AND/OR logic
* Analytics dashboard with charts and statistics for campaigns and contacts
* Marketing consent management for GDPR compliance with consent date tracking
* Secure token-based unsubscribe links in all email campaigns
* REST API endpoints for form integration (/wp-json/gee-crm/v1/subscribe and /unsubscribe)
* Batch email processing queue system via WP Cron for reliable delivery
* 6 predefined email templates (Marketing, Thank You, Product Launch, Flash Sale, Product Recommendation, Abandoned Cart)
* Tag and segment management with visual interface
* Contact import via CSV with field mapping
* Test email functionality for previewing campaigns
* WooCommerce customer and order synchronization
* API key generation and management for secure form integration
* Email template variable replacement (first_name, last_name, full_name, email, site_name)
* Campaign logging and tracking for opens and clicks
* Responsive admin interface with modern UI

== Upgrade Notice ==

= 1.0.0 =
Initial release of CRM Marketing, Mail & Analytics for Woo.

