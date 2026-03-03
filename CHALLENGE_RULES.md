# Challenge Rules — Proof Before Consequence

## What this is

This challenge is built around one claim:

> If execution can move faster than humans can intervene,  
> **governance has to exist in the runtime path.**  
> And if you can’t produce proof *before* consequence, you can’t defend what happened.

Judgement Spine turns execution-time governance into a portable, signed Evidence Pack.

This kit gives you three “Moments That Matter” (levels) and a verifier.

---

## Your objective

Pick any level and try to do the impossible:

**Change the decision record — and still pass verification.**

Examples:
- Turn `BLOCK` into `ALLOW` (Level 1)
- Remove canary/abort/rollback bounds (Level 2)
- Turn `ESCALATE` into `ALLOW` and “publish” (Level 3)

If your modified pack still verifies as authentic, you’ve forged execution‑time proof.

---

## What counts as “PASS”

A valid submission must:

1) **Verify successfully** using either:
   - `START_HERE.html` (browser verifier), or
   - `python3 verifier/verify_pack.py <pack-folder>`

2) **Contain a meaningful change** (not just metadata re-zipping).  
   You must change a real decision or safeguard:
   - outcome, bounds, authority chain, or exported artefact content.

3) **Stay within this kit**  
   This is an offline challenge. Do not target any external systems.

---

## What you’re allowed to do

Anything to the files inside a pack:
- edit JSON / TXT / PDFs
- reorder files
- re-zip
- try different tools, scripts, editors
- bring your best AI assistant

The verifier is the gate. Beat the gate.

---

## If you want to submit

Email **founder@judgementspine.com** with:

- the modified pack ZIP
- the verification output (copy/paste or screenshot)
- a short write‑up of the method

If you do it responsibly, you’ll be credited.

---

## Why this matters

Most “audit trails” are logs plus narrative.

This kit is different:

- a **pinned trust anchor** (public key fingerprint)
- a **signed manifest** (what should exist)
- **hash‑checked artefacts** (what actually exists)
- portable proof that survives dispute

That’s what “proof before consequence” looks like.
