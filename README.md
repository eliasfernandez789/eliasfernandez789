# 👋 Elías Fernández

<div align="center">

**Full-Stack Developer** | **UI/UX Engineer** | **Real Estate Tech Specialist**

Building elegant, performant web applications that solve real business problems.

[Portfolio](#-featured-projects) • [Tech Stack](#-tech-stack) • [Get in Touch](#-connect-with-me)

</div>

---

## 🎯 About Me

I'm a passionate full-stack developer with expertise in creating sophisticated web applications for complex business domains. I specialize in building **responsive, accessible interfaces** combined with **robust backend systems** that scale.

Currently focused on:
- 🏠 Real estate technology and marketplace solutions
- 🎨 Design-driven development with premium UI/UX
- 🚀 Performance optimization and modern web standards
- 🔐 Secure, scalable architectures with proper data governance

---

## 🌟 Featured Projects

### 🏆 **Bolsa de Pedidos Royal** — Real Estate Deal Board
*A sophisticated marketplace platform for RE/MAX Royal real estate network*

**What it does:**
- Centralized order board connecting multiple agents and offices across Paraguay
- Smart matching engine that pairs property captures with buyer requests
- Role-based access control with strict data privacy (lead information segregation)
- Real-time consultation tracking and deal workflow management

**Tech highlights:**
```
Frontend:  Vanilla JS, CSS custom properties, responsive design
UX:        Command palette (⌘K), advanced filtering, live search
Features:  Matching algorithm, dynamic pricing (USD/PYG conversion)
Design:    Premium dark theme, glassmorphism, smooth animations
Data:      RLS-protected leads table, audit trail with timeline
```

**Key Features:**
- ✨ **Global Search Command** (`⌘K`) with intelligent suggestions
- 🎯 **Smart Matching** — Proprietary algorithm ranks captures by compatibility
- 🔐 **Privacy-First** — Lead data visible only to assigned office
- 💱 **Multi-Currency** — USD ↔ PYG conversion with configurable rates
- 📊 **Rich Analytics** — Consultation tracking, temperature scoring (🔥🟡❄️)
- 📝 **Audit Trail** — Complete timeline of actions per deal
- 🌐 **Multi-Office Support** — RE/MAX Royal + external network

**Design System:**
- Deep space color palette (`#080C14`) with institutional navy
- Smooth cubic-bezier animations and micro-interactions
- Accessibility-first approach (focus-visible, semantic HTML)
- Mobile-responsive grid layout

---

## 💻 Tech Stack

### **Frontend**
- **HTML5** — Semantic structure, accessibility
- **CSS3** — Custom properties, grid, flexbox, animations
- **JavaScript (Vanilla)** — Event handling, DOM manipulation, state management
- **Design** — Premium UI with glassmorphism, dark theme mastery

### **Patterns & Practices**
- Responsive & Mobile-First Design
- Progressive Enhancement
- State Management (immutable patterns)
- Event-Driven Architecture
- ARIA & Accessibility Standards (WCAG)

### **Design & UX**
- Figma (design systems thinking)
- Interaction Design
- Micro-animations & Transitions
- Color theory & Typography
- Dark mode optimization

### **Tools & Workflows**
- Git & GitHub
- Modern browser DevTools
- Performance profiling
- Responsive testing

---

## 🎨 Design Philosophy

I believe in **elegant simplicity** — interfaces should be:
- **Intuitive** — Minimal learning curve
- **Performant** — Smooth 60fps animations
- **Accessible** — Works for everyone
- **Beautiful** — Premium aesthetics matter
- **Functional** — Every pixel serves a purpose

---

## 📈 Key Achievements

✅ Built a **production-grade marketplace platform** handling complex deal workflows  
✅ Implemented **role-based access control** with database-level privacy policies  
✅ Created **intelligent matching algorithm** for real estate captures  
✅ Designed **premium dark UI** with accessibility-first approach  
✅ Managed **multi-currency transactions** with dynamic conversion  
✅ Built **command palette interface** for power-user efficiency  

---

## 🔧 Notable Code Patterns

### Smart Filtering System
```javascript
// Composable filter functions that play well together
function filtrar(){
  return PEDIDOS
    .filter(porVista)
    .filter(porEstado)
    .filter(porZonas)
    .filter(porTemperatura)
    .sort(porRelevancia);
}
```

### Compatibility Scoring Algorithm
```javascript
function compatibilidad(capture, request){
  let score = 0;
  if (capture.type === request.type) score += 40;
  if (request.zones.includes(capture.zone)) score += 35;
  if (capture.price <= request.budget) score += 25;
  return score; // Used for ranking matches
}
```

### Data Privacy with RLS Simulation
```javascript
// Lead data only visible if user's office owns the request
const puedeVerLead = p => ROLE === 'interna' && esMiOficina(p);
```

---

## 📚 What I'm Learning

- Advanced state management patterns
- Backend system design (APIs, databases)
- Web performance optimization
- Accessibility standards in depth
- Team collaboration at scale

---

## 🤝 Connect With Me

- 💼 **GitHub** — You're already here! Check out my repos
- 📧 **Email** — Let's talk about your next project
- 🔗 **LinkedIn** — Professional updates and insights

---

## 💡 Philosophy

> *"Great software isn't just about making computers happy—it's about making humans happy. Design, code, and communication all matter equally."*

I approach every project with:
- **Attention to detail** in both code and UX
- **User empathy** — understanding real workflows
- **Performance mindset** — respecting user's time & bandwidth
- **Clean code** — maintainable, documented, tested
- **Continuous learning** — staying current with web standards

---

<div align="center">

### 🚀 Let's Build Something Amazing Together

*Open to collaboration on impactful projects*

</div>
