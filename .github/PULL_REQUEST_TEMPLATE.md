## ✅ Stage-0 Checklist
- [ ] Branch protection (main) requires PR review & status checks
- [ ] PR template autoloads these checkboxes and blocks merge if any [ ] remain
- [ ] Nightly workflow (`.github/workflows/nightly.yml`) executes a checkout-only sanity job and passes
- [ ] Feature flags (`flag_email_import`, `flag_pos_webhook`, `flag_stripe_billing`) exist in GrowthBook; server & client keys stored as GitHub Secrets
- [ ] Blue/Green Amplify – `prod-blue` and `prod-green` environments deployed; `scripts/swap-env.ts` toggles the live CNAME
