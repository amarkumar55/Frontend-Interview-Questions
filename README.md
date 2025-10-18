# 📘 Frontend Interview Questions

> Here we are including global frontend interview questions to make it one source of true

---


## 💬  Questions & Answers

1. What is React, and what problem does it solve?
2. What is JSX? Can browsers directly understand JSX?
3. Explain the concept of a "component" in React.
4. What is the difference between a functional component and a class component?
5. What are "props" in React, and how are they used?
6. What is "state" in React, and why is it important?
7. How do you update the state of a component?
8. What is the "Virtual DOM," and how does React use it?
9. How do you render a React component to the actual DOM?
10. What is an event in React, and how do you handle events (e.g., `onClick`)?
11. Explain the "unidirectional data flow" in React. Why is it beneficial?
12. What are React Hooks? Name two commonly used Hooks.
13. How do you use the `useState` Hook? Provide a simple example.
14. Explain the purpose of the `useEffect` Hook. When does the effect function run?
15. What is the dependency array in `useEffect`, and what happens if you omit it or provide an empty array?
16. How do you pass data from a parent component to a child component?
17. How do you pass data from a child component to a parent component (e.g., using callbacks)?
18. What are "conditional rendering" and "list rendering" in React? How do you implement them?
19. Why are `key` props important when rendering lists in React?
20. What is "lifting state up" in React? When would you do it?
21. Explain the difference between controlled and uncontrolled components in React forms. When would you use each?
22. How do you optimize functional components to prevent unnecessary re-renders (e.g., `React.memo`, `useCallback`, `useMemo`)?
23. Describe the purpose of `useContext`. When would you use it instead of prop drilling?
24. How do you handle asynchronous operations (e.g., data fetching) in functional components?
25. Explain the concept of "refs" in React. When would you use them, and why should you generally avoid them?
26. What are "Fragments" in React, and why are they useful?
27. Discuss error boundaries in React. How do they work, and when would you implement them?
28. Explain the reconciliation process in React and how it optimizes UI updates.
29. How would you structure a large React application into components and folders?
30. What are "higher-order components" (HOCs)? When would you use them, and what are the alternatives (e.g., Hooks)?
31. Deep dive into the `useEffect` lifecycle. Explain its cleanup function and how it mimics `componentWillUnmount`.
32. Discuss the trade-offs between client-side rendering (CSR) and server-side rendering (SSR) for React applications.
33. How does React handle events internally (Synthetic Event System)? What are its advantages?
34. Explain how you would implement a custom Hook. Provide an example of a useful custom Hook.
35. What are the common challenges with state management in complex React applications, and what solutions are available (e.g., Redux, Zustand, Recoil)?
36. Discuss the importance of accessibility (A11y) in React applications and how you can ensure your components are accessible.
37. How would you test a React component (e.g., unit testing with Jest/React Testing Library, integration testing)?
38. Explain how React uses fiber reconciliation and concurrent mode (if familiar).
39. Describe a scenario where you would use `useReducer` instead of `useState` for state management.
40. What are the common performance pitfalls in React development, and how do you identify and resolve them?
41. What is Next.js, and how does it relate to React?
42. What is the main benefit of using Next.js over a plain React application created with Create React App?
43. Explain "Server-Side Rendering" (SSR) in Next.js.
44. Explain "Static Site Generation" (SSG) in Next.js.
45. How does Next.js handle routing? (File-system based routing)
46. How do you create a new page in a Next.js application?
47. What is the purpose of the `<Link>` component in Next.js?
48. How do you include images in Next.js, and what benefits does the `<Image>` component offer?
49. Where do you write CSS in a Next.js application?
50. What is the `public` directory used for in Next.js?
51. Explain the difference between `getStaticProps` and `getServerSideProps` in Next.js. When would you use each?
52. How does `getStaticPaths` work, and when is it necessary to use it with `getStaticProps`?
53. Describe the concept of "Automatic Static Optimization" in Next.js.
54. What are Next.js API Routes? When would you use them?
55. How do you handle environment variables in a Next.js application (client-side vs. server-side)?
56. What is the purpose of `_app.js` and `_document.js` files in the Pages Router?
57. How can you implement dynamic routes in Next.js (e.g., `/posts/[id].js`)?
58. Explain "Client-Side Rendering" (CSR) in the context of Next.js. When is it appropriate to use?
59. How does Next.js optimize image loading, and what features does the `next/image` component provide?
60. Discuss the role of `next/head` for managing metadata and SEO in Next.js pages.
61. Explain "Incremental Static Regeneration" (ISR) in Next.js. How does it combine the benefits of SSG and SSR?
62. Design a data fetching strategy for a complex Next.js application that balances performance, SEO, and real-time data needs.
63. How do you handle authentication in a Next.js application? Discuss server-side and client-side authentication patterns.
64. Explain the concept of "middleware" in Next.js. Provide a use case.
65. How do you handle error pages (e.g., 404, 500) in Next.js?
66. Discuss the advantages of using the Next.js `App Router` (introduced in Next.js 13) compared to the `Pages Router`.
67. Explain Server Components and Client Components in the App Router. What are their respective roles and benefits?
68. How can you optimize the performance of a Next.js application beyond basic data fetching and image optimization? (e.g., bundle analysis, lazy loading components).
69. Describe how you would deploy a Next.js application to a production environment (e.g., Vercel, AWS Amplify, self-hosting).
70. What are the considerations for internationalization (i18n) in a Next.js application?
71. Deep dive into the hydration process in Next.js. What are the potential pitfalls and how to avoid them?
72. Discuss the trade-offs between static exports (`next export`) and deploying a Node.js server for Next.js applications.
73. Explain the caching mechanisms in Next.js, including `fetch` caching, `revalidate`, and ISR.
74. How does Next.js handle data mutations and revalidation (e.g., using SWR, `router.refresh()`, `revalidatePath`)?
75. Describe how to implement "streaming" and "suspense" with data fetching in the Next.js App Router.
76. Analyze the impact of different rendering strategies on SEO, initial page load, and perceived performance.
77. How would you integrate a GraphQL API with a Next.js application, considering different data fetching patterns?
78. Discuss the architectural considerations for building a large-scale enterprise application using Next.js.
79. Explain the concept of "Route Handlers" in the App Router and how they differ from API Routes in the Pages Router.
80. What are the future directions of Next.js, especially with React Server Components and data fetching strategies?
