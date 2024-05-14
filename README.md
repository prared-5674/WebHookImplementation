ASP.NET Core WebHook System
This project implements a WebHook system in ASP.NET Core, designed to facilitate real-time event notifications. It supports dynamic event handling, enhancing user engagement through timely updates.

Features
Event Driven Notifications: Send real-time updates to registered subscribers when specified events occur.
Subscription Management: Allows clients to subscribe or unsubscribe to specific event types with an easy-to-use API.

Tech Stack Used
.NET 6 SDK or later
Visual Studio 2022

API Reference
POST /api/webhooks/subscribe: Subscribe to a specific type of event.
POST /api/webhooks/notify: Notify all subscribers about an event occurrence.
GET /api/webhooks/verify: Verify subscriber endpoint during the subscription process.
