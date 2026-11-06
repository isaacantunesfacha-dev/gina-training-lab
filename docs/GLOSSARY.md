# Glossary (Gina Intell UI)

| Term | Means | Not |
| --- | --- | --- |
| Priority queue | Organize tab list of customers who need a human today | inbox, alerts, leads |
| Observed | Median days between this customer's orders | cycle, frequency |
| Recency | Days since the last order | last seen, age |
| Ratio | Recency ÷ Observed, shown as `1.6×` | score, risk |
| In rhythm | Ratio ≤ 1.5×; no message | healthy, safe |
| Delay / Missed window | Ratio over 1.5× and up to 3.0× | late, at risk |
| Dormant | Ratio over 3.0×; 90-day rest, no task | churned, lost, critical |
| Owner task | The one open Salesforce Task Gina creates for human review | message, campaign, send |
| Create Owner Task | Action that creates the owner task | Send, Approve, Contact |
| Explain Decision | Opens the rule, numbers and reasoning for one row | Details, Why?, Info |
| Consent blocked | Customer revoked consent; never contacted | opted out, muted |
| Not on file | No documented consent yet; ask in store first | pending, unknown |
| Concierge human touch | VIP in delay; the owner contacts them personally | VIP campaign |
| Friendly nudge | Reminder based on past orders, no aggressive discount | promo, blast |
| Rule parity | Share of Apex results that match `crmMath.ts` | sync, accuracy |
| Receive / Organize / Connect / Complete | The four stages: new customers, queue, approved tasks, archive | — |
| Rhythm timeline | Customer page: orders, observed rhythm, boundaries, today | history chart, journey |
| Expected window | From the last order to 1.0× rhythm | due date, SLA |
| Rest | 90-day no-contact period after dormancy | pause, snooze, churn |
| How Gina got here | The four rule checks behind a decision | AI reasoning, model output |
| Decision artifact | `DA-…` record proving server and engine agree | receipt, log |
