## Next.js App Router Course - Starter


pnpm dev

-> Next.Js automatically optimses the fonts using "next/font" module.It downloads font files at build time and hosts them with static assests. When user visits application, No additional requests for fonts.

-> Adding font to the Layout always:"<body className={`${inter.className} antialiased`}>{children}</body>"

-> if Page names loading.tsx in a folder, it automatically comes while loading when any page opening from folder.Its a fallback UI.
->When you create a new folder using parentheses (), the name won't be included in the URL path.So /dashboard/(overview)/page.tsx becomes /dashboard.

Streaming a component: creating a loading.tsx streams whole page, But if we want to stream component
-> Suspense allows you to defer rendering parts of your application until some condition is met (e.g. data is loaded). You can wrap your dynamic components in Suspense. Then, pass it a fallback component to show while the dynamic component loads.(Which means suspenese makes the UI reneder if data is loaded).







