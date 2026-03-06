# web-portofolio-technical-writing-course

**Elevate your products to the next level**

A portfolio website for **Usef Mohamed** — full-stack developer specialising in intelligent web applications and data-driven business solutions.

---

## Site Structure Flowchart

```mermaid
flowchart TD
    HOME["🏠 Home\nindex.html"]
    PROJ["📁 Projects\nprojects.html"]
    SVC["🛠️ Services\nservices.html"]
    REV["⭐ Reviews\nreviews.html"]
    BG["🎓 Background\nacademic.html"]
    FC["🗺️ Flowchart\nflowchart.html"]
    CON["📬 Contact\ncontact.html"]

    %% Global navigation bar — present on every page
    HOME <-->|global nav| PROJ
    HOME <-->|global nav| SVC
    HOME <-->|global nav| REV
    HOME <-->|global nav| BG
    HOME <-->|global nav| FC
    HOME <-->|global nav| CON
    PROJ <-->|global nav| SVC
    PROJ <-->|global nav| REV
    PROJ <-->|global nav| BG
    PROJ <-->|global nav| FC
    PROJ <-->|global nav| CON
    SVC  <-->|global nav| REV
    SVC  <-->|global nav| BG
    SVC  <-->|global nav| FC
    SVC  <-->|global nav| CON
    REV  <-->|global nav| BG
    REV  <-->|global nav| FC
    REV  <-->|global nav| CON
    BG   <-->|global nav| FC
    BG   <-->|global nav| CON
    FC   <-->|global nav| CON

    %% Inline call-to-action links
    HOME  -.->|"CTA: View My Work"| PROJ
    HOME  -.->|"CTA: Get In Touch"| CON
    SVC   -.->|"CTA: Request a Quote"| CON
    REV   -.->|"CTA: Get In Touch"| CON
    BG    -.->|"CTA: View Projects"| PROJ
    BG    -.->|"CTA: Get In Touch"| CON
    PROJ  -.->|"CTA: Start a Conversation"| CON
```

> **Legend**
> - `↔` Solid bidirectional arrows = global navigation bar (every page ↔ every page)
> - `⇢` Dashed arrows = inline call-to-action buttons

---

## Pages

| Page | File | Description |
|------|------|-------------|
| 🏠 Home | `index.html` | Hero, stats strip, featured projects, CTA banner |
| 📁 Projects | `projects.html` | Full portfolio of 8 delivered projects |
| 🛠️ Services | `services.html` | 9 service cards + 4-step process |
| ⭐ Reviews | `reviews.html` | 6 client testimonials + rating summary |
| 🎓 Background | `academic.html` | Technical skills grid + B.Sc. education |
| 🗺️ Flowchart | `flowchart.html` | Interactive site-structure diagram (this flowchart, rendered) |
| 📬 Contact | `contact.html` | Contact form + FAQ + direct email |

