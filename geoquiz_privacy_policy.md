# GeoQuiz Privacy Policy

**Effective date:** 07/01/2026
**Last updated:** 07/01/2026

GeoQuiz ("the App," "we," "us") is a location-based trivia app. This policy explains
what information the App collects, how it's used, and what choices you have. We've
written it to plainly match what GeoQuiz actually does — nothing more.

---

## 1. Information We Collect

### Location
GeoQuiz uses your device's location **only while the app is open and in use** (we do
not request or use background/"Always" location access). Your location is used to:
- Find nearby places via Wikipedia's public geosearch service, so the App can
  generate trivia about places near you.
- Calculate the distance and direction shown on screen (e.g. "900 ft to your east").

Your location is **not** stored on our servers, **not** linked to any personal
identifier, and **not** shared with advertisers. It is used in the moment, on your
device, to find places and is sent only to Wikipedia's API (as anonymous
coordinates) to look up nearby place names.

### Microphone & Speech Recognition (optional)
If you turn on "Answer by voice," GeoQuiz uses your device's microphone and Apple's
on-device Speech Recognition to let you answer trivia questions by saying a number
("one," "two," "three," "four"). This processing happens **on your device**; we do
not record, store, or transmit your voice audio to our servers. This feature is
off by default and requires your explicit permission.

### Trivia Question Requests
When the App needs a new trivia question, it sends the **name of the nearby place**
(e.g. "Boston Common"), your chosen difficulty and content style, and an approximate
distance/direction label to our backend (hosted on Supabase) so a question can be
generated or retrieved from our question bank. This request does **not** include
your precise coordinates, your name, your device's advertising identifier, or any
other personal identifier.

### Technical / Abuse-Prevention Data
To prevent abuse of our trivia-generation service, our backend temporarily logs the
IP address of requests and a request count, used only to apply rate limits (capping
how many questions can be requested per hour from a given IP). This data is not used
to identify individual users, is not sold, and is not shared with third parties
except as described below.

### What We Do NOT Collect
GeoQuiz has no user accounts, no login, no name or email collection, no advertising
identifiers, no third-party analytics SDKs, and no ad networks. We do not track you
across other apps or websites.

---

## 2. How We Use Information

We use the information above solely to:
- Find and display nearby places.
- Generate and serve trivia questions relevant to your location.
- Read questions and answers aloud (entirely on-device — no data leaves your phone
  for this feature).
- Prevent abuse/spam of our question-generation service.

We do not use your information for advertising, profiling, or any purpose unrelated
to running the App.

---

## 3. Third-Party Services

GeoQuiz relies on the following third-party services to function:

- **Wikipedia / Wikimedia APIs** — used to find nearby places and source factual
  background for trivia questions. Requests include only approximate coordinates,
  not any personal identifier. See [Wikimedia's privacy policy](https://foundation.wikimedia.org/wiki/Policy:Privacy_policy).
- **Supabase** — hosts our backend (the question bank and the service that
  generates new questions). See [Supabase's privacy policy](https://supabase.com/privacy).
- **Anthropic (Claude API)** — used server-side to generate new trivia question text
  from factual background material. Anthropic does not receive your location,
  device identifiers, or any personal information — only the place name and the
  factual material used to write the question. See [Anthropic's privacy policy](https://www.anthropic.com/legal/privacy).
- **Apple (on-device Speech Recognition & Text-to-Speech)** — used for the optional
  voice-answer and read-aloud features, processed on-device per Apple's own
  platform privacy terms.

We do not control these third parties' own data practices and encourage you to
review their policies if you have questions beyond what's described here.

---

## 4. Data Retention

- **Location**: never stored; used only in the moment on your device.
- **Voice audio**: never stored; processed on-device and discarded immediately
  after recognition.
- **Rate-limiting data (IP + request count)**: retained only as long as needed to
  enforce hourly limits, then rolls over/expires automatically.
- **Generated trivia questions**: stored in our question bank (tied to a place
  name, difficulty, and style — never tied to you personally) so they can be
  reused efficiently for future players.

---

## 5. Children's Privacy & Age Guidance

GeoQuiz is intended for users **13 and older**. We do not knowingly collect personal
information from children under 13, and the App is not directed at that age group.

GeoQuiz offers different content styles ("Family-friendly," "General," "Spicy").
None are intended to include explicit content, but "Spicy" leans into gossip,
scandal, and adult-flavored historical trivia in tone, which is why the App overall
is intended for users 13 and older rather than a younger audience.

**Driver Mode**: GeoQuiz includes a "Driver" play mode intended for use only by
someone who is a legally licensed driver, operating the vehicle lawfully, and
using the App in a manner consistent with all applicable traffic and distracted-
driving laws in their jurisdiction. GeoQuiz is not a substitute for safe driving
practices, and by selecting Driver mode, the user confirms they meet these
requirements. See the in-app Driver Safety notice shown before this mode is used.

---

## 6. Your Choices

- **Location**: You can deny or revoke location access at any time in iOS Settings
  → Privacy & Security → Location Services. The App's core trivia features require
  location to find nearby places.
- **Microphone / Speech Recognition**: voice-answering is optional and off by
  default; you can deny, revoke, or simply never enable it.
- **Read-aloud**: can be muted at any time within the App.

---

## 7. Changes to This Policy

We may update this policy as the App changes. We'll update the "Last updated" date
above when we do. Continued use of the App after a change means you accept the
revised policy.

---

## 8. Contact Us

Questions about this policy or how GeoQuiz handles information can be sent to:
devon.rogalski@gmail.com

---

_This policy is written to describe GeoQuiz's actual, current data practices. It is
not legal advice — if you plan a wide public launch, especially to users in the EU
(GDPR) or California (CCPA), consider a brief review by someone with relevant legal
expertise to confirm this fully meets those specific requirements._
