# Technical overview

The private delivery uses Django with Steam OpenID identity, Django ORM persistence and Stripe Checkout/webhook integration. The application models player profiles, virtual coin packages, transactions, game items and player slots.

## Public engineering boundary

The public showcase describes authentication, application-state and payment integration boundaries without publishing implementation source, identities, secrets or database content.
