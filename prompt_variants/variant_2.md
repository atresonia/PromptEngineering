# Variant 2 (Provide Context)
<transcript>
[paste turn-numbered transcript]
</transcript>

# Context
This is an auto-transcribed requirements interview for a portal for the
International Football Association (IFA). spk_1 is the client, an IFA
representative. spk_0 and spk_2 are analysts. Engineers will build from your
document without hearing the call. Three things make the transcript unreliable,
and each becomes a bug if it lands in the spec:
- The analysts guess, propose features and restate the client. Sometimes the
  client corrects them; sometimes nobody does.
- The transcription has errors: misheard words and broken sentences.
- The client sometimes defers a topic or calls it a future idea.
Only the client's own statements, or analyst proposals the client explicitly
confirms, are requirements.

# Instructions
Write the requirements document.

# Output format
1. Summary (3 sentences)
2. Roles and permissions: Role | Can do | Cannot do
3. Functional requirements by area: ID | Requirement | Phase (only as the
   client stated it)
4. Non-functional requirements (performance, localization, security)
5. Rejected: analyst proposals the client turned down
6. Future or deferred items
7. Open questions, each with why it's open
8. Transcription fixes: misheard words you corrected, and what you assumed

# Constraints
- If the client never confirmed it, it is not a requirement.
- Don't invent numbers, dates or features.