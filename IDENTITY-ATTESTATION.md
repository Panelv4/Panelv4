# Identity attestation — `Panelv4` = Dhairya Sharma

> Purpose: allow a CNA, maintainer, bug-bounty programme or recruiter to verify that the handle credited as reporter on three CVEs belongs to the same person whose real name is Dhairya Sharma — **without** sending identity documents, private report details or personal contact information to anyone.

**How to use:** commit this file to the `Panelv4/Panelv4` profile repository (or publish it as a public Gist from the `Panelv4` account). The fact that it is published *from that account* is the proof. Optionally make the commit a verified/signed commit and link the commit SHA in your CNA request.

---

```text
IDENTITY ATTESTATION
Version: 1.0
Date: 25 November 2026

I, the owner and operator of the GitHub account https://github.com/Panelv4,
state that:

  1. My real name is Dhairya Sharma.
  2. The handle "Panelv4" refers to me and to no other person.
  3. I am based in Gwalior, Madhya Pradesh, India.
  4. I am the researcher credited as "reporter: Panelv4" on these
     publicly published security advisories:

       CVE-2026-120213 · GHSA-h3vp-4jfr-v364 · @fastify/http-proxy
       CVE-2026-117518 · GHSA-vp2r-3vgv-32g9 · @fastify/reply-from
       CVE-2026-116592 · GHSA-mqg3-3v4r-cm32 · undici
         (co-reporter: w116tjb)

  5. I am also the account behind https://hackerone.com/vibecoder.
     The GitHub handle "Panelv4" and the HackerOne handle "vibecoder"
     both refer to me, Dhairya Sharma: Panelv4 = vibecoder = Dhairya Sharma.
  6. Requests to render my credit as "Dhairya Sharma (Panelv4)" in
     CVE Records and GitHub Security Advisories originate from me.
     The existing "Panelv4" credit should be retained for continuity,
     and the other reporters' and remediation developers' credits must
     remain unchanged.

Verification anchors (all controlled by the same GitHub account):
  • https://github.com/Panelv4                     (display name: Dhairya Sharma)
  • https://github.com/Panelv4/Panelv4             (profile README)
  • https://github.com/Panelv4/CVE-Research-Dhairya-Sharma
  • https://github.com/Panelv4/Panelv4/blob/main/ALIASES.md   (alias resolution)
  • https://github.com/Panelv4/CVE-Research-Dhairya-Sharma/blob/main/FINDINGS.md
  • https://panelv4.github.io/DhairyaSharma/       (portfolio, JSON-LD Person)
  • This file's commit SHA: ______________________ (fill in after commit)

Contact for verification: dhairyasharma7101@gmail.com

Signed,
Dhairya Sharma  /  @Panelv4  /  vibecoder
```

---

### Optional stronger proof (no documents needed)

- **Signed commit:** `git commit -S -m "Add identity attestation"` and paste the verified commit URL into the email.
- **Cross-post:** publish the same statement as a Gist from `Panelv4` and link it from the profile README.
- **Reply-to-check:** offer to reply to the CNA from the address associated with the account, or to add a one-line confirmation to the advisory thread from `@Panelv4`.

### Privacy note

Do **not** attach school records, government ID, phone number or dates of birth to a public attestation or to a CNA email. The advisory credit plus an account-controlled statement is sufficient for a credit clarification.
