# Sauce Demo Bug Reports

**Application:** [Sauce Demo](https://www.saucedemo.com)
**Tester:** Raghav Raj
**Testing Period:** August 2026
**Browser:** Chrome v137.0.7151.79
**Device:** iPhone 13  (iOS 18.5)
**Total Bugs Found:** 6
**User Accounts Tested:** standard_user, locked_out_user, performance_glitch_user, problem_user, error_user, visual_user

---

## Bug Summary

| Bug ID | Title | User Account | Severity | Priority |
|---|---|---|---|---|
| [STAND-01](./STAND-01-special-chars-accepted-checkout.md) | Special characters accepted in name and zip code fields at checkout | standard_user | High | High |
| [LOCK-01](./LOCK-01-locked-out-user-login-error.md) | Login returns locked-out error message | locked_out_user | High | Low |
| [PERF-01](./PERF-01-login-delay-20-30-seconds.md) | Login delay of 20-30 seconds before inventory loads | performance_glitch_user | Medium | High |
| [PERF-02](./PERF-02-special-chars-accepted-checkout.md) | Special characters accepted in name and zip code fields at checkout | performance_glitch_user | High | High |
| [PROB-01](./PROB-01-image-mismatch-inventory-vs-detail.md) | Image mismatch between inventory page and product detail page | problem_user | Medium | Medium |
| [PROB-02](./PROB-02-3-of-6-items-cannot-add-to-cart.md) | 3 out of 6 items cannot be added to cart | problem_user | High | High |

---

## Severity Breakdown

| Severity | Count |
|---|---|
| Critical | 3 |
| High | 2 |
| Medium | 1 |
| Low | 0 |
