# Contract Issues Backlog

## Issue: Implement policy-factory issuance and enrollment
**Labels:** `core`, `soroban`
**Description:** Develop the smart contract logic to instantiate new policy instances from predefined actuarial templates.
**Acceptance Criteria:**
- Validates premium payment before issuance.
- Stores policy metadata efficiently on-chain.

## Issue: Implement risk-pool deposit/withdrawal rules
**Labels:** `core`, `finance`
**Description:** Build the `risk-pool` crate to handle capital provider deposits and enforce solvency rules.
**Acceptance Criteria:**
- Correctly calculates LP shares.
- Locks withdrawals if pool solvency drops below the minimum threshold.

## Issue: Implement payout-engine trigger and release flow
**Labels:** `core`, `automation`
**Description:** Create the logic that accepts oracle data and automatically disperses funds to policyholders if conditions are met.
**Acceptance Criteria:**
- Verifies oracle signatures.
- Computes payout amounts deterministically.
- Executes payouts securely to policyholder addresses.

// patch: 2026-06-01T13:52:30

// patch: 2026-06-12T03:00:00

// patch: 2026-06-13T12:45:00

// patch: 2026-06-17T01:07:30

// patch: 2026-06-19T03:45:00
