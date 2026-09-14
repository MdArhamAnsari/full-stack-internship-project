# Accessibility Baseline & Repository Architecture Audit

## 1. Audit Overview

This document records a focused accessibility audit of the Airtel public-facing website.

**Audited Website:** Airtel India  
**Audit Method:** Google Chrome Lighthouse + Keyboard-only navigation  
**Audit Focus:** Accessibility baseline and keyboard navigation

---

## 2. Lighthouse Accessibility Audit

The website was tested using Google Chrome Lighthouse.

### Result

**Accessibility Score: 99/100**

The Lighthouse result indicates a strong accessibility baseline for the audited page.

### Evidence

See:

`screenshots/lighthouse-accessibility-99.png`

---

## 3. Keyboard-Only Navigation Audit

A manual keyboard-only navigation pass was performed using the `Tab` key.

### Observation

The keyboard focus was visible while navigating through the website.

For example, the **Postpaid** navigation item displayed a clear focus outline when it received keyboard focus.

### Result

**Status: Pass**

A visible focus indicator was observed during keyboard navigation.

### Evidence

See:

`screenshots/keyboard-navigation-focus.png`

---

## 4. Accessibility Findings

| Area | Finding | Severity | Priority |
|---|---|---|---|
| Lighthouse | Accessibility score of 99/100 | Low | Low |
| Keyboard Navigation | Visible focus indicator observed | Pass | N/A |

No specific critical accessibility failure was identified during the documented checks.

---

## 5. Remediation Recommendations

Although the audited page achieved a high accessibility score, accessibility should continue to be verified through:

- Keyboard-only testing
- Screen-reader testing
- Color and contrast checks
- Semantic HTML review
- Automated Lighthouse audits

---

## 6. Evidence

The following evidence is included in the repository:

1. Lighthouse accessibility result
2. Keyboard navigation focus state

All evidence is stored in the `screenshots/` directory.

---

## 7. Conclusion

The audited Airtel page demonstrated a strong accessibility baseline with a Lighthouse accessibility score of 99/100 and visible keyboard focus during manual keyboard navigation.

The repository also provides a maintainable monorepo-style foundation with separate client, server, documentation, screenshots, and testing directories.
