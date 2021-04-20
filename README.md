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
[bp-react-query]: https://badgen.net/bundlephobia/minzip/react-query
[gh-react-query]: https://github.com/tannerlinsley/react-query
[stars-react-query]: https://img.shields.io/github/stars/tannerlinsley/react-query

<!-- -->

[bp-swr]: https://badgen.net/bundlephobia/minzip/swr
[gh-swr]: https://github.com/vercel/swr
[stars-swr]: https://img.shields.io/github/stars/vercel/swr
[bpl-swr]: https://bundlephobia.com/result?p=swr

<!-- -->

[bp-apollo]: https://badgen.net/bundlephobia/minzip/@apollo/client
[gh-apollo]: https://github.com/apollographql/apollo-client
[stars-apollo]: https://img.shields.io/github/stars/apollographql/apollo-client
[bpl-apollo]: https://bundlephobia.com/result?p=@apollo/client

<!-- -->

[bp-rtk-query]: https://badgen.net/bundlephobia/minzip/@rtk-incubator/rtk-query
[gh-rtk-query]: https://github.com/rtk-incubator/rtk-query
[stars-rtk-query]: https://img.shields.io/github/stars/rtk-incubator/rtk-query
[bpl-rtk-query]: https://bundlephobia.com/result?p=@rtk-incubator/rtk-query

<!-- -->
[gh-react-use]: https://github.com/streamich/react-use
[stars-react-use]: https://img.shields.io/github/stars/streamich/react-use
