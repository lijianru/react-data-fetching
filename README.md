# Comparison
|                        | React Query                              | SWR                        | Apollo Client                         | RTK-Query                            | useAsync/useAsyncFn(react-use)       |
| -----------------------| ---------------------------------------- | -------------------------- | ------------------------------------- | ------------------------------------ | ------------------------------------ |
| Stars                  | [![][stars-react-query]][gh-react-query] | [![][stars-swr]][gh-swr]   | [![][stars-apollo]][gh-apollo]        | [![][stars-rtk-query]][gh-rtk-query] | [![][stars-react-use]][gh-react-use] |
| 平台需求                | React                                    | React                      | React, GraphQL                        | Redux                                | React                                |
| 支持的查询语法           | Promise, REST, GraphQL                   | Promise, REST, GraphQL     | GraphQL                               | Promise, REST, GraphQL               | Promise, REST, GraphQL               |
| 支持的框架               | React                                    | React                      | React + Others                        | Any                                  | React                                |
| 支持的查询键             | JSON                                     | JSON                       | GraphQL Query                         | JSON                                 | JSON                                 |
| 查询键变更检测           | Deep Compare (Stable Serialization)      | Referential Equality (===) | Deep Compare (Unstable Serialization) | Referential Equality (===)           | (none)                               |
| 查询数据记忆级别         | Query + Structural Sharing               | Query                      | Query + Entity + Structural Sharing   | Query                                | Query                                |
| 包大小                 | [![][bp-react-query]][bpl-react-query]   | [![][bp-swr]][bpl-swr]     | [![][bp-apollo]][bpl-apollo]          | [![][bp-rtk-query]][bpl-rtk-query]   | (none)                               |
| API定义                | On-Use, Declarative                      | On-Use                     | GraphQL Schema                        | Declarative                          | On-Use                               |


[bpl-react-query]: https://bundlephobia.com/result?p=react-query
[bp-react-query]: https://badgen.net/bundlephobia/minzip/react-query?label=💾
[gh-react-query]: https://github.com/tannerlinsley/react-query
[stars-react-query]: https://img.shields.io/github/stars/tannerlinsley/react-query?label=%F0%9F%8C%9F

<!-- -->

[swr]: https://github.com/vercel/swr
[bp-swr]: https://badgen.net/bundlephobia/minzip/swr?label=💾
[gh-swr]: https://github.com/vercel/swr
[stars-swr]: https://img.shields.io/github/stars/vercel/swr?label=%F0%9F%8C%9F
[bpl-swr]: https://bundlephobia.com/result?p=swr

<!-- -->

[apollo]: https://github.com/apollographql/apollo-client
[bp-apollo]: https://badgen.net/bundlephobia/minzip/@apollo/client?label=💾
[gh-apollo]: https://github.com/apollographql/apollo-client
[stars-apollo]: https://img.shields.io/github/stars/apollographql/apollo-client?label=%F0%9F%8C%9F
[bpl-apollo]: https://bundlephobia.com/result?p=@apollo/client

<!-- -->

[rtk-query]: https://rtk-query-docs.netlify.app/
[rtk-query-comparison]: https://rtk-query-docs.netlify.app/introduction/comparison
[bp-rtk]: https://badgen.net/bundlephobia/minzip/@reduxjs/toolkit?label=💾
[bp-rtk-query]: https://badgen.net/bundlephobia/minzip/@rtk-incubator/rtk-query?label=💾
[gh-rtk-query]: https://github.com/rtk-incubator/rtk-query
[stars-rtk-query]: https://img.shields.io/github/stars/rtk-incubator/rtk-query?label=%F0%9F%8C%9F
[bpl-rtk]: https://bundlephobia.com/result?p=@reduxjs/toolkit
[bpl-rtk-query]: https://bundlephobia.com/result?p=@rtk-incubator/rtk-query

<!-- -->
[gh-react-use]: https://github.com/streamich/react-use
[stars-react-use]: https://img.shields.io/github/stars/streamich/react-use?label=%F0%9F%8C%9F
