---
name: Bug Report
about: Something on the platform doesn't work as it should.
title: "<Summary> [Severity: <Critical | High | Medium | Low>]"
labels: bug
---

<!--
Severity:
- Critical. Production is down, or data is lost with no recovery.
- High. A crash or data loss, or no workaround.
- Medium. Wrong behaviour that has a workaround.
- Low. Cosmetic.
-->

## Description

<!-- What went wrong, as the person using it saw it. -->

**Frequency:** <!-- Every time | Sometimes | Once so far -->

**Component:** <!-- Mobile app | Device API | Tenant API | Web UI | Integration, e.g. FARO -->

**Cause:**

<!-- If it's known, otherwise "Not yet known". -->

**Effect on Data:**

<!-- What was lost, duplicated or left inconsistent, and whether it recovers on its own. -->

## Expected Behaviour

## Reproduction

**Environment:** <!-- Local | Staging | Production -->

**Version:** <!-- The commit, and whether it had uncommitted changes. -->

**Tenant:** <!-- UUID only. The slug names the customer. -->

**Reader:** <!-- Model and serial. Leave the line out when no reader is involved. -->

**Steps:**

1.

### Logs and Stack Trace

<!--
Remove tokens, passwords and personal data, e.g. names and email addresses.
Refer to a database row by its UUID rather than its name, e.g. a location or
a product, since a name can say who the customer is.
-->

```shell
```

## Resolution

**Proposed:**

**Actual:**

<!-- One commit as "**Related commit:** <hash>", several as "**Related commits:**" and a list. -->

**Related commit:**
