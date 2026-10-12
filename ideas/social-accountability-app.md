# Social Accountability App

An app where users set accountability goals backed by financial stakes — fail your goal, and money is automatically donated to an NGO of your choice.

## Details

- **Core loop:** Set a goal → commit an amount → verify completion (photo, check-in, or third-party data) → succeed (keep your money) or fail (donation is triggered automatically).
- NGO selection is user-driven: pick from a curated list of verified charities, making the stakes feel meaningful rather than punitive.
- **Social layer:**
  - Share goals publicly or with a private group of friends.
  - Friends can cheer, nudge, or hold you accountable with comments.
  - Streak tracking: visualize consecutive days/weeks of goal completion.
  - Leaderboards within friend groups to add friendly competition.
- **Verification approaches:**
  - Manual: user submits proof (photo, note); peers can vouch or dispute.
  - Automated: connect to health apps (Apple Health, Strava) for fitness goals, or GitHub activity for coding goals.
- **Payment flow:** Funds held in escrow (Stripe) at goal creation; released to the NGO on failure or returned on success.
- Potential partnerships with NGOs for co-marketing ("X users donated $Y to us via accountability goals").
