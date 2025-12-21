# alx-graphql-0x02

## alx-rick-and-morty-app

### Application of GraphQL in React (Next.js)

This project, `alx-rick-and-morty-app`, is a hands-on exercise designed to kickstart the integration of **GraphQL** data fetching into a modern **React** application built using the **Next.js** framework. It leverages **Apollo Client** to consume the public Rick and Morty GraphQL API.

### Objectives

The primary goals of this project are:

1.  Set up a new Next.js project using **TypeScript**, **ESLint**, and **Tailwind CSS**.
2.  Integrate and configure **Apollo Client** for connecting to a GraphQL endpoint.
3.  Define a sample GraphQL query to fetch episode data.
4.  Wrap the entire application with the **`ApolloProvider`** for global data access.

### Technology Stack

| Component | Description |
| :--- | :--- |
| **Framework** | Next.js |
| **Language** | TypeScript |
| **Styling** | Tailwind CSS |
| **GraphQL Client** | `@apollo/client` |
| **GraphQL API** | [Rick and Morty API](https://rickandmortyapi.com/graphql) |

### Getting Started

Follow these instructions to set up and run the project locally.

#### 1. Installation

First, ensure you are in the correct parent directory (`alx-graphql-0x01`), then navigate into the project folder.

```bash
# Navigate to the project directory
cd alx-graphql-0x01/alx-rick-and-morty-app

# Install all necessary dependencies
npm install

# Install Apollo Client and GraphQL types
npm install @apollo/client graphql
npm install --save-dev @types/graphql
