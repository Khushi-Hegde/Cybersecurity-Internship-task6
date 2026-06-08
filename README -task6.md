# Task 6 – Create a Strong Password and Evaluate Its Strength

## Objective
Understand what makes a password strong by creating passwords of varying complexity and testing them against an online password strength checker.

## Tool Used
- **[passwordmeter.com](https://passwordmeter.com)** – evaluates password strength based on length, character variety, patterns, and common usage. Provides a rating, entropy score (bits), and estimated crack time.

## What I Did
1. Created 6 passwords ranging from very weak to very strong.
2. Tested each password on passwordmeter.com and recorded the rating, entropy, and feedback.
3. Analysed the results to identify patterns that weaken or strengthen passwords.
4. Researched common password attacks (brute force, dictionary, credential stuffing, rainbow table).
5. Summarised best practices for creating and managing strong passwords.

## Results Summary

| Password | Rating | Entropy | Crack Time (Fast DB) |
|---|---|---|---|
| `123456` | Very Weak | ~undefined | Instantly |
| `P@ssw0rd!` | Very Weak | ~29 bits | 9 hours |
| `Pass@1234` | Fair | ~66 bits | 6 years |
| `Summer#2024` | Weak | ~64 bits | 2 years |
| `BlueSky!Rain#42` | Strong | ~98 bits | 45 billion years |
| `Tr0ub4dor&3#Secure!` | Very Strong | ~125 bits | >1 trillion years |

## Key Takeaways
- **Length is the most impactful factor** – every extra character multiplies crack time exponentially.
- **Common patterns are dangerous** – keyboard walks, dictionary words, and years are all in attacker dictionaries.
- **All four character types matter** – but only when combined with sufficient length.
- **Use a password manager** to generate and store unique, random passwords for every account.
- **Enable MFA** as a second layer of defence on all critical accounts.

## Files
- `Task6_Password_Strength_Report.pdf` – Full report with test results, attack types, and best practices.
- Screenshots of passwordmeter.com results for each password tested.

## Key Concepts
`Password Strength` · `Brute Force Attack` · `Dictionary Attack` · `Entropy` · `MFA` · `Best Practices`
