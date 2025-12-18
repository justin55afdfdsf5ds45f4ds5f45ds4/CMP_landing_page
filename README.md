# CMP: Context Memory Protocol (Private Beta)

**Status:** v0.2.1 (Stable)
**Access:** Invite Only / Early Adopters

---

### 🛑 The Problem: "Context Rot"
If you code with Claude or ChatGPT, you know the pain:
1. You work for 3 hours.
2. The context window fills up.
3. The model starts "forgetting" your folder structure or hallucinating dependencies that don't exist.

Most devs try to fix this by asking the AI to "summarize" the project. **This is a mistake.** AI summaries are "lossy." They guess, they drift, and they eventually hallucinate.

### ⚡ The Solution: Math > Vibes
CMP is a local CLI tool that replaces "AI Summaries" with **Deterministic Dependency Mapping**.

Instead of asking the LLM to guess what your code does, CMP uses a custom **Rust engine (`mu`)** to generate a mathematical map of your exact project structure. It injects this "Hard Truth" into the context window before every prompt.

* **Zero Hallucinations:** 100% accurate dependency trees.
* **Instant:** Runs in <2ms.
* **Local:** Your source code never leaves your machine.

### 📦 How to Get Access
We are currently in **Closed Beta** to keep the feedback loop tight.
We have opened up **50 Lifetime Licenses** for early testers who want to lock in the tool before the public v1.0 release.

**Beta Access Includes:**
* The Compiled CLI Binary (Mac/Windows/Linux)
* The Rust Analysis Engine
* Lifetime Updates (including v1.0)
* Direct Dev Support

**Click Here to Get the Beta (Gumroad) https://justinlord.gumroad.com/l/mppmoan**

*(Note: Once the 50 spots are gone, we will close access until the public launch.)*
