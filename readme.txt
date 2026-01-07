=== Hamotech Umami Analytics ===
Contributors: hamotechsolutions
Tags: analytics, umami, privacy, tracking, events
Requires at least: 6.0
Tested up to: 6.7
Requires PHP: 7.4
Stable tag: 1.0.0
License: GPLv2 or later
License URI: https://www.gnu.org/licenses/gpl-2.0.html

Professional Umami Analytics integration for WordPress with advanced event tracking, enhanced privacy controls, and comprehensive analytics features.

== Description ==

Hamotech Umami Analytics is a powerful WordPress plugin that seamlessly integrates Umami Analytics into your website. Built by Hamotech Solutions, this plugin goes beyond basic pageview tracking to provide comprehensive insights into user behavior while respecting privacy.

= Why Choose Hamotech Umami Analytics? =

* **Advanced Event Tracking** - Automatically track user interactions beyond pageviews
* **Privacy-First** - GDPR compliant, no cookies, respects Do Not Track
* **Easy Setup** - Simple configuration with your self-hosted Umami instance
* **Professional Grade** - Built with WordPress best practices and coding standards
* **Actively Maintained** - Regular updates and support from Hamotech Solutions

= Key Features =

**Automatic Event Tracking:**
* File Downloads (PDF, ZIP, DOC, XLS, MP3, MP4, etc.)
* Outbound Link Clicks
* Comment Submissions
* User Logins
* New User Registrations
* 404 Error Pages

**Privacy Controls:**
* Respect Do Not Track browser settings
* Exclude admin users from tracking
* Exclude all logged-in users
* No cookies or personal data collection
* GDPR compliant

**Dashboard Integration:**
* Quick access widget to Umami dashboard
* Settings page with organized sections
* Plugin action links for easy access
* Professional admin interface

**Developer Friendly:**
* Clean, documented code
* WordPress coding standards
* Translation ready
* Hooks and filters available

= Perfect For =

* Privacy-conscious website owners
* GDPR compliance requirements
* Self-hosted analytics needs
* Detailed event tracking
* Professional WordPress sites

= About Umami Analytics =

Umami is a simple, fast, privacy-focused alternative to Google Analytics. It doesn't use cookies and respects user privacy. This plugin helps you integrate your self-hosted Umami instance or Umami Cloud account with WordPress.

= Documentation & Development =

* **GitHub Repository:** [https://github.com/RichardVBoi/Umami_wordpress_plugin](https://github.com/RichardVBoi/Umami_wordpress_plugin)
* **Documentation:** Full documentation available on GitHub
* **Developer Website:** [hamotechsolutions.com](https://hamotechsolutions.com) (launching soon)
* Actively developed and tested on production sites

= Setup Instructions =

1. Install and activate the plugin
2. Go to Settings → Umami Analytics
3. Enter your Website ID (from Umami dashboard)
4. Enter your Script URL (e.g., https://yourdomain.com/script.js)
5. Enable tracking and configure your preferences
6. Save settings and start tracking!

= Brought to You By =

**Hamotech Solutions** - Professional WordPress development and digital solutions.
Visit us at [hamotechsolutions.com](https://hamotechsolutions.com)

== Privacy Policy ==

Hamotech Umami Analytics integrates with Umami Analytics, a privacy-focused analytics platform. When tracking is enabled, this plugin connects to an external service (your configured Umami Analytics instance).

= Data Sent to Umami =

When tracking is active, the following data is sent to your configured Umami server:
* Page views and URLs visited
* Browser and device information (user agent, screen resolution, language)
* Referrer information (where visitors came from)
* Geographic location (country/region level, based on IP address)
* User interactions when event tracking is enabled:
  - File downloads (file name and type)
  - Outbound link clicks (destination URL)
  - Comment submissions (post ID, approval status)
  - User logins (username not tracked, only event occurrence)
  - New user registrations (only event occurrence)
  - 404 error pages (requested URL)

= User Privacy and Control =

**How Users Are Protected:**
* Tracking can be disabled completely by the site administrator
* Respects "Do Not Track" browser settings when enabled in plugin settings
* Admin users can be excluded from all tracking
* All logged-in users can be excluded from tracking
* No cookies are set by this plugin
* No personal identifying information is collected beyond standard web analytics
* IP addresses are processed by Umami (your configured instance) according to Umami's privacy practices

**Plugin Does Not Collect Data:**
This plugin itself does not collect, store, or transmit any data to Hamotech Solutions or any third party. All analytics data flows directly from your WordPress site to your configured Umami Analytics instance.

= External Service Information =

**Umami Analytics Service:**
* Service: Umami Analytics (self-hosted or Umami Cloud)
* Website: https://umami.is
* Privacy Policy: https://umami.is/privacy
* Service Location: Your configured Umami server URL
* Data Controller: You (the site owner) control where data is sent and stored

**User Configuration Required:**
* Site administrators must manually configure their Umami instance URL
* Site administrators must obtain and enter their Website ID from Umami
* No tracking occurs until these settings are configured and enabled
* You choose whether to self-host Umami or use Umami Cloud

= Your Legal Responsibilities =

As the site owner using this plugin, you are responsible for:
* Informing your website visitors that analytics are being collected
* Providing a privacy policy on your website disclosing analytics usage
* Ensuring compliance with GDPR, CCPA, and applicable local privacy laws
* Configuring the plugin's privacy settings appropriately for your jurisdiction
* Obtaining necessary consents from users if required by law
* Understanding and complying with Umami's terms of service

= GDPR Compliance Features =

* No cookies used by this plugin or Umami Analytics
* Anonymized data collection
* User exclusion options available
* DNT (Do Not Track) support
* Data processor agreement available through Umami
* User data stored on your chosen Umami instance (you control location)

= Data Retention =

Data retention is controlled by your Umami instance configuration, not by this plugin. Refer to your Umami dashboard settings and Umami's documentation for data retention policies.

== Installation ==

= Automatic Installation =

1. Log in to your WordPress admin panel
2. Navigate to Plugins → Add New
3. Search for "Hamotech Umami Analytics"
4. Click "Install Now" and then "Activate"
5. Go to Settings → Umami Analytics to configure

= Manual Installation =

1. Download the plugin ZIP file
2. Log in to WordPress admin panel
3. Navigate to Plugins → Add New → Upload Plugin
4. Choose the downloaded ZIP file and click "Install Now"
5. Activate the plugin
6. Configure at Settings → Umami Analytics

= FTP Installation =

1. Download and extract the plugin ZIP file
2. Upload the `hamotech-umami-analytics` folder to `/wp-content/plugins/`
3. Activate the plugin through the Plugins menu
4. Configure at Settings → Umami Analytics

= After Installation =

1. Navigate to Settings → Umami Analytics
2. Enable tracking with the toggle switch
3. Enter your Umami Website ID (found in your Umami dashboard under Settings → Websites)
4. Enter your Script URL (usually https://your-umami-domain.com/script.js)
5. Optionally enter your Host URL for dashboard widget access
6. Configure privacy settings according to your needs
7. Enable desired event tracking options
8. Click "Save Settings"
9. Verify tracking is working by checking your Umami dashboard

== Frequently Asked Questions ==

= What is Umami Analytics? =

Umami is a simple, fast, privacy-focused alternative to Google Analytics. It's open-source and can be self-hosted, giving you complete control over your data. Learn more at https://umami.is

= Do I need a paid Umami account? =

No! Umami is open-source and free to self-host on your own server. You can also use Umami Cloud if you prefer a managed solution (which has both free and paid tiers).

= Where do I get my Website ID and Script URL? =

1. Log into your Umami dashboard
2. Go to Settings → Websites
3. Select your website
4. Copy the Website ID (a string of characters)
5. Click "Edit" and find the Tracking Code section
6. Copy the script URL from the tracking code (the part after src=")

= Does this plugin work with Umami Cloud? =

Yes! This plugin works seamlessly with both self-hosted Umami instances and Umami Cloud accounts. Simply enter your Umami Cloud script URL and Website ID.

= Will this slow down my website? =

No. The tracking script loads asynchronously with the defer attribute, which means it won't block page rendering or affect your site's loading speed. The script is lightweight and optimized for performance.

= Is this GDPR compliant? =

Yes. Umami is designed to be privacy-focused and GDPR-compliant. It doesn't use cookies and doesn't collect personally identifiable information. This plugin includes additional privacy controls like DNT (Do Not Track) respect and user exclusion options to help you maintain compliance.

= Can I track custom events? =

Yes! The plugin automatically tracks common events (downloads, outbound links, etc.), but you can also use the Umami JavaScript API directly in your theme or other plugins to track custom events. Example: `umami.track('button-click', {button: 'signup'});`

= Does it track admin users by default? =

Yes, by default all visitors are tracked. However, you can enable the "Ignore Admin Users" option in the Privacy Settings to exclude users with administrator capabilities from all tracking.

= Can I exclude logged-in users? =

Yes! There's an "Ignore Logged-in Users" option in the Privacy Settings that excludes all authenticated users from tracking, not just admins.

= What events are tracked automatically? =

When you enable event tracking options, the plugin automatically tracks:
* **File Downloads:** PDF, ZIP, DOC, DOCX, XLS, XLSX, PPT, PPTX, MP3, MP4, AVI, MOV, JPG, PNG, GIF, SVG
* **Outbound Links:** Clicks on links pointing to external domains
* **Comment Submissions:** When users submit comments (with post ID and approval status)
* **User Logins:** Successful login events (username not tracked)
* **User Registrations:** New user account creation
* **404 Errors:** Page not found errors with requested URL

= How do I access my analytics dashboard? =

After configuring the Host URL in the plugin settings, a dashboard widget will appear on your WordPress dashboard with a direct link to your Umami analytics. You can also access it directly through your Umami instance URL.

= Is this plugin translation ready? =

Yes! The plugin is fully translation-ready using WordPress internationalization standards. The text domain is `hamotech-umami` and translation files can be placed in the `/languages` folder.

= Where can I get support? =

For support, bug reports, and feature requests:
* **Email:** info@hamotechsolutions.com
* **GitHub:** [https://github.com/RichardVBoi/Umami_wordpress_plugin](https://github.com/RichardVBoi/Umami_wordpress_plugin)
* **Website:** [hamotechsolutions.com](https://hamotechsolutions.com) (launching soon)

= How is this different from other Umami plugins? =

Hamotech Umami Analytics offers:
* More comprehensive event tracking options
* Better organized settings interface with clear sections
* Enhanced privacy controls beyond basic implementations
* Professional-grade code following WordPress standards
* Active development and support
* Dashboard widget integration
* More granular user exclusion options

= Can I use this with WooCommerce or other plugins? =

Yes! This plugin works alongside WooCommerce and other WordPress plugins. The event tracking (especially outbound links and downloads) will work automatically. You can also use Umami's JavaScript API to track custom WooCommerce events.

= Does this work with caching plugins? =

Yes! Since the tracking script is loaded directly in the HTML output, it works with all major caching plugins including WP Rocket, W3 Total Cache, WP Super Cache, and others.

= What PHP and WordPress versions are required? =

* WordPress 6.0 or higher
* PHP 7.4 or higher (PHP 8.0+ recommended)

The plugin has been tested with WordPress 6.7 and PHP 8.2.

== Screenshots ==

1. Main settings page with basic configuration - Enter your Umami Website ID and Script URL
2. Privacy and user settings section - Control who gets tracked and respect user privacy
3. Event tracking configuration options - Enable automatic tracking for various user interactions
4. Dashboard widget with quick access to Umami - One-click access to your analytics dashboard
5. Plugin settings link in plugins list - Easy access to configuration from the plugins page

== Changelog ==

= 1.0.0 - 2025-01-07 =
* Initial release
* Basic Umami Analytics integration with Website ID and Script URL configuration
* Advanced event tracking system with granular controls
* File download tracking for common file types (PDF, ZIP, DOC, media files)
* Outbound link tracking to monitor external link clicks
* Comment submission tracking with post metadata
* User login event tracking
* User registration event tracking
* 404 error page tracking with requested URLs
* Privacy controls including DNT (Do Not Track) support
* Admin user exclusion option
* Logged-in user exclusion option
* Professional admin settings interface with organized sections
* Dashboard widget for quick access to Umami dashboard
* Settings link in plugins page for easy access
* Translation ready with proper internationalization
* WordPress coding standards compliance
* Secure data handling with proper sanitization and escaping
* GPL v2 or later license
* Professional branding by Hamotech Solutions
* Tested with WordPress 6.0 through 6.7
* Tested with PHP 7.4, 8.0, 8.1, and 8.2

== Upgrade Notice ==

= 1.0.0 =
Initial release of Hamotech Umami Analytics. Install now to get started with privacy-focused analytics and advanced event tracking for your WordPress site.

== Third Party Services ==

This plugin connects to external services to provide analytics functionality:

= Umami Analytics =

**Service Provider:** Your configured Umami Analytics instance (self-hosted or Umami Cloud)
**Service Website:** https://umami.is
**Privacy Policy:** https://umami.is/privacy
**Terms of Service:** https://umami.is/terms

**Purpose:** Web analytics tracking to measure website traffic and user behavior

**Data Transmitted:**
* Pageviews and URLs
* Browser and device information
* Referrer data
* User interaction events (when enabled)

**When Data is Sent:**
* Only when tracking is enabled in plugin settings
* Only to the Umami server URL you configure
* Can be disabled at any time by the site administrator

**Legal Basis:**
* You (the site owner) are the data controller
* Your configured Umami instance is the data processor
* Ensure compliance with applicable privacy laws in your jurisdiction

== Credits ==

**Developed by:** Hamotech Solutions
**Website:** https://hamotechsolutions.com (launching soon)
**Email:** info@hamotechsolutions.com
**GitHub:** https://github.com/RichardVBoi/Umami_wordpress_plugin

Built with ❤️ for the WordPress community.

**Special Thanks:**
* Umami Analytics team for creating an excellent privacy-focused analytics platform
* WordPress community for ongoing support and feedback

== Support ==

For support, documentation, and updates:
* **Email:** info@hamotechsolutions.com
* **GitHub:** https://github.com/RichardVBoi/Umami_wordpress_plugin
* **Website:** https://hamotechsolutions.com (launching soon)
* **Documentation:** Available on GitHub repository

**Before requesting support:**
1. Check the FAQ section above
2. Verify your Umami Website ID and Script URL are correct
3. Ensure your Umami instance is accessible
4. Check browser console for JavaScript errors
5. Test with WP_DEBUG enabled

**When requesting support, please provide:**
* WordPress version
* PHP version
* Plugin version
* Description of the issue
* Steps to reproduce the problem
* Any error messages you're seeing

You can also open an issue on our GitHub repository: https://github.com/RichardVBoi/Umami_wordpress_plugin

== Contributing ==

We welcome contributions from the WordPress community! This plugin is built to serve website owners who value privacy and need professional-grade analytics integration.

**Ways to contribute:**
* Report bugs and issues on GitHub: https://github.com/RichardVBoi/Umami_wordpress_plugin
* Suggest new features via GitHub Issues
* Submit pull requests on GitHub
* Submit translations
* Improve documentation
* Share your experience using the plugin

Visit our GitHub repository for contribution guidelines: https://github.com/RichardVBoi/Umami_wordpress_plugin

== Roadmap ==

Future enhancements being considered:
* Custom event tracking UI in admin
* Analytics dashboard preview within WordPress
* WooCommerce integration enhancements
* Form submission tracking
* Search query tracking
* Video play tracking
* Scroll depth tracking
* Click heatmap data export

Have a feature request? Contact us at info@hamotechsolutions.com or open an issue on GitHub: https://github.com/RichardVBoi/Umami_wordpress_plugin
