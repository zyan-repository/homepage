# Design Document - Personal Homepage

## Project Description

This project is a personal homepage website for Yian Zhou. The website serves as a professional portfolio showcasing skills, projects, and experience to potential employers, collaborators, and professional networks.

The homepage is built using HTML5, CSS3, and ES6+ JavaScript with Bootstrap 5. It features a clean, modern interface with smooth scrolling navigation and project showcases with GitHub repository links.

## User Personas

### Primary Persona: Potential Employers
- **Name**: Alex Wang
- **Role**: Hiring Manager at Tech Company
- **Goals**: 
  - Quickly assess candidate's technical skills
  - Review relevant project experience
  - Evaluate communication and presentation skills
- **Pain Points**: Limited time to review portfolios, need clear skill demonstration

### Secondary Persona: Professional Network
- **Name**: Jack Smith
- **Role**: Senior Software Engineer
- **Goals**:
  - Connect with professionals in software engineer field
  - Find potential collaborators for projects
  - Stay updated on industry trends
- **Pain Points**: Difficulty finding relevant professionals, need quick skill assessment

## User Stories

### Story 1: The Busy Hiring Manager
Alex is a hiring manager at a tech startup. She's reviewing dozens of resumes and portfolios every week, and she needs to quickly assess candidates' technical skills. When she visits Yian's homepage, she immediately sees his 7+ years of experience and the skill progress bars showing his proficiency in Python (95%), C (90%), and other technologies. The clean layout and clear information hierarchy help her make a quick decision about whether to schedule an interview.

### Story 2: The Curious Developer
Jack is a senior developer who met Yian at a tech conference. He's interested in collaborating on a computer vision project and wants to see what kind of work Yian has done before. He navigates to the Projects section and finds three well-documented projects with clear descriptions and GitHub links. He can quickly understand the tech stack used (OpenCV, PyTorch, etc.) and decide if their skills align for potential collaboration.

## Design Mockups

```
┌─────────────────────────────────────────────────────────────┐
│ [Zyan]                    [Home] [Projects] [Skills]        │
├─────────────────────────────────────────────────────────────┤
│                                                             │
│  Hello, I'm Yian Zhou        [Profile Photo]                 │
│  Software Engineer                                          │
│  Software Engineer with 7 years...                          │
│  [View My Work]                                             │
│                                                             │
│  [7+ Years] [20+ Projects] [10+ Technologies]               │
├─────────────────────────────────────────────────────────────┤
│                    My Projects                              │
│  ┌─────────────┐ ┌─────────────┐ ┌─────────────┐            │
│  │ Track-any   │ │ Video       │ │ Fisheye     │            │
│  │ thing       │ │ understand  │ │ to side     │            │
│  │ [Opencv]    │ │ [Pytorch]   │ │ [Calib]     │            │
│  └─────────────┘ └─────────────┘ └─────────────┘            │
├─────────────────────────────────────────────────────────────┤
│                    My Skills                                │
│  ┌─────────────────────┐ ┌─────────────────────┐            │
│  │ Programming Langs   │ │ Tools & Frameworks  │            │
│  │ C: ████████████ 90% │ │ Pytorch: ████████ 85%│           │
│  │ Python: ██████████ 95%│ │ TensorRT: ████████ 90%│        │
│  └─────────────────────┘ └─────────────────────┘            │
└─────────────────────────────────────────────────────────────┘
```

### Color Scheme
- **Primary**: #667eea (Blue gradient start)
- **Secondary**: #764ba2 (Purple gradient end)
- **Accent**: Bootstrap primary blue
- **Background**: White (#ffffff)
- **Text**: Dark gray (#333333)
- **Light Background**: #f8f9fa

### Typography
- **Font Family**: "Helvetica", "Roboto", "Lora", sans-serif
- **Headings**: Bootstrap display classes
- **Navigation**: Bootstrap navbar styling

### Interactive Elements
- **Hover Effects**: Cards lift up with shadow
- **Smooth Scrolling**: Navigation links scroll smoothly to sections

## Technical Requirements
- HTML5 semantic structure
- CSS3 with Bootstrap 5 framework
- ES6+ JavaScript modules
