# Comparison
Feature/Capability Key:

- ✅ 1st-class, built-in, and ready to use with no added configuration or code
- 🟡 Supported, but as an unoffical 3rd party or community library/contribution
- 🔶 Supported and documented, but requires extra user-code to implement
- 🛑 Not officially supported or documented.

|                                                    | [React Query](https://react-query.tanstack.com/overview)                              | [SWR](https://swr.vercel.app/zh-CN)     | [Apollo Client(React)](https://www.apollographql.com/docs/react/)   | [RKT Query](https://rtk-query-docs.netlify.app/introduction/getting-started/)   |
| -------------------------------------------------- | ---------------------------------------- | -------------------------- | ------------------------------------- | ------------------------------------ |
| Github Repo / Stars                                | [![][stars-react-query]][gh-react-query] | [![][stars-swr]][gh-swr]   | [![][stars-apollo]][gh-apollo]        | [![][stars-rtk-query]][gh-rtk-query] |
| Platform Requirements                              | React                                    | React                      | React, GraphQL                        | Redux                                |
| Their Comparison                                   |                                          | (none)                     | (none)                                | [Comparison][rtk-query-comparison]   |
| Supported Query Syntax                             | Promise, REST, GraphQL                   | Promise, REST, GraphQL     | GraphQL                               | Promise, REST, GraphQL               |
| Supported Frameworks                               | React                                    | React                      | React + Others                        | Any                                  |
| Supported Query Keys                               | JSON                                     | JSON                       | GraphQL Query                         | JSON                                 |
| Query Key Change Detection                         | Deep Compare (Stable Serialization)      | Referential Equality (===) | Deep Compare (Unstable Serialization) | Referential Equality (===)           |
| Query Data Memoization Level                       | Query + Structural Sharing               | Query                      | Query + Entity + Structural Sharing   | Query                                |
| Bundle Size                                        | [![][bp-react-query]][bpl-react-query]   | [![][bp-swr]][bpl-swr]     | [![][bp-apollo]][bpl-apollo]          | [![][bp-rtk-query]][bpl-rtk-query]   |
| API Definition                                     | On-Use, Declarative                      | On-Use                     | GraphQL Schema                        | Declarative                          |
| Queries                                            | ✅                                       | ✅                         | ✅                                    | ✅                                   |
| Caching                                            | ✅                                       | ✅                         | ✅                                    | ✅                                   |
| Devtools                                           | ✅                                       | 🟡                         | ✅                                    | ✅                                   |
| Polling/Intervals                                  | ✅                                       | ✅                         | ✅                                    | ✅                                   |
| Parallel Queries                                   | ✅                                       | ✅                         | ✅                                    | ✅                                   |
| Dependent Queries                                  | ✅                                       | ✅                         | ✅                                    | ✅                                   |
| Paginated Queries                                  | ✅                                       | ✅                         | ✅                                    | ✅                                   |
| Infinite Queries                                   | ✅                                       | ✅                         | ✅                                    | 🛑                                   |
| Bi-directional Infinite Queries                    | ✅                                       | 🔶                         | 🔶                                    | 🛑                                   |
| Infinite Query Refetching                          | ✅                                       | ✅                         | 🛑                                    | 🛑                                   |
| Lagged Query Data<sup>1</sup>                      | ✅                                       | 🛑                         | 🛑                                    | ✅                                   |
| Selectors                                          | ✅                                       | 🛑                         | ✅                                    | ✅                                   |
| Initial Data                                       | ✅                                       | ✅                         | ✅                                    | ✅                                   |
| Scroll Recovery                                    | ✅                                       | ✅                         | ✅                                    | ✅                                   |
| Cache Manipulation                                 | ✅                                       | ✅                         | ✅                                    | ✅                                   |
| Outdated Query Dismissal                           | ✅                                       | ✅                         | ✅                                    | ✅                                   |
| Render Optimization<sup>2</sup>                    | ✅                                       | 🛑                         | 🛑                                    | ✅                                   |
| Auto Garbage Collection                            | ✅                                       | 🛑                         | 🛑                                    | ✅                                   |
| Mutation Hooks                                     | ✅                                       | 🟡                         | ✅                                    | ✅                                   |
| Offline Mutation Support                           | ✅                                       | 🛑                         | 🟡                                    | 🛑                                   |
| Prefetching APIs                                   | ✅                                       | 🔶                         | ✅                                    | ✅                                   |
| Query Cancellation                                 | ✅                                       | 🛑                         | 🛑                                    | 🛑                                   |
| Partial Query Matching<sup>3</sup>                 | ✅                                       | 🛑                         | 🛑                                    | ✅                                   |
| Stale While Revalidate                             | ✅                                       | ✅                         | 🛑                                    | ✅                                   |
| Stale Time Configuration                           | ✅                                       | 🛑                         | 🛑                                    | 🛑                                   |
| Pre-usage Query/Mutation Configuration<sup>4</sup> | ✅                                       | 🛑                         | 🛑                                    | ✅                                   |
| Window Focus Refetching                            | ✅                                       | ✅                         | 🛑                                    | 🛑                                   |
| Network Status Refetching                          | ✅                                       | ✅                         | ✅                                    | 🛑                                   |
| General Cache Dehydration/Rehydration              | ✅                                       | 🛑                         | ✅                                    | ✅                                   |
| Offline Caching                                    | ✅ (Experimental)                        | 🛑                         | ✅                                    | 🔶                                   |
| React Suspense (Experimental)                      | ✅                                       | ✅                         | 🛑                                    | 🛑                                   |
| Abstracted/Agnostic Core                           | ✅                                       | 🛑                         | ✅                                    | ✅                                   |
| Automatic Refetch after Mutation<sup>5</sup>       | 🔶                                       | 🔶                         | ✅                                    | ✅                                   |
| Normalized Caching<sup>6</sup>                     | 🛑                                       | 🛑                         | ✅                                    | 🛑                                   |