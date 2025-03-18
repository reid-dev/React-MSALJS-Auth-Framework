# React-MSALJS-Auth-Framework

## Prerequisites

* An Azure account with an active subscription. If you don't already have one, Create an account for free.
* This Azure account must have permissions to manage applications. Any of the following Microsoft Entra roles include the required permissions:
    * Application Administrator
    * Application Developer
* Cloud Application Administrator
* A workforce tenant. You can use your Default Directory or set up a new tenant.

## React Steps

* Register a new app in the Microsoft Entra admin center with the following configuration and record its identifiers from the app Overview page and record its identifiers from the app Overview page. For more information, see Register an application.
* Name: identity-client-spa
* Supported account types: Accounts in this organizational directory only (Single tenant)
* Platform configuration: Single-page application (SPA)
* Redirect URI: http://localhost:3000/
* Node.js