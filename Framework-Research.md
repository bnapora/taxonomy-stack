### Download Template Websites
wget --mirror -p --convert-links -P ./hyper2_062823 https://coderthemes.com/hyper_2/

wget --mirror -p --convert-links -P ./phoenix_062823 https://prium.github.io/phoenix/v1.13.0/

wget --mirror -p --convert-links -P ./falcon_062923 https://prium.github.io/falcon/v3.14.0/

### Frameworks
Django with VueJS
https://www.digitalocean.com/community/posts/build-an-app-with-vuejs-and-django-part-one



FastAPI with VueJS
https://testdriven.io/blog/developing-a-single-page-app-with-fastapi-and-vuejs/
https://github.com/testdrivenio/fastapi-vue
https://medium.com/codex/how-to-integrate-fastapi-with-vuejs-ef6734b308fd
https://dimmaski.com/serve-vue-fastapi/

FastAPI with Nuxt
https://github.com/whythawk/nuxt-for-fastapi

Research Tasks (063023)
[] Install FastAPI Fullstack on Linux1 - Build Errors
    - https://github.com/tiangolo/full-stack-fastapi-postgresql
    - Issue with "fixes" for build issue
        https://github.com/tiangolo/full-stack-fastapi-postgresql/issues/469
[] Build FastAPI Fullstack with mySQL - Build Errors
    - https://github.com/vuongtlt13/full-stack-fastapi-mysql
    - Builds and Displays Logon but can't login
    - Celery container error; doesn't copy app folder (can't get it to copy)
[] Add NuxtJS to Stack
    - https://github.com/whythawk/nuxt-for-fastapi
[] Review FastAPI/NextJS Tutorial
    https://www.travisluong.com/full-stack-next-js-fastapi-postgresql-tutorial/
    https://www.youtube.com/watch?v=HJ314MNcCck
[] Review FastAPI/NuxtJS Tutorial
    - https://www.youtube.com/watch?v=J9EbxoJGwbI
    - https://www.fullstackbook.com/frontend/ui-component-libraries
[] Install FastAPI-Vuetify
    - https://github.com/ywiyogo/FastAPI-Vuetify
[] Install FastAPI full-stack-fastapi-mysql
    - https://github.com/vuongtlt13/full-stack-fastapi-mysql
[] Build FastAPI Vue App
    - https://github.com/dimmaski/fastapi-vue
[] Install nuxt-fastapi-template - Build Errors
    - https://github.com/MehdiRtal/nuxt-fastapi-template
    - New repo; didn't troubleshoot  

#### This One Works!!!  
[] Install update fullstack with Nuxt 3
    - https://github.com/bnapora/full-stack-fastapi-postgresql

#### TailwindCSS Admin Templates
https://github.com/justboil/admin-one-vue-tailwind

Nuxt/Tailwind Dashboard Sysem
https://tairo.cssninja.io/

Tailwind Components
https://tailwindui.com/components

Flowbite - Tailwind UI Components
https://flowbite.com/docs/getting-started/quickstart/


#### Nuxt3 Starters
Nuxt Starter Repo
https://github.com/viandwi24/nuxt3-awesome-starter

https://github.com/creativetimofficial/nuxt-black-dashboard

https://github.com/who-jonson/sakai-nuxt

https://github.com/fzn0x/mazer-nuxt

#### Next.js Starters (07/01/23)
https://github.com/vercel/nextjs-postgres-auth-starter
https://github.com/wenion/notus-nextjs

#### Sveltekit Starters: (070723)
#1 = sveltekit-auth-starter
https://github.com/delay/sveltekit-auth-starter
- uses SkeletonUI; little clunk look but it works.

#2 = https://github.com/xulioc/sveltekit-supabase-dashboard
Pros: supabase; works; more complete
Issues: didn't use SkeletonUI
ToDo: revisit UI kit 

#3 = https://github.com/multiplehats/jaydens-stack - nice roadmap
Pros: shadcn; several tools integrated; docs limited
Issues: no docs; couldn't get auth working

#4 = https://github.com/chasetmartin/SvelteKit_Skeleton_Playground
Pros: Demo of sidebar nav; could port to auth-starter
Issues: not full stack; 

Additions Repos to Try:
https://github.com/far-horizons-ou/sveltekit-tailwind-auth0-starter  -  Not working
https://github.com/navneetsharmaui/sveltekit-starter




UIKits - https://github.com/huntabyte/shadcn-svelte
 - https://github.com/melt-ui/melt-ui


##### Interesting Ones
https://github.com/tradingstrategy-ai/frontend
- very full feature frontend; shows what can be done with svelte

Svelte UI Libraries - lots of activity here; 
- SkeletonUI, 
- ports of shadcn/ui

#### NextJS Starters
#1 = taxonomy
https://github.com/shadcn/taxonomy (forked as https://github.com/bnapora/taxonomy-stack)
Pros: uses the technology (including shadcn); good dev
Issues: doesn't run without bugs; not well supported
ToDo: Run with ALL env vars filled out.

#1b = next-app-starter
https://github.com/jellydn/next-app-starter (forked as https://github.com/bnapora/next-app-starter)
Pros: uses technology stack; uses shadcn/ui; storybook; updated by dev; got email auth to work; react forms;
Issues: not much sample UI; storybook
ToDo: test copying a shadcn/ui example to it.

#2 = start-ui-web 
https://github.com/BearStudio/start-ui-web (forked as https://github.com/bnapora/nextjs-ui-starter)
- full feature; works well; only downside is using ChakraUI; custom authentication
- add theme to ChakraUI (https://github.com/abds4816/chakra-ui-theme)

#3 = precedent
https://github.com/steven-tey/precedent (forked as https://github.com/bnapora/fastapi-nextjs-stack)
Pros: uses the technology; looks nice; good dev
Issues: can't get shadcn/ui to integrate
ToDo: try to integrate "shadcn/next-template" since has same structure



#4 = tauri-ui
https://github.com/agmmnn/tauri-ui
Pros: nice implementation of shadcn; has samples

#5 = https://github.com/shadcn/next-template
Pros: Nice clean shadcn template
Issues: No auth; Prisma

#6 = https://github.com/AntonioErdeljac/next13-ecommerce-admin.git
Pros: runs; advanced shadcn ui; SOA nextjs config; demo of Clerk integration
Issues: uses clerk auth (not generic auth)

https://github.com/jhavej/turbo-starter
Pros: clean look/feel; auth works easily; nice roadmap
Issues: not many features; but what's there works

*** https://github.com/sharjilk/next-dashboard
Pros: shadcn, left side nav, auth screen
Issues: no auth

*** https://github.com/Sazzad-Anwar/shadcn-admin-panel
Pros: sahdcn, couldn't see admin,
Issues; auth installed but not working (watch for updates)

https://github.com/ixartz/Next-js-Boilerplate
Pros: Works, 
Issues: No admin; no prisma, no auth; entrypoint for premium themes
https://creativedesignsguru.com/

https://github.com/jotyy/Mantine-Admin
Pros: Nice sidebar nav, good dev documentation, use as reference
Issues: not using shadcn/ui




#### Starters To Review:  

https://github.com/luisFilipePT/shadcn-ui-theme-explorer - nice; no auth or db connection; can it be ported to another framework?
https://github.com/UnbreakableKid/turborepo-shadcn-storybook - no ui configured
https://github.com/wangfengyuan/frontend-nav





Other FrontEnd Starters Tried:
https://github.com/theodorusclarence/ts-nextjs-tailwind-starter

#### Vite + React Starters

#1 https://github.com/Sairyss/fullstack-starter-template
- Pros: uses monorepo build tool (NX), Admin portal, backend/frontend seperation, login ui, 
- Issues: Storybook integ not working; outdated dependencies (6 mo old); good outline to follow, using ChakraUI instead of Radix

#2 - https://github.com/Overdrive141/vite-shadcnui-boilerplate - example is table; 


https://github.com/oedotme/render - ***
- Pros: Looks pretty good, very quick, 
- Issues: No prisma, auth, storybook, shadcn
- TODO - attempt to integrate Tailwind & shadcn/ui

https://github.com/esafwan/dashboard-starter - react/vite framework; looks like shadcn; bare-bones, but small; doesn't appear to have auth or prisma

https://github.com/dan5py/react-vite-ui - didn't work

https://github.com/ychengcloud/react-vite-admin - works, uses Ant Design components, internationalization, login, has left sidebar
- Issues: 2 years old, not actively supported, no db

https://github.com/marmelab/react-admin
https://github.com/Zoot01/sentrify-dashboard

#### List of App Starers
https://medevel.com/16-os-saas/
- some good ones on list


#### Opensource Starter Applications
https://github.com/async-labs/saas
https://github.com/blitz-js/blitz
https://github.com/graphile/starter
https://github.com/saas-js/saas-ui

#### Healthcare Related Starters
https://github.com/kakoni/awesome-healthcare#applications
https://github.com/medplum/medplum - looks promising.
https://github.com/hikmahealth
https://github.com/medblocks/medblocks-ui

#### Applications
https://github.com/ever-co/ever-gauzy - full feature, written in Angular
https://github.com/ixahmedxi/noodle - tasks, calendar, could be used for datset management; Loaded, not functionality yet
https://github.com/refinedev/refine

#### UI Component Libraries
Mantine
Chakra

#### Meta Meta-Frameworks
NextJS
- Tutorials
https://www.youtube.com/watch?v=5miHyP6lExg&t=46s

Redwoodjs
Remix
- https://remix.run/docs/en/1.18.1/tutorials/jokes
Blitzjs
- Tutorial: https://blitzjs.com/docs/tutorial
Solidjs

#### Tech Stack Outlines:
FastAPI, React, Vite

### TODO 
(071023)
[x] Search for largest opensource applications on GitHub 
[] Review latest version of Django documentation
[] React, Vite, Auth, Prisma, Tailwind, Shadcn/ui, 
    - example of pulling data from Postgres db.
    - example of sidebar/topbar nav
    - example of auth
    - example of datagrid

### Research Summary
Starter Kit: shadcn/taxonomy (bnapora/taxonomy-stack)
Pros: shadcn, prisma, auth, dashboard (link not built), project structure
Issues: minimal dev tools, no axios/api integration
Dashboard: integrate into
    https://github.com/sharjilk/next-dashboard
    Features: i8n, DataGrid, style, Generic Email auth

    https://github.com/Sazzad-Anwar/shadcn-admin-panel  
    Features: logon screen

Other Features:

    https://github.com/jellydn/next-app-starter (forked as https://github.com/bnapora/next-app-starter)
    Features: next_auth email config, dev tooling (React Query, Forms, etc)

    https://github.com/steven-tey/precedent (forked as https://github.com/bnapora/fastapi-nextjs-stack)
    Features: nextauth github config

Dev Library Integrations
1. Blitzjs for next - https://blitzjs.com/
    * adding prisma tools, data discovery
1. Refine - https://refine.dev/
    * for CRUD opperations

















