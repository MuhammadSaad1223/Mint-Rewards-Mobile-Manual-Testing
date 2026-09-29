# Mint Rewards – Manual Mobile Testing (Android & iOS)

Manual testing project on the **Mint Rewards** mobile app. The goal was to find functional, UI, usability and cross-platform issues and report them in a clear bug report.

## Scope

| Item | Details |
|---|---|
| Application | Mint Rewards |
| Platforms | Android (Samsung, Android 15) and iOS |
| Test types | Functional, Usability, Compatibility, UI, Exploratory |
| Tested by | Muhammad Saad |
| Report date | 17-Aug-2026 |

## Result Summary

**12 bugs logged**

| Severity | Count |
|---|---|
| Critical | 0 |
| High | 3 |
| Medium | 5 |
| Low | 4 |

## Areas Covered

- Login and input validation (placeholder text, email whitespace, password length limit)
- Home screen UI (Your Deals section layout)
- Rewards and points (initial balance, deal eligibility)
- Session management (behavior after long time in background)
- Guest account flow
- Rapid tap behavior (duplicate dialogs)
- Cross-platform consistency (Deals vs Discounts naming)
- App-wide behavior (screen rotation, Dark Mode)

## Sample Bugs

| ID | Title | Severity |
|---|---|---|
| TC_BUG_003 | No maximum length limit on the Password field | High |
| TC_BUG_004 | UI overlap and layout break in the "Your Deals" section | High |
| TC_BUG_007 | Session does not expire after long background time | Medium |
| TC_BUG_009 | Duplicate dialogs on rapid repeated taps | Medium |

## Files

- `Mint_Rewards_Bug_Report_Android_iOS.xlsx` – full bug report with steps to reproduce, actual vs expected result, severity, priority and status
- `Screenshots/` – proof screenshots referenced in the report

## Bug Report Format

Each bug includes: Test Case ID, Title, Module, Platform, Preconditions, Steps to Reproduce, Actual Result, Expected Result, Severity, Priority, Status and Proof.

## Note

This project is for learning and portfolio purposes. Only findings from manual testing are included, and no confidential or personal data is shared.
