# jira-clone

## 01 Initialize Project

```
$ bunx create-next-app@14.2.4 jira-clone
```

## 02 Adding a component library

```
bunx --bun shadcn --version
2.3.0

$ bunx --bun shadcn@2.3.0 init
✔ Preflight checks.
✔ Verifying framework. Found Next.js.
✔ Validating Tailwind CSS.
✔ Validating import alias.
✔ Which style would you like to use? › New York
✔ Which color would you like to use as the base color? › Neutral
? Would you like to use CSS variables for theming? › yes

$ bunx --bun shadcn@2.3.0 add button
✔ Checking registry.
✔ Installing dependencies.
✔ Created 1 file:
  - src/components/ui/button.tsx
```

## 03 Customizing components

```
$ bunx --bun shadcn@2.3.0 add
avatar
badge
button
calendar
card
chart
checkbox
dialog
drawer
dropdown-menu
form
input
label
popover
scroll-area
select
separator
sheet
skeleton
sonner
table
tabs
text-area
```

Current: 34:02

## 04 Resolving lint errors

```
$ bun run build

No errors
```

Current: 39:12

## 05 Creating auth screens - Part 1

Current: 1:07:02

## 05 Creating auth screens - Part 2

```
$ bun add react-icons
```

Current: 1:24:06

## 05 Creating auth screens - Part 3

```
Adjustment of sign-in-card.tsx, sign-up-card.tsx, layout.tsx
```

Current: 1:34:19

## 06 Setting up Hono API - Part 1

```
$ bun add hono
```

## 06 Setting up Hono API - Part 2

Current: 1:48:13

## 07 Creating auth API - Part 1

```
bun add @tanstack/react-query@5.59.0

[https://tanstack.com/query/latest/docs/framework/react/guides/advanced-ssr#advanced-server-rendering]

bun add @hono/zod-validator

.env.local
NEXT_PUBLIC_APP_URL=http://localhost:3000
```

Current: 2:03:07

## 07 Creating auth API - Part 2

Current: 2:21:50

## 08 Setting up Appwrite & database

```
Auth / SSR Login
Server-SDK
Node.js SDK 14.1.0
$ bun add node-appwrite@14.1.0

Admin client / generate an API key
Integrate with your server / API key
Name: jira-clone
Auth / session.write users.write

...

Tutorial / Next.js SSR

$ bun add server-only

```

Current: 2:51:10

## 09 Building a session middleware - Part 1

Current: 3:01:48

## 09 Building a session middleware - Part 2

Current: 3:13:06

## 10 Learning how to protect routes - Part 1

```
[https://appwrite.io/docs/tutorials/nextjs-ssr-auth/step-7]
Auth / SSR login / Tutorials / Next.js SSR / OAuth authentication with SSR
```

Current: 3:21:27

## 10 Learning how to protect routes - Part 2

Current: 3:45:28

## 11 Building a dashboard layout - Part 1

Current: 3:51:06

## 11 Building a dashboard layout - Part 2

Current: 4:07:02

