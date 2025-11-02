# Choices, Choices - The Tech-stack

Ik heb een onderzoek uitgevoerd naar 11ty, Next.js en Vue. Voor elk framework heb ik een aparte repository aangemaakt, waarin ik in de README de installatie, belangrijke stappen en bevindingen heb gedocumenteerd. Daarnaast heb ik een live voorbeeldwebsite toegevoegd om de werking van elk framework te demonstreren.

# Repos die ik heb gemaakt:

https://github.com/Abeeryu/11ty

https://github.com/Abeeryu/Next.js

https://github.com/Abeeryu/Vue.js

Hier maak ik een **vergelijking** tussen 11ty, Next.js en Vue op het gebied van User Experience, Developer Experience en Content Management Experience.
En ik heb voor dat een powerpoint gemaakt. 

[Presentatie tech-stack.pptx](https://github.com/user-attachments/files/23293052/Presentatie.tech-stack.pptx)

## User eXperience

### 11ty:
-- --

### Doelgroep & devices:

- Contentlezers: desktop, tablet, mobiel.

- Lage eisen qua internet; statische HTML-sites laden snel, zelfs bij lage bandbreedte.

### Randvoorwaarden:

- Site is statisch → weinig JavaScript, minimale rekenkracht nodig.

- Werkt offline alleen beperkt (kan wel met Service Workers).

- Netwerkverkeer is laag; weinig HTTP-requests.

### Next.js: 
-- --

### Doelgroep & devices:

- Interactieve webapps en complexe websites: desktop, tablet, mobiel.

- Modern browsergebruik vereist; SSR zorgt dat eerste load snel is.

### Randvoorwaarden:

- Kan SSR en SSG gebruiken → snellere laadtijden en SEO.

- Dynamische content → netwerkverkeer hoger bij API-calls.

- Offline ervaring via Service Workers en caching mogelijk.

### Vue:
-- --

### Doelgroep & devices:

- Interactieve apps: desktop, tablet, mobiel.

- Modern browsergebruik vereist.

### Randvoorwaarden:

- SPA → JavaScript nodig.

- Interactiviteit zoals forms, modals, animaties → hogere rekenkracht nodig.

- Netwerkverkeer kan hoger zijn bij veel API-calls.

- Offline gebruik beperkt zonder extra setup (Service Workers).

## Developer eXperience

### 11ty:
-- --

### Functies:

- Statische site generator → eenvoudig op te zetten met minimale config.

- Markdown support, templating (Nunjucks, Liquid).

### Betrouwbaarheid & performance:

- Snel bouwen, weinig dependencies.

- Actieve community en updates, maar geen complexe tooling.

### Gemak & helderheid:

- Documentatie duidelijk, CLI makkelijk.

- API beperkt tot data-templates; eenvoudig te begrijpen.

### Next.js: 
-- --

### Functies:

- Component-based architecture → herbruikbare componenten.

- Hot Module Replacement (HMR) via Vite → snelle feedback tijdens development.

### Betrouwbaarheid & performance:

- Snelle builds, goed onderhoudbare projecten.

- Community groot, veel plugins en tutorials.

### Gemak & helderheid:

- Documentatie goed, duidelijke API.

- Templates en reactiviteit eenvoudig te begrijpen.

### Vue
-- --

### Functies:

- Server-side rendering, static generation, API-routes.

- Routing, dynamic pages en middleware eenvoudig via framework.

### Betrouwbaarheid & performance:

- Framework stabiel, goede community.

- Regelmatige updates, goede debugging tools.

### Gemak & helderheid:

- Documentatie uitgebreid en duidelijk.

- Codebase kan complex zijn bij grote projecten, maar goed gestructureerd.
  
Vue: Component-based, HMR via Vite, goede docs

## Content Management eXperience

### 11ty:
-- --

### Eisen aan contentbeheerders:

- Kan werken met markdown of headless CMS zoals Netlify CMS.

- Lage technische kennis nodig; eenvoudige content toevoeging.

### Beperkingen:

- Voor dynamische content of complexe pagina’s moet beheerder wat technische kennis hebben

### Next.js:
-- --

### Eisen aan contentbeheerders:

- CMS-integratie (Contentful, Prismic, Sanity) → minimale technische kennis vereist.

- Beheer van dynamische content en pagina’s is intuïtief bij headless CMS.

### Beperkingen:

- Voor het toevoegen van complexe componenten kan frontend kennis handig zijn.
  
### Vue:
-- --

### Eisen aan contentbeheerders:

- Voor statische content → CMS integratie mogelijk (Netlify CMS, Strapi).

- Voor dynamische componenten → technische kennis nodig om componenten te configureren.

### Beperkingen:

- Beheerder moet begrijpen dat sommige componenten data-driven zijn.

## Bronnen

https://medium.com/swlh/what-is-dx-developer-experience-401a0e44a9d9

https://www.softermii.com/blog/10-tips-in-choosing-the-best-tech-stack-for-your-web-application

https://symfony.com/ten-criteria

https://www.velvetech.com/blog/choosing-project-tech-stack-basic-principles/

https://tray.io/blog/align-revenue-ops-tech-stack

https://www.zachleat.com/web/site-generator-review/

## Licentie

This project is licensed under the terms of the [MIT license](./LICENSE).
