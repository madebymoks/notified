# Notified Dashboard

The **Notified Dashboard** is the management interface for the Notified platform. It allows developers and product teams to create, schedule, and manage contextual in-app messages that are delivered through the Notified React and Next.js SDK.

With Notified, you can communicate with users without modifying application code or redeploying your application. Simply create or update a message in the dashboard and your application will receive the changes automatically.

## Features

* 📢 Create and manage in-app messages
* 🎯 Target messages to specific application routes
* 🌐 Restrict messages to specific application base URLs
* 🗓️ Schedule messages to automatically activate and expire
* 👀 View-only informational messages
* ✅ Dismissible messages that remain hidden after dismissal
* 🧭 Internal navigation messages
* 🔗 External navigation messages
* ⚡ Remote message updates without application redeployment
* 🔐 Secure delivery through Supabase Edge Functions

## Supported Message Types

### View Only

Display informational messages that require no user interaction.

Examples:

* Product announcements
* Maintenance notices
* Welcome messages

---

### Dismissible

Allow users to dismiss messages after reading them. Once dismissed, the message remains hidden for that user unless the message is updated.

Examples:

* Release notes
* Product tips
* Important reminders

---

### Internal Navigation

Guide users to another page within your application.

Examples:

* Try a newly released feature
* Complete onboarding
* View account settings

---

### External Navigation

Direct users to resources outside your application.

Examples:

* Documentation
* Help Center
* Pricing page
* Blog articles

## Scheduling

Messages can be scheduled to automatically appear and disappear.

Scheduling supports:

* Future publication
* Automatic expiration
* Temporary promotions
* Planned maintenance notifications
* Product launch announcements

The scheduling engine is managed by the backend, ensuring messages activate and expire automatically without requiring manual intervention.

## How It Works

1. Install the Notified SDK in your React or Next.js application.
2. Register your application in the Notified Dashboard.
3. Create a project and obtain a project key.
4. Install the project key in your application.
5. Create and publish messages from the dashboard.
6. The SDK retrieves active messages and renders them inside your application.

No redeployment is required after publishing or updating a message.

## Technology

The dashboard is built using:

* React
* TypeScript
* Supabase
* Supabase Edge Functions
* PostgreSQL

## Roadmap

Future improvements include:

* Message analytics
* Click tracking
* User engagement metrics
* Message templates
* Team collaboration
* Role-based access control
* Audit logs
* Webhooks
* Public API

## Contributing

Contributions, feature requests, and bug reports are welcome. Please open an issue or submit a pull request.
