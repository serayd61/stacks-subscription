# Stacks Subscription

On-chain subscription management for SaaS on Stacks.

## Features
- Multi-tier subscriptions (Basic, Pro, Enterprise)
- Auto-renewal option
- Subscription extension
- Usage tracking

## Tiers
| Tier | Price/Month |
|------|-------------|
| Basic | 5 STX |
| Pro | 15 STX |
| Enterprise | 50 STX |

## Functions
```clarity
(subscribe (tier) (months))
(set-auto-renew (enabled))
(cancel-subscription)
(get-subscription (user))
(is-active (user))
```

## License
MIT



---
## Subscription Service
- ✅ Recurring payments
- ✅ Plan management
- ✅ On-chain billing
