# CampusConnect · IIT Guwahati

A clickable prototype of a club and event discovery app for IIT Guwahati.

**Try it:** https://prashantkumarsingh2903-bit.github.io/campusconnect-iitg/

It runs entirely in the browser. There's no backend, and all data is sample data.

## What's in it

- **Getting in:** sign in with an IITG email, then a code. The app asks *"Are you on a club team?"*.
- **Students:**
  - Explore clubs by board and read a club page.
  - Register for events.
  - Plan your week on a calendar with reminders.
  - Read the club-only feed.
  - Join rooms (chat, voice and video).
- **Verifying a club role:** pick your club and role, then check your roll number.
  - The club's Secretary approves members and core team.
  - The Gymkhana Council approves Secretaries.
  - A marked demo button plays the approver.
- **Club teams:**
  - Members and core team write drafts and discuss them.
  - The **Secretary** publishes them, runs recruitment and manages the team.
- **Rooms:** only club members can start a room. Everyone can join open rooms.

## Roles

| | Student | Member | Core team | Secretary |
|---|---|---|---|---|
| Follow, register, comment, ask, apply, join rooms | ✓ | ✓ | ✓ | ✓ |
| Write drafts (posts, events, club page) | | ✓ | ✓ | ✓ |
| Start rooms | | ✓ | ✓ | ✓ |
| Read applications and add notes | | | ✓ | ✓ |
| Publish, run recruitment, manage the team | | | | ✓ |

## Try both sides

- Sign in with `prashant.kumar.singh@iitg.ac.in`. You're found on two club rosters: Secretary of Photography and Member of Music.
- Any other `@iitg.ac.in` email signs in as a student. You can verify a club role from there.
- Any 6 digits work as the code.

## Files

- `index.html`: the whole prototype (HTML, CSS and JS in one file).
- `img/`: club illustrations.
