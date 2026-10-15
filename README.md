# Kliqture

Kliqture is a professional platform for businesses, brands, skilled professionals, and creatives to showcase their work, discover opportunities, find talent, and collaborate remotely.

> The production source code is private. This repository is a public product and engineering case study.

---

## My Role

**Founder & Software Engineer**

I designed and developed Kliqture across mobile engineering, backend systems, product architecture, user experience, and production deployment.

My work spans the Flutter application, NestJS backend services, professional and brand experiences, opportunity workflows, real-time communication, workrooms, notifications, media delivery, payments, and mobile release engineering.

---

## What Kliqture Does

Kliqture brings professional discovery, hiring, and collaboration into one platform.

Users can:

- Create professional or brand profiles
- Showcase skills, projects, and creative work
- Discover professionals, brands, and opportunities
- Publish projects and engagements
- Seek specific expertise
- Apply for opportunities
- Review and select applicants
- Hire professionals
- Collaborate remotely
- Communicate through real-time conversations
- Organize work through tasks and workrooms
- Manage engagements from discovery through delivery

---

## Tech Stack

### Mobile
- Flutter
- Dart

### Backend
- NestJS
- TypeScript
- REST APIs
- WebSockets

### Data & Infrastructure
- PostgreSQL
- AWS
- Firebase

### Platform Engineering
- Push notifications
- Real-time messaging
- Media delivery
- Authentication and authorization
- iOS deployment
- Android deployment

---

## Selected Engineering Work

Some of the systems and product flows I have built or implemented include:

- Cross-platform mobile architecture with Flutter
- Professional and business profile experiences
- Media-rich discovery feeds
- Project and engagement publishing
- Opportunity application workflows
- Applicant review and selection
- Hiring workflows
- Real-time conversations
- Collaboration and hire rooms
- Project task management
- Push notifications and deep linking
- Backend APIs and application-state synchronization
- Payment-related workflow engineering
- Production iOS and Android deployment

---

# Product Walkthrough

## Discover

Professionals and brands can discover people, work, and opportunities across the platform.

![Kliqture Discover Page](assets/discover-page.png)

---

## Professional & Creative Feed

Kliqture is designed around multi-skilled professionals and creatives rather than restricting users to a single professional identity.

### Singer & Songwriter

![Singer and Songwriter Post](assets/home-feed-showing-a-singer-and-songwriter-post.png)

### Actor

![Actor Post](assets/home-feed-showing-an-actor-post.png)

---

## Brand Opportunities

Brands and businesses can publish opportunities and seek professionals with specific expertise.

![Brand Engagement Post](assets/home-feed-showing-brand-engagement-post.png)

### Engagement Details

This example shows a brand seeking a Flutter developer.

![Brand Seeking Flutter Developer](assets/engagement-work-detail-page-showing-the-brand-seeking-a-flutter-developer.png)

---

## Projects

Professionals can showcase projects and work they have created.

![Animator Project](assets/work-detail-page-showing-an-animator-project.png)

---

## Collaboration

Kliqture includes dedicated collaboration spaces for people working together after a professional connection has been made.

### Conversation & Project Deliverables

![Collaboration Room Conversation](assets/collab-room-conversation-displaying-project-deliverables.png)

### Task Management

![Project Tasks](assets/project-page-showing-the-tasks.png)

---

## Hire Workflow

The platform includes dedicated workflows for managing professional hiring engagements.

### Active Work

![Active Work](assets/submit-milestone-sheet-showing-first-milestone-is-running.png)

### Releasing Funds

![Release Funds](assets/hire-room-release-milestone-funds-showing-the-release-button.png)

### Successful Release

![Successful Release of Funds](assets/hire-room-successful-release-of-funds.png)

---

## Engineering Scope

Kliqture is a full production product involving multiple interconnected systems across mobile, backend, infrastructure, and product engineering.

A typical workflow can involve:

**Discovery → Opportunity → Application → Selection → Conversation → Workroom → Task Execution → Delivery**

Building these experiences has required work across areas such as:

- Complex application state
- Role-specific user experiences
- API design and integration
- Authentication and authorization
- Real-time communication
- File and media handling
- Push notifications
- Deep linking
- Error handling
- Data persistence
- Performance optimization
- Mobile release engineering
- Production environment management

---

## Architecture

At a high level, Kliqture uses a mobile-client and API architecture:

```text
Flutter Mobile Application
          │
          │
       REST APIs
          │
          ▼
    NestJS Backend
          │
     ┌────┴────┐
     │         │
 PostgreSQL   External Services
     │         │
     │      Firebase / AWS
     │
 Application Data
```

Real-time functionality is handled through persistent communication services where required.

> This architecture is intentionally high-level. Internal implementation details remain private.

---

## Selected Screens

| Discover | Brand Opportunity |
|---|---|
| ![Discover](assets/discover-page.png) | ![Brand Engagement](assets/home-feed-showing-brand-engagement-post.png) |

| Creative Work | Professional Project |
|---|---|
| ![Actor](assets/home-feed-showing-an-actor-post.png) | ![Animator Project](assets/work-detail-page-showing-an-animator-project.png) |

| Collaboration | Task Management |
|---|---|
| ![Collaboration](assets/collab-room-conversation-displaying-project-deliverables.png) | ![Tasks](assets/project-page-showing-the-tasks.png) |

---

## Product

**Website:** [kliqture.com](https://kliqture.com)

Kliqture is an actively developed commercial product for businesses, brands, skilled professionals, and creatives.

---

## Source Code

The production Flutter and backend repositories are private because Kliqture is a commercial product under active development.

This public repository intentionally contains no proprietary production source code, credentials, internal infrastructure configuration, or sensitive business logic.

Its purpose is to demonstrate:

- The product
- My engineering responsibilities
- The systems I have built
- The technical scope of the application
- My ability to take a mobile product from concept through production
