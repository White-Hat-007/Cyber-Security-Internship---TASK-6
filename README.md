# 🔐 Password Security Analysis & Attack Techniques

## 1. Generated Passwords of Varying Complexity

| Password                   | Length | Complexity                             |
|---------------------------|--------|----------------------------------------|
| `password123`             | 11     | Lowercase + Numbers                    |
| `Pa$$w0rd`                | 8      | Uppercase + Lowercase + Symbol + Number |
| `G9r#8LpZ!q`              | 10     | All character types                    |
| `XyZ!98@L#w$*3`           | 13     | High complexity, random                |
| `D@rsh_2025`              | 11     | Mixed, personalized                    |
| `&K#t2L6qP3z9!Vd`         | 16     | Strongest, high entropy                |
| `LetMeIn`                 | 7      | Low complexity, common phrase          |
| `correcthorsebatterystaple` | 25  | Long passphrase, low symbols           |

---

## 2. Password Strength Test Results

| Password                   | Strength         | Reason                                                         |
|---------------------------|------------------|----------------------------------------------------------------|
| `password123`             | ❌ Very Weak      | Common, easily guessable                                       |
| `Pa$$w0rd`                | ❌ Weak           | Predictable pattern, short                                     |
| `G9r#8LpZ!q`              | ✅ Strong         | Random, all character types                                    |
| `XyZ!98@L#w$*3`           | ✅ Very Strong    | High entropy, long, complex                                    |
| `D@rsh_2025`              | ⚠️ Moderate      | Mixed, but predictable and personalized                        |
| `&K#t2L6qP3z9!Vd`         | ✅ Very Strong    | Excellent randomness and length                                |
| `LetMeIn`                 | ❌ Very Weak      | Very common and short                                          |
| `correcthorsebatterystaple` | ⚠️ Moderate–Strong | Long, lacks symbol/number complexity                         |

---

## 3. Best Practices Learned from Evaluation

- ❌ Avoid using common words or patterns like `password`, `123456`, or `letmein`.
- ✅ Use all character types: uppercase, lowercase, numbers, symbols.
- ✅ Make passwords long (12+ characters preferred).
- ❌ Don’t rely on substitutions like "@" for "a".
- ✅ Prefer random, unpredictable strings or improved passphrases.
- ✅ Use a password manager to generate and store complex passwords.

---

## 4. Common Password Attack Techniques

### 🔓 I. Brute Force–Based Attacks

- **Brute Force**: Tries every possible combination.
  - Mitigation: Use long and complex passwords; limit login attempts.
- **Dictionary Attack**: Uses wordlists of common passwords.
  - Mitigation: Avoid real words or common phrases.
- **Hybrid Attack**: Mixes dictionary words with character substitutions.
  - Mitigation: Increase randomness.
- **Reverse Brute Force**: Uses a common password across many usernames.
  - Mitigation: Use unique passwords per account.
- **Password Spraying**: Tries one/few common passwords across many users.
  - Mitigation: Enforce lockout and retry limits.
- **Smart Brute Force (AI-based)**: Uses user-specific data for predictions.
  - Mitigation: Avoid predictable or personal patterns.
- **Offline Brute Force**: Cracks stolen hashes offline.
  - Mitigation: Use strong, slow hashing algorithms like bcrypt or Argon2.

### 🕵️ II. Social Engineering Attacks

- **Phishing**: Fake emails/sites trick users into giving credentials.
  - Mitigation: MFA, training, anti-phishing tools.
- **Pretexting**: Impersonation for extracting login info.
  - Mitigation: Identity verification policies.
- **Baiting**: Malicious downloads or USB drives.
  - Mitigation: Avoid suspicious media/devices.
- **Quid Pro Quo**: Fake service offers in exchange for credentials.
  - Mitigation: Staff training and awareness.
- **Shoulder Surfing**: Observing credentials being entered.
  - Mitigation: Use privacy screens; be aware of surroundings.

### 🛰️ III. Credential Reuse Exploits

- **Credential Stuffing**: Reuse of leaked credentials on other sites.
  - Mitigation: Use unique passwords; enable MFA.
- **Password Reuse**: Manually trying known credentials elsewhere.
  - Mitigation: Use password managers; audit reuse.

### 🐛 IV. Malware-Based Attacks

- **Keylogging**: Records keystrokes to capture passwords.
  - Mitigation: Use antivirus software and MFA.
- **Screen Scraping**: Captures screen during password entry.
  - Mitigation: Use secure input environments.
- **Clipboard Hijacking**: Monitors clipboard for copied passwords.
  - Mitigation: Use password managers with autofill.
- **Credential Harvesters**: Extract saved browser credentials.
  - Mitigation: Avoid storing passwords in browsers; harden browser security.

### 🌐 V. Web and Application Attacks

- **Man-in-the-Middle (MitM)**: Intercepts credentials over insecure networks.
  - Mitigation: Use HTTPS, VPNs, and TLS.
- **Session Hijacking**: Steals session tokens post-login.
  - Mitigation: Secure cookies, session expiry, activity monitoring.
- **Cross-Site Scripting (XSS)**: Steals credentials via injected scripts.
  - Mitigation: Sanitize inputs, use CSP headers.

### 🧠 VI. Cognitive or Guessing-Based Attacks

- **Guessing**: Based on birthdays, pet names, etc.
  - Mitigation: Don’t use personal info in passwords.
- **Security Question Exploits**: Easily guessed recovery questions.
  - Mitigation: Use fake or strong answers; prefer email/SMS recovery.

---

## 5. Why Password Complexity Still Matters for Security

| Factor              | Impact                                                             |
|---------------------|--------------------------------------------------------------------|
| Length              | Increases cracking time exponentially                              |
| Character Variety   | More variety = more possible combinations                          |
| Randomness          | Makes brute-force, hybrid, and guess-based attacks ineffective     |
| Uniqueness          | Stops credential stuffing/reuse                                    |
| Non-personalization | Protects against targeted guessing and social engineering          |

---

## 6. Password Entropy Example

- A **6-character lowercase password**: ~308 million combinations → cracked in seconds.
- A **12-character password** with all types: ~475 quintillion combinations → nearly uncrackable.

**Security Rule**:  
`Strong Password = Length + Complexity + Randomness + Uniqueness`

---

## ✅ Final Recommendations

- ✅ Use **password managers** to create/store complex passwords.
- ✅ Enable **Multi-Factor Authentication (MFA)**.
- ✅ Regularly **rotate** high-privilege account credentials.
- ✅ Use **unique passwords** across every account.
- ✅ Avoid **saving passwords in browsers**; use secure managers instead.

---

> 📌 _Security starts with awareness — your password is your digital identity's first line of defense._

---

## 👨‍💻 Author

**Darsh Chatrani**  
🔗 [LinkedIn](https://linkedin.com/in/darshchatrani)  
📞 Contact: +91 97899 57123

---
