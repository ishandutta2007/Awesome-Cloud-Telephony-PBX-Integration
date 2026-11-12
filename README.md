# Awesome-Cloud-Telephony-PBX-Integration

# Top Cloud Telephony & PBX Integration Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Unified Communications, Cloud PBX & Programmable Voice Infrastructure*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Cloud Telephony & PBX Integration**. These tools provide business telephony over the internet—covering virtual phone numbers, IVR, call routing, voicemail, conferencing, and contact center capabilities—eliminating the need for on-premises PBX hardware while enabling distributed teams to communicate from anywhere.

**Examples** include RingCentral MVP, 8x8 X Series, Nextiva, Dialpad, Vonage Business Communications, Zoom Phone, Talkdesk, GoTo Connect, Ooma Office, and Zoho Voice (the category leaders).

**Open-source emphasis**: This section highlights every major active project for self-hosted PBX systems, SIP infrastructure, and open-source unified communications—ideal for system administrators, IT teams, and developers building transparent, vendor-neutral telephony infrastructure without per-user cloud subscriptions.

Contributions welcome! Open an PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

| Product | Description | Pricing (Starting) | Free Tier / Trial Limits |
|---------|-------------|-------------------|--------------------------|
| **[RingCentral MVP](https://www.ringcentral.com/)** | Enterprise unified communications with RingEX plans (Core, Advanced, Ultra) bundling unlimited domestic calling, video meetings, team messaging, and SMS. Includes PSTN connectivity in base pricing; Webex Calling requires separate PSTN add-ons for comparison [citation:2]. | Core: $20/user/month (annual, 1–100 users); Advanced: $25; Ultra: $35 [citation:14] | No free plan; free trial available via sales. Discounts of 20–35% below list are common for multi-year commitments [citation:2]. |
| **[8x8 X Series](https://www.8x8.com/)** | Cloud communications with six tiers: Express ($15/user/month), X2 Work ($24), X4 Work ($44), X6–X8 contact center tiers. X2 includes video meetings up to 100 participants and unlimited calling to 14 countries [citation:3][citation:15]. | Express: $15/user/month; X2 Work: $24/user/month [citation:15] | No free tier as of 2026; free trial not confirmed by vendor [citation:15]. |
| **[Nextiva](https://www.nextiva.com/)** | Business VoIP with call routing, user-friendly interface, and CRM integrations. Rated Best Business VoIP Phone Providers in 2026 by GetVoIP [citation:4]. | From $19.95/user/month (depending on user count and contract length) [citation:4] | Monthly no-commitment plan available; contract terms of 12/24/36 months offer savings [citation:4]. No free tier listed. |
| **[Dialpad](https://www.dialpad.com/)** | AI-powered cloud communications with voice, video, messaging, and contact center. Standard includes voicemail transcription and Google Workspace/Microsoft 365 integration [citation:5]. | Standard: ¥1,000/user/month (~$7 USD); Pro: ¥1,500; Enterprise: ¥2,000 (JP pricing, April 2026) [citation:5] | **30-day free trial** for Dialpad for 050 [citation:5]. No permanent free tier. |
| **[Vonage Business Communications](https://www.vonage.com/)** | Cloud PBX with mobile/desktop apps, team messaging, video meetings (up to 200 participants on Premium), multi-level auto attendant, and CRM integrations [citation:6]. | Basic Mobile: $13.99/user/month (12-month promo, save 30%); Premium: $20.99; Advanced: $26.59 [citation:6] | No free tier listed; promotional pricing available on 12-month terms [citation:6]. |
| **[Zoom Phone](https://www.zoom.us/)** | Cloud phone system integrated with Zoom Meetings. Metered and Unlimited plans for US/Canada. AI Companion included for post-call summaries and voicemail prioritization . | Metered (US/CA): HK$78.50/month (~$10 USD); Unlimited (US/CA): HK$117.75 (~$15 USD)  | No permanent free tier; metered option for low-volume use. Business Plus bundle available . |
| **[Talkdesk](https://www.talkdesk.com/)** | AI-powered cloud contact center platform. Voice Essentials, Digital Essentials, Elite, and Industry Experience Clouds. Includes 25 licenses and $100 free credit for small businesses via Talkdesk Express [citation:8]. | Voice Essentials: $105/user/month; Digital Essentials: $85; Elite: $165 [citation:8] | **Talkdesk Express**: 25 licenses + $100 free credit for businesses under 50 employees, no commitment [citation:8]. |
| **[GoTo Connect](https://www.goto.com/)** | Unified communications with Phone System, AI Receptionist, CX Complete, and Contact Center tiers. Includes free calls to 50 countries, video meetings up to 250 participants, and 99.999% reliability [citation:9]. | Phone System: from $26/user/month (annual); AI Receptionist and CX tiers available [citation:9] | Free trial available; no permanent free tier listed [citation:9]. |
| **[Ooma Office](https://www.ooma.com/)** | Affordable VoIP for small businesses with three tiers: Essentials ($19.95), Pro ($24.95), Pro Plus ($29.95). Includes unlimited calling to US, Canada, Mexico, and Puerto Rico on Essentials [citation:10]. | Essentials: $19.95/user/month; Pro: $24.95; Pro Plus: $29.95 [citation:10] | No free tier; phone number porting free; additional numbers $9.95/month [citation:10]. |
| **[Zoho Voice](https://www.zoho.com/voice/)** | Cloud telephony integrated with Zoho CRM, Desk, and other Zoho apps. Solo plan free with 250 outgoing mins/month. Enterprise Telephony plans for Zoho ecosystem users [citation:11]. | Solo: Free (250 outgoing mins/month); Paid plans via Zoho Voice credits (1 credit = $1 USD) [citation:11] | **Solo (free)**: 250 free outgoing mins/month, call charges applicable; Telephony agents don't have web UI access [citation:11]. |

## Open-Source GitHub Projects

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[FreeSWITCH](https://github.com/signalwire/freeswitch)** | [![Stars](https://img.shields.io/github/stars/signalwire/freeswitch?style=social&color=white)](https://github.com/signalwire/freeswitch/stargazers) | Software-defined telecom stack for building PBX, conferencing, and media processing applications. Runs on commodity hardware from Raspberry Pi to multi-core servers. ~5,237 GitHub stars [citation:12]. |
| **[Asterisk](https://github.com/asterisk/asterisk)** | [![Stars](https://img.shields.io/github/stars/asterisk/asterisk?style=social&color=white)](https://github.com/asterisk/asterisk/stargazers) | The world's most widely deployed open-source PBX engine. Handles calls, routing, SIP trunks, IVR, queues, voicemail, and conferencing. ~3,632 GitHub stars [citation:12]. |
| **[Kamailio](https://github.com/kamailio/kamailio)** | [![Stars](https://img.shields.io/github/stars/kamailio/kamailio?style=social&color=white)](https://github.com/kamailio/kamailio/stargazers) | Open-source SIP server for large VoIP and real-time communication platforms. Focused on flexibility, security, and scalability. ~2,978 GitHub stars [citation:12]. |
| **[OpenSIPS](https://github.com/OpenSIPS/opensips)** | [![Stars](https://img.shields.io/github/stars/OpenSIPS/opensips?style=social&color=white)](https://github.com/OpenSIPS/opensips/stargazers) | Multi-functional SIP server targeting high-performance and high-level technical solutions. GPL implementation. ~1,543 GitHub stars [citation:12]. |

### Additional Strong Open-Source Options

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[FusionPBX](https://github.com/fusionpbx/fusionpbx)** | [![Stars](https://img.shields.io/github/stars/fusionpbx/fusionpbx?style=social&color=white)](https://github.com/fusionpbx/fusionpbx/stargazers) | Full-featured domain-based multi-tenant PBX and voice switch for FreeSWITCH. Web GUI for managing extensions, trunks, IVR, and voicemail. ~1,072 GitHub stars [citation:12]. |
| **[PJSIP](https://github.com/pjsip/pjproject)** | [![Stars](https://img.shields.io/github/stars/pjsip/pjproject?style=social&color=white)](https://github.com/pjsip/pjproject/stargazers) | Open-source SIP, SDP, RTP, and STUN/TURN library. Foundation for many softphones and PBX integrations. ~2,700 GitHub stars [citation:12]. |
| **[HOMER](https://github.com/sipcapture/homer)** | [![Stars](https://img.shields.io/github/stars/sipcapture/homer?style=social&color=white)](https://github.com/sipcapture/homer/stargazers) | 100% open-source SIP, VoIP, and RTC packet capture and monitoring tool. Essential for troubleshooting SIP infrastructure. ~2,022 GitHub stars [citation:12]. |

**Frameworks for building custom systems**: Combine **Asterisk** or **FreeSWITCH** for core PBX functionality, **FusionPBX** for web-based administration, **Kamailio** or **OpenSIPS** at the edge for SIP routing and security, and **HOMER** for monitoring—all deployable on commodity Linux servers or VMs.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Cloud phone systems handle voice communications and call recordings; ensure compliance with applicable regulations (call recording consent laws, GDPR, HIPAA) and enforce strong authentication on admin portals.
- Self-hosted PBX systems require proper firewall configuration, SIP security (fail2ban, TLS, SRTP), and regular security updates; misconfigured PBX can be exploited for toll fraud. Pricing and free-tier limits change frequently; verify against vendor pages before committing.

---

**Made for IT administrators, small business owners, VoIP engineers, and developers building telephony infrastructure.**  
Let's make cloud telephony and PBX integration more open, secure, and cost-transparent.
