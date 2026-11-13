# Rashed | Arabic Voice AI Agent

Rashed is an Arabic voice agent I built independently with ElevenLabs
for a fictional Saudi motor insurance company as a Sarj AI take-home challenge.

**[Watch the demo on Loom](https://www.loom.com/share/b7435f3910fd434ca666eaf3bbfffe5a)**

## What I built

- Designed an Arabic conversation flow for motor insurance inquiries
  and accident-reporting guidance.
- Configured a knowledge base to support the agent's responses.
- Tested a multi-turn accident scenario covering an initial safety check,
  follow-up questions, and a recap of the caller's details.

  ## Demo Test

- **Scenario:** A caller reports a minor accident and has no report number.
- **Observed behavior:** Rashed checked for injuries first, asked follow-up
  questions, continued without a report number, and summarized the incident.
- **Improvement identified:** Validate the phone number format before accepting it.
