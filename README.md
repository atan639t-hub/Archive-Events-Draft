# ArtLink SG

> A single, arts-specific hub that connects Singapore's independent artists with learning opportunities, collaborators, and government art initiatives.

![Status](https://img.shields.io/badge/status-prototype-orange.svg)
![Built with](https://img.shields.io/badge/built%20with-HTML-e34c26.svg)
![License](https://img.shields.io/badge/license-MIT-blue.svg)

> **Note:** ArtLink SG is an early prototype. Features, structure, and design are still being developed and may change significantly.

## Table of Contents

- [About](#about)
- [The Problem](#the-problem)
- [Objectives](#objectives)
- [Who It's For](#whos-it-for)
- [Planned Features](#planned-features)
- [How ArtLink SG Differs](#how-artlink-sg-differs)
- [Getting Started](#getting-started)
- [Project Structure](#project-structure)
- [Roadmap](#roadmap)
- [Security, Privacy and Compliance](#security-privacy-and-compliance)
- [Team](#team)
- [Contributing](#contributing)
- [License](#license)
- [References](#references)

## About

Singapore supports the arts through cultural policy and government-funded programmes, but support often focuses on established institutions and the wider creative industry. Independent artists can find it hard to access opportunities, build skills, and gain visibility.

ArtLink SG is a centralised platform that brings independent artists, art organisations, and local communities together in one place. It hosts artist pages, lists events and opportunities, and links artists to partners such as arts councils, art schools, libraries, and community spaces.

## The Problem

Singapore's creative economy is driven by state-led ambitions, yet the education system prioritises STEM, arts education is marginalised, art graduates have limited professional training, and artistic visibility is often discouraged. This weakens the creative culture and talent pipeline needed for sustainable growth.

Independent artists, government initiatives, and residents often operate separately, with no shared place to connect.

## Objectives

- **Accessibility and opportunities:** provide accessible creative education, mentorship, and skills development.
- **Inclusion and community building:** help independent artists gain exposure and access opportunities without the burden of constant self-promotion.

## Who It's For

- **Independent artists** of all ages and mediums who need accessible, flexible, and inclusive spaces to connect, collaborate, and grow.
- **Art enthusiasts** looking for enrichment such as gallery visits, casual in-person painting sessions, and human-created art.
- **Community members** who want ways to build connections beyond their neighbourhoods and Community Centres, across age groups.
- **Partner organisations** such as arts councils, art schools, libraries, galleries, and community groups.

## Planned Features

- **Artist portfolios and showcases:** a home for original, human-created work, with clear AI-content labelling.
- **Centralised events hub:** one dedicated place to discover, join, and take part in art-related and social events. Listings from multiple organisations (arts councils, schools, libraries, galleries, community groups, and independent artists) are brought together with searchable categories, interest-based filters, and personalised recommendations.
- **Artist-led events:** artists can organise and host their own events, open to beginners, and list them in the events hub.
- **Event chat:** every event gets its own chat space where attendees, hosts, and organisers can ask questions, share updates and reminders, coordinate meetups, and keep the conversation going after the event. Hosts can pin announcements, and chats are moderated with reporting tools.
- **Opportunities board:** open calls, grants, commissions, and public programmes in one central listing.
- **Artist collaboration:** a matching board and shared project tools so artists can co-create.
- **Learning and skills:** workshops and mentorship, plus skills in cybersecurity, UI/UX, legal/audit, and finance/accounting.
- **Community network:** regular meetups, showcases, and shared channels, with a physical home base through partner venues.
- **Free community access:** free event listings and external ticketing links at launch, with affordable integrated ticketing as the platform grows.

## How ArtLink SG Differs

General ticketing platforms such as Eventbrite are built for ticket sales, not for building an arts community. Arts events can get buried among concerts and conferences, per-ticket fees can hurt small or free community initiatives, and there is no link to government grants or open calls.

ArtLink SG is designed for Singapore's context, including HDB-based community participation, and supports the full artist journey of visibility, funding, and learning.

## Getting Started

> The prototype is planned as a website built with HTML. Update these steps as the project takes shape.

### Prerequisites

- A modern web browser
- Git
- *(Optional)* Python 3, to serve the site locally

### Run Locally

1. Clone the repository

   ```bash
   git clone https://github.com/your-username/artlink-sg.git
   cd artlink-sg
   ```

2. Open `index.html` in your browser, or serve the folder locally:

   ```bash
   python3 -m http.server 8000
   ```

   Then visit `http://localhost:8000`.

## Project Structure

```
artlink-sg/
├── index.html      # Landing page
├── css/            # Stylesheets
├── js/             # Scripts
├── assets/         # Images and other media
├── docs/           # Proposal, screenshots, and documentation
├── LICENSE
└── README.md
```

*(Update this to match the actual layout of the repository.)*

## Roadmap

- [ ] **Phase 1: Research and planning:** confirm the audience, partners, and scope; verify domain availability and hosting approval.
- [ ] **Phase 2: Design and development:** build the core pages and features, including the centralised events hub and event chat, followed by usability and beta testing.
- [ ] **Phase 3: Launch and evaluation:** phased rollout starting with selected organisations, then measure engagement and feedback.

Success will be tracked through community growth, partnerships, user engagement, usability and accessibility, security testing, and compliance.

## Security, Privacy and Compliance

ArtLink SG aims to protect artists and their work from the start:

- **Data privacy:** privacy-by-design, informed consent, access controls, and data retention policies in line with Singapore's PDPA.
- **Security:** penetration testing, vulnerability assessments, and secure code reviews before launch.
- **Intellectual property:** copyright policies, ownership guidelines, and reporting mechanisms to protect artists' original works.
- **Content standards:** standardised event submission guidelines and content moderation and reporting procedures.
- **Chat safety:** event chats include moderation tools, a way to report messages and users, and clear community guidelines. Chat data is covered by the same consent, access control, and retention rules as other personal data.

## Team

Proposed by Amberlyn Tan, Tanisha Dasari, and Nurhazira.

The project also needs artists, web developers, and anyone interested in contributing, as well as mentorship to help roll out the idea.

## Contributing

Contributions and feedback are welcome, especially at this early prototype stage.

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/your-feature`)
3. Commit your changes (`git commit -m "Add your feature"`)
4. Push to the branch (`git push origin feature/your-feature`)
5. Open a Pull Request

## License

The source code is distributed under the MIT License. See [`LICENSE`](LICENSE) for details. Artwork and content shown on the platform remain the property of their respective artists.

## References

- Chung, P. (2008). The creative industry of Singapore: Cultural policy in the age of globalisation. *Media International Australia, 128*(1), 31-45.
- Gwee, J. (2009). Innovation and the creative industries cluster: A case study of Singapore's creative industries. *Innovation: Management, Policy & Practice, 11*(2), 240-252.
- Kong, L. (2012). Ambitions of a global city: Arts, culture and creative economy in 'post-crisis' Singapore. *International Journal of Cultural Policy, 18*(3), 279-294.
- Ooi, C.-S. (2012). Education and becoming an artist: Experiences from Singapore. In C. Mathieu (Ed.), *Careers in creative industries* (pp. 266-281). Routledge.
- Trivic, Z., Tan, B. K., Mascarenhas, N., & Duong, Q. (2020). Capacities and impacts of community arts and culture initiatives in Singapore. *The Journal of Arts Management, Law, and Society.*

The full reference list is in the project proposal deck.
