# PHISHING AWARENESS TRAINING

# INTRODUCTION

Imagine opening your email and seeing an urgent warning from your bank saying your account is blocked. Panicked, you click the link provided, log in, and fix the issue. Only later do you realize the email was fake, the website was a copy, and you just handed your password directly to a thief.
This is phishing. It is a trick where scammers send fake emails, texts, or messages that look exactly like they are from trusted companies, banks, or friends. Instead of hacking into computers using complicated codes, phishing scammers simply hack our emotions—like fear or curiosity—to trick us into clicking bad links, downloading viruses, or giving away our passwords and money. It is the most common cyber threat today because it relies on a simple truth: it is much easier to trick a person than it is to break a computer.

In the course of this presentation, we will look at what phishing is, its types, how to recognize phishing emails and others.

# WHAT IS PHISHING?

Phishing is a type of cyberattack where scammers use deceptive messages to trick you into revealing sensitive information, sending money, or downloading malware. Instead of targeting technical bugs in software, phishing exploits human psychology (social engineering), often using a false sense of urgency or fear to make you act before you think.

# How Phishing Works: The 4-Step Cycle

A typical phishing attack follows a straightforward pattern:

1. Planning: The attacker sends an email, text, or message masquerading as a trusted brand, colleague, or authority figure.
   
2. Setup: Fake domains and lures created. You are prompted to click a link, open an attachment, or scan a QR code because of an "urgent" problem (e.g., "Account suspended!" or "Unauthorized charge!").
 
3. Execution: The link takes you to a fake login portal or website designed to look exactly like the real thing.
   
4. Harvest: Once you type in your username, password, or credit card details, the attacker captures them to steal your data or money.
 
# Common Types of Phishing

Phishing has evolved far beyond traditional mass-email scams. Attackers use various vectors to reach targets:

Email Phishing: Mass emails sent out to thousands of people pretending to be major platforms like Google or Microsoft.

Spear Phishing:	Highly targeted attacks aimed at a specific individual or company using personalized information gathered from social media.

Smishing & Vishing	Phishing via SMS text messages (Smishing) or fraudulent phone calls (Vishing).

# How to recognise phishing emails and fake websites

1 Extreme Urgency

2  Suspicious Sender Addresses

3 Generic Greetings

4 Unexpected Links or Attachments

5 Lookalike and Misspelled Domains (Typosquatting)

6 Broken Links and Layout Flaws

7 Look for the Padlock

# Social Engineering tactics used by attackers
Social engineering is the psychological manipulation of people into performing actions or divulging confidential information. Rather than hacking into a system by exploiting technical software flaws, cybercriminals exploit human vulnerabilities—such as trust, fear, urgency, and greed.

Because humans are often considered the weakest link in any security perimeter, social engineering is the primary root cause of most modern data breaches.

# The Core Psychological Framework (The "Why")
Attackers structure their campaigns around specific human cognitive biases to bypass rational thinking.

1 Authority:
Impersonating someone with power or clout. Victims are naturally conditioned to comply with demands from executives, legal departments, or government agencies.

2 Social Proof & Consensus: 
Tricking a victim into believing that others have already complied (e.g., "The rest of the sales team has already migrated to this new portal").

3 Urgency & Fear: 
Forcing a victim to act quickly before they can think rationally (e.g., "Your account will be permanently deactivated in 2 hours" or "Law enforcement has flagged this IP")

4 Scarcity: 
Creating a false sense of limited availability (e.g., "Only 3 employee holiday bonuses left, register now").

# Common Social Engineering Attack Vectors (The "How")
Social engineering takes many shapes depending on the delivery medium and the attacker's ultimate goal.

1 Quid Pro Quo:
An attacker promises a service or benefit in exchange for information or access.

2 Tailgating / Piggybacking:
A physical social engineering attack where an unauthorized person gains access to a restricted area simply by following closely behind a legitimate employee who has access credentials.

3 Pretexting:
The attacker invents a fabricated scenario (a pretext) to steal personal information. They establish a fake identity and context to build a baseline of trust.

4 Baiting:
This tactic promises an item or goodie to entice the victim, relying on curiosity or greed. Once the bait is taken, malware is executed or data is harvested.

# BEST PRACTISES AND TIPS TO AVOID FALLING VICTIM TO PHISHING

1 Use a Password Manager: 
Apps like Bitwarden or 1Password are smart. If you accidentally visit a fake website that looks exactly like Google, the app will refuse to type your password because it knows the web link is wrong.

2 Upgrade Your Security Codes: Instead of getting security codes sent to your phone via text message (which hackers can intercept), use an authenticator app (like Google Authenticator) or a physical security key.

3 Strengthen Email Authentication (DMARC): Ensure your organization’s domain cannot be spoofed to trick clients or employees. You must deploy and strictly configure three core records: SPF, DKIM, DMARC

4 Practice "Out-of-Band" Verification: 
If you receive an urgent message from your bank, boss, or a delivery service claiming there is a problem, do not click any links in the message. Instead, open a new browser tab, manually type the official website address, or call a known, trusted phone number to verify.

5 Hover Before You Click: 
On a computer, hover your mouse cursor over any link before clicking it to reveal the actual destination URL. If the text says paypal.com but the preview link points to paypl-security-update.net, it is a scam.

6 Enforce Phishing-Resistant MFA:
Traditional MFA (SMS text codes or push notifications) can be bypassed via phone spoofing or push-fatigue attacks. Transition your organization to FIDO2 / WebAuthn hardware security keys (like YubiKeys) or device-bound passkeys. These cryptographic standards bind the authentication process to the specific, legitimate web domain, making it impossible for a user to accidentally hand an authorization code to a phishing site.

# REAL-WORLD EXAMPLES OF PHISHING

# 1. The MGM Resorts Disaster (The Help Desk Call) 
The Background: In September 2023, the casino giant MGM Resorts International had its slot machines, digital hotel room keys, and reservation systems completely shut down for 10 days. The attack cost the company $100 million in a single quarter. 

How it happened: A hacking group called Scattered Spider used LinkedIn to look up info on an MGM employee. They then called the MGM IT help desk, pretended to be that employee, and claimed they had lost their phone and needed their Multi-Factor Authentication (MFA) security code reset. The help desk employee believed the caller and bypassed the security. 

The Lesson: Technical defenses fail if an employee can be manipulated over a simple phone call into resetting a password.

# 2. The Google and Facebook $100 Million Scam (The Fake Vendor) 
The Background: Between 2013 and 2015, a single attacker managed to steal over $100 million from Google and Facebook combined.
 
How it happened: The hacker realized both companies used a massive computer parts manufacturer called Quanta Computer. The hacker registered a fake company in Latvia with the exact same name as the manufacturer. He then sent perfectly designed corporate invoices to the accounting departments of Google and Facebook, prompting them to wire millions of dollars to his bank accounts instead of the real supplier. 

The Lesson: This is Business Email Compromise (BEC). Large organizations often process so many invoices that an attacker mimicking a real vendor can slip through unnoticed without an out-of-band verification process.

# INTERACTIVE QUIZ

# Question 1

Imagine you work in the finance department of a logistics company. You receive this email at 4:45 PM on a Friday afternoon:

From: internal-payroll@microsoft365-updates.net
To: finance-team@yourcompany.com
Subject: URGENT: Q3 Executive Compensation Adjustments Required

Team,

Please see the attached spreadsheet containing the updated salary adjustments for the executive leadership team. Due to an accounting error, these changes must be applied to the payroll system before 5:30 PM today so the modifications register for the upcoming weekend cycle.

Failure to update this in time will delay executive bonuses.

📄 Q3_Bonus_Adjustments_CONFIDENTIAL.xlsm (1.2 MB)

Thank you,
HR & Payroll Department

What would you do in this situation?
(A) Click the link quickly (B) Open the official website and verify (C)Reply to the mail

Answer: B (Make sure to always visit the official app or website to verify the email you received.)

Answer: C (Social engineers use phone calls to create an atmosphere of helpful urgency. Always verify the caller’s identity through official internal channels.)

# Question 2 

An individual calls your desk phone claiming to be an IT support technician from your company's service desk. They claim your computer is broadcasting a network error and ask you to install a remote-access tool (TeamViewer or AnyDesk) so they can fix it. How should you respond?

Option A: Follow their instructions immediately to ensure your machine doesn't disrupt the corporate network.

Option B: Hang up and call your co-workers to see if they are experiencing the same technical network error.

Option C: Decline the request, hang up, and independently look up the official internal IT Help Desk number to verify the call.

Option D: Provide them with your corporate password over the phone so they can log in and fix it on their end.

Answer: C (Social engineers use phone calls to create an atmosphere of helpful urgency. Always verify the caller’s identity through official internal channels.)

# Abbreviations used and full meaning
1  MFA: Multi-Factor Authentication (A security system that requires more than one password/code to log in).

2     OTP: One-Time Password (A temporary security code sent to your phone or app).

3   FIDO2: Fast IDentity Online 2 (A modern, highly secure standard for logging in without passwords using physical keys or fingerprints.

4   TOTP: Time-based One-Time Password (Security codes generated by apps that change automatically every 30 seconds).

5    WebAuthn: Web Authentication (The technical system that allows secure FIDO2 logins to work on websites).

6    SPF: Sender Policy Framework (A list that tells email servers exactly which computers are allowed to send emails from a specific domain).

7   DKIM: DomainKeys Identified Mail (A digital signature added to emails to prove they weren't changed or faked on the way).

8  DMARC: Domain-based Message Authentication, Reporting, and Conformance (The master rulebook that tells email servers what to do if an email fails the SPF or DKIM checks).

9     OSINT: Open Source Intelligence (Information that anyone can legally and publicly find on the internet, like on social media or LinkedIn).

# CONCLUSION

The bottom line: Cybercriminals don’t just hack systems, they hack people. Technology can block thousands of threats every day, but your vigilance remains our strongest line of defense.
Thank you for taking the time to complete this quiz and for doing your part to keep our data, our clients, and our team safe. 

Remember:  when in doubt, don't click; report it!


RESOURCES

Google.com

ZoneAlarm Phishing Quizz

Canva



NITA ILEM
CYBERSECURITY INTERN 
CODEALPHA
