# Momentum Privacy Policy

**Last updated:** May 28, 2026  
**Effective date:** May 28, 2026

This Privacy Policy describes how Momentum ("Momentum", "we", "us", or "our") collects, uses, and shares information when you use the Momentum mobile application and any related services (collectively, the "Service"). By using the Service you agree to this Policy.

If you have questions about this Policy, email **privacy@momentum.app**.

---

## 1. Who we are

Momentum is operated by **Mincimouse** (referred to here as "we" / "us"). For postal or data-protection correspondence, email **privacy@momentum.app** and we will provide a mailing address where required by law.

If you are an EU/UK resident, our contact point for data-protection questions is the same email address listed above.

---

## 2. Information we collect

We try to collect as little as possible. The categories below are exhaustive — we do not collect anything not listed here.

### 2.1 Information you provide directly

- **Account information:** email address, password (stored only as a one-way hash by our authentication provider), display name, optional username, optional profile photo.
- **Goal, habit, and task content:** goals, milestones, habits, tasks, check-ins, daily logs, wins, blockers, mood and energy ratings, journal-style reflections.
- **Fitness and health logs:** workouts, exercises, sets, weights, reps, food logs, body measurements, and any free-text notes you attach.
- **Social graph (optional):** friendships you initiate, friend requests you accept, and content you choose to share with friends.
- **AI coach conversations:** the messages you send to your AI coach, plus a small set of "memories" the coach automatically extracts from those conversations (e.g. "user prefers morning workouts").
- **Support correspondence:** anything you send us by email.

### 2.2 Information collected automatically

- **Device and app diagnostics:** operating system, app version, locale, time zone, anonymous error reports.
- **Usage events:** which features you used, how often, and aggregate counts for AI features (used to enforce the per-tier daily limits described in the in-app Settings → Plan section). We do not record the content of any AI response server-side beyond the token counts needed for billing.
- **Push token (optional):** if you grant permission, we store an Expo / Apple push notification token so we can deliver coach nudges and habit reminders.
- **Crash logs:** if the app crashes, the operating system may send us a stack trace through Apple's own crash reporting pipeline. These reports do not contain your personal data.

### 2.3 Information from third parties

- **In-app purchase events** from RevenueCat (our subscription provider), including which subscription you purchased, its renewal status, and a RevenueCat customer ID. We do **not** receive your full payment card information from Apple or Google.

---

## 3. How we use information

We use the information above only to:

1. **Provide the Service.** Run your account, store your goals/habits/logs, surface them across your devices.
2. **Operate the AI coach.** Forward your messages and the context you've granted (goals, habits, recent logs, prior coach memories) to our AI model providers so they can generate a reply.
3. **Enforce plan limits.** Count AI requests against the daily caps described in Settings → Plan.
4. **Send notifications you've opted in to.** Daily habit reminders, weekly review prompts, AI coach nudges.
5. **Process subscriptions.** Reconcile RevenueCat purchase events with your account so the right plan is active.
6. **Improve the Service.** Aggregate, anonymous usage patterns. We do not train AI models on your personal data.
7. **Keep the Service safe.** Detect abuse, fraud, or violations of our Terms of Service.
8. **Comply with the law.** When we receive a binding legal request and have no good-faith basis to refuse.

We do **not** sell your personal information, and we do **not** use it for cross-context behavioral advertising.

---

## 4. AI model providers

When you use an AI feature, the relevant content (your message, plus the minimum context needed to produce a useful reply) is sent to a third-party AI model provider on our behalf. As of this Policy's effective date that provider is **OpenAI**, and we run requests through our own server proxy so your account credentials never reach the model provider directly.

The providers we use have contractually committed to:

- Not training their public models on the data we send via the API.
- Retaining the data for no longer than 30 days for abuse-monitoring purposes (often less).

We will list any additional or replacement AI providers in this section when we add them.

---

## 5. Where data lives

Your account, content, and usage events live in a managed PostgreSQL database operated by **Supabase, Inc.** in the AWS region closest to you at the time of sign-up (usually `us-east-1` or `eu-central-1`). Profile photos are stored in Supabase Storage in the same region.

Subscription events are processed by **RevenueCat, Inc.** in the United States.

Push notifications are delivered via **Apple Push Notification Service** (Apple Inc.) or **Firebase Cloud Messaging** (Google LLC) depending on your device.

If you are an EU/UK resident, your data may be transferred to the United States or other countries that do not provide an equivalent level of data-protection law. We rely on the European Commission's Standard Contractual Clauses (or the equivalent UK IDTA) for these transfers.

---

## 6. How long we keep it

- **Active accounts:** for as long as you keep the account.
- **AI usage counters:** rolling 30 days (older buckets are pruned automatically).
- **Coach memories:** until you delete them from Settings → Coach memory or delete your account.
- **Backups:** Supabase retains rolling encrypted backups for up to 30 days after deletion; these are overwritten on schedule.
- **Closed accounts:** we delete your account data within 30 days of your deletion request. Some derived, fully-anonymous usage counts may persist indefinitely in aggregate analytics.

---

## 7. Your rights

Regardless of where you live, you can:

- **Access** your data: tap Settings → Data → Export to receive a complete JSON archive on-device.
- **Edit** your data: every screen that shows your data lets you change or delete it.
- **Delete** your account: Settings → Sign out & Delete → Delete my account. This is irreversible and removes your goals, habits, logs, coach history, and account record on our servers.
- **Withdraw notification consent:** OS settings → Momentum → Notifications.

If you are in the EU/UK, you additionally have the right to lodge a complaint with your local data-protection authority. We'd appreciate you reaching out to us first so we can address the issue directly.

If you are in California, you have rights under the CCPA/CPRA including the right to know what we collect (this Policy), the right to delete (see above), the right to correct, the right to limit use of sensitive personal information, and the right not to be discriminated against for exercising these rights. We do not sell or "share" personal information for cross-context behavioral advertising.

---

## 8. Children

Momentum is not directed at children under 13 (or the relevant age of digital consent in your jurisdiction — 16 in some EU countries). We do not knowingly collect data from children under that age. If you believe a child has provided us data, email **privacy@momentum.app** and we will delete it.

---

## 9. Security

We use industry-standard practices including TLS in transit, encryption at rest at the storage layer, hashed passwords, scoped row-level security policies on every database table, and access controls on our admin tooling. No system is perfectly secure; if we ever become aware of a breach affecting your account we will notify you and, where applicable, the relevant authorities.

---

## 10. Changes to this Policy

We may update this Policy from time to time. When we make material changes we will (a) update the "Last updated" date at the top, (b) notify you in-app on next launch, and (c) for material changes, send an email to the address on file. Continued use of the Service after a change means you accept the new Policy.

---

## 11. Contact

Privacy questions, data-subject requests, or anything else this Policy doesn't cover:

**Email:** privacy@momentum.app
