# RPTrainor01

## How to build a React app with perfect 100/100 Lighthouse scores

**This actually works**

* Go to https://rptrainor01.pages.dev 
* Open an incognito Chrome browser window
* Run the Lighthouse test
* And observe 100 out of 100 Lighthouse scores across the board

It's not magic, and I will teach you how to do it too, in these 3 easy steps:
1. Create and deploy your app — with one command
2. Style your app
3. Add your integrations

And you can do it too! Let's get started

## First run:

```bash
pnpm create cloudflare@latest my-app-name
```

Follow the prompts:

```
╰ What would you like to start with?
  ○ Hello World example
  ● Framework Starter
  ○ Application Starter
  ○ Template from a Github repo

  Select from the most popular full-stack web frameworks 

╰ Which development framework do you want to use?
  ○ Analog
  ○ Angular
  ● Astro
  ○ Docusaurus
  ○ Gatsby
  ○ Hono
  ○ Next
  ○ Nuxt
  ○ Qwik
  ○ React
  ○ Remix
  ○ Solid
  ○ Svelte
  ○ Vue
  ◁ Go back

  tmpl   How would you like to start your new project?
         ● Include sample files (recommended)
         ○ Use blog template
         ○ Empty

    ts   Do you plan to write TypeScript?
         ● Yes  ○ No

   use   How strict should TypeScript be?
         ● Strict (recommended)
         ○ Strictest
         ○ Relaxed

   git   Initialize a new git repository? (optional)
         ● Yes  ○ No

╰ Do you want to deploy your application?
  Yes / No
```

After successful deployment, you'll see:

```
│ 🎉  SUCCESS  Application deployed successfully!                                           │
│                                                                                           │
│ 🔍 View Project                                                                           │
│    Visit: https://rptrainor01.pages.dev                                          │
│    Dash: https://dash.cloudflare.com/?to=/:account/workers/services/view/rptrainor0 │
│                                                                                           │
│ 💻 Continue Developing                                                                    │
│    Change directories: cd rptrainor0                                                │
│    Start dev server: pnpm run dev                                                         │
│    Deploy again: pnpm run deploy                                                          │
│                                                                                           │
│ 📖 Explore Documentation                                                                  │
│    https://developers.cloudflare.com/pages                                                │
│                                                                                           │
│ 💬 Join our Community                                                                     │
│    https://discord.cloudflare.com
```

Now your app is live on the Internet! Time to style your app.

## Styling your app

I recommend using TailwindCSS because of its performance optimizations that allow you to send the smallest possible .css file to the client and keep the page load time low.

Run:

```bash
pnpm astro add tailwind
```

Answer `Y` or yes to the prompts, and TailwindCSS is added to your app.

From here, you can update the content of your page.

## Adding integrations

You can add whatever other integrations you need:

**React:**
```bash
pnpm astro add react
```

**Database:**
```bash
pnpm astro add db
```

And more...