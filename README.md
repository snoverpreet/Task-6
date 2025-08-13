# Task-6

**Create a Strong Password and Evaluate Its Strength**

# 1. Safety first
Never test real passwords on any website. Create throwaway sample passwords only.
Use an incognito/private window.

# 2. Pick your tools
Choose 1–2 free checkers (e.g., Password Meter). If you also check exposure against breach datasets, use a privacy-preserving checker (range-query style).

# Tools (Online Free Tools):

**https://passwordmeter.com/** 

**https://bitwarden.com/password-strength/ Password Tester | Test Your Password Strength**
# 3. Build your test set (10–12 samples)

Start simple and ramp up:

all-lowercase word, capitalized word, word+digit, word+symbol, leetspeak+year, random 9–10 chars, 3–5 word passphrases with separators, passphrase + digits/symbols, long random string.

Record patterns (e.g., Word-Word-Word-##!), not secrets.

# 4. Test systematically

For each sample: paste it into the checker → capture the score/grade, any entropy value shown, and the feedback text.

If you use a breach checker, note if it’s “seen before” (don’t paste real passwords).

Clear the input between tests.

# 5. Analyze your findings

Compare short-but-complex vs long-and-simple passphrases.

Note how predictable tweaks (Password1, P@ssw0rd) still rate poorly.

# 6. Derive best practices
From your results you should conclude:

# Prefer length (16+).

# Use unpredictable content (random strings or 4–5 word passphrases with separators).

# Unique per site + MFA.

# Avoid personal info, common words, years, keyboard patterns, and leetspeak versions of common words.

# Use a password manager to generate/store.

# 7. Research common attacks (short notes)

**Brute force:** tries all combos; length explodes the search space.
**Dictionary/rules attacks:** target common words and patterns; unpredictability/passphrases beat these.
**Credential stuffing:** reuses breached pairs; uniqueness stops it.
**Phishing/keylogging:** steal the password directly; MFA limits damage.

# 8. Summarize how complexity affects security

Length is the strongest lever; variety helps but predictable patterns are weak; uniqueness + MFA mitigates real-world risks.

**Note=** I add my own developed password strength checker tool using html, css and javascript | file named as **"pass.html"** 
