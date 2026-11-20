# Retrospective literature-search audit
**Date:** 2026-11-21 (Asia/Kolkata).
**Scope:** Six fresh searches of a web search index. These are not original IEEE Xplore/Google Scholar/ACM database searches.

## What can and cannot be counted
- **6** search queries executed.
- **18** identified result previews checked individually: three per query.
- **10** of those previews match distinct works already present in the 25-paper survey corpus.
- **6** additional candidates and **2** results outside the research-paper/date criteria were observed in the preview sample.
- **Full database hit totals: not reported.** They are unknown, not zero.
- This exercise does **not** establish initial works identified, screened or excluded for the original 25-paper selection.
- Publication year conditions were mentioned in query text; no server-side database date filter was verifiable.

## Search strings
- **S01 — Protocol security:** `"TLS 1.3" formal verification vulnerabilities session tickets state machine security 2022..2026`. Full hits: not reported. Preview records checked: 3. Previously included works found: P01.
- **S02 — Certificate validation:** `"X.509" "certificate validation" "TLS" browser transcert 2022 2026`. Full hits: not reported. Preview records checked: 3. Previously included works found: P04, P15.
- **S03 — Certificate revocation:** `"HTTPS certificate revocation" CRL OCSP privacy 2022 2026`. Full hits: not reported. Preview records checked: 3. Previously included works found: P06, P07.
- **S04 — Encrypted traffic:** `"TLS 1.3" "encrypted traffic" "machine learning" "privacy" 2022 2026`. Full hits: not reported. Preview records checked: 3. Previously included works found: P10.
- **S05 — CAA CT DANE:** `"CAA" "DANE" "certificate transparency" "Web PKI" deployment measurement 2022 2026`. Full hits: not reported. Preview records checked: 3. Previously included works found: P08, P09.
- **S06 — Post-quantum TLS:** `"post-quantum" "TLS 1.3" handshake performance QUIC certificate 2022 2026`. Full hits: not reported. Preview records checked: 3. Previously included works found: P02, P23.

## Auditable preview records

### S01: Protocol security
- **Towards Validation of TLS 1.3 Formal Model and Vulnerabilities in Intel’s RA-TLS Protocol** (2024) — Previously included (P01). [Source](https://pub.h-brs.de/frontdoor/deliver/index/docId/8701/file/ACCESS_2024_3497184.pdf).
- **Formally Verifying the State Machine of TLS 1.3 Handshake in OpenSSL** (2025) — Additional candidate. [Source](https://researchconnect.buffalo.edu/en/publications/formally-verifying-the-state-machine-of-tls-13-handshake-in-opens/).
- **Unified Formal Verification of Security Requirements in the TLS Family** (2025) — Additional candidate. [Source](https://di0zxmb8pwajl.cloudfront.net/kiisc/conference/mobisec2025/programbook/65.pdf).

### S02: Certificate validation
- **On the Validation of Web X.509 Certificates by TLS Interception Products** (2022) — Previously included (P04). [Source](https://mmlab.snu.ac.kr/wp-content/uploads/2025/06/On_the_Validation_of_Web_X.509_Certificates_by_TLS_Interception_Products-20250609-073013.pdf).
- **Coverage-Directed Differential Testing of X.509 Certificate Validation in SSL/TLS Implementations** (2023) — Previously included (P15). [Source](https://doi.org/10.1145/3510416).
- **Hallucinating Certificates: Differential Testing of TLS Certificate Validation Using Generative Language Models** (2026) — Additional candidate. [Source](https://softsec.rub.de/publications/icse2026-hallucinating-certificates/).

### S03: Certificate revocation
- **An Internet-Wide View on HTTPS Certificate Revocations: Observing the Revival of CRLs via Active TLS Scans** (2024) — Previously included (P07). [Source](https://portal.fis.tum.de/en/publications/an-internet-wide-view-on-https-certificate-revocations-observing-/).
- **An Evaluation of X.509 Certificate Revocation and Related Privacy Issues in the Web PKI Ecosystem** (2023) — Previously included (P06). [Source](https://iris.polito.it/retrieve/handle/11583/2980760/8935fca3-fee6-4b86-abe0-4d186981abc0/An_Evaluation_of_X.509_Certificate_Revocation_and_Related_Privacy_Issues_in_the_Web_PKI_Ecosystem.pdf).
- **Analysis of the HTTPS Certificate Ecosystem** (2013) — Excluded from this verification sample: out of period. [Source](https://faculty.cc.gatech.edu/~mbailey/publications/imc13_https_final.pdf).

### S04: Encrypted traffic
- **Challenges and Advances in Analyzing TLS 1.3-Encrypted Traffic: A Comprehensive Survey** (2024) — Previously included (P10). [Source](https://www.mdpi.com/2079-9292/13/20/4000).
- **Encrypted-Traffic Detection in the TLS 1.3 Era: A Comprehensive Review and Future Research Directions** (2026) — Additional candidate. [Source](https://www.mdpi.com/2079-9292/15/17/3846).
- **SoK: Decoding the Enigma of Encrypted Network Traffic Classifiers** (2025) — Additional candidate. [Source](https://cgi.cse.unsw.edu.au/~ntciq/research/ntc-enigma/).

### S05: CAA CT DANE
- **Do CAA, CT, and DANE Interlink in Certificate Deployments? A Web PKI Measurement Study** (2024) — Previously included (P08). [Source](https://tma.ifip.org/2024/wp-content/uploads/sites/13/2024/05/tma2024-final38-1.pdf).
- **How to Measure TLS, X.509 Certificates, and Web PKI: A Tutorial and Brief Survey** (2024) — Previously included (P09). [Source](https://arxiv.org/abs/2401.18053).
- **Web PKI: How to Protect a Popular Security Service?** (2024) — Excluded from this verification sample: non-primary blog. [Source](https://blog.apnic.net/2024/10/02/web-pki-how-to-protect-a-popular-security-service/).

### S06: Post-quantum TLS
- **The Performance of Post-Quantum TLS 1.3** (2023) — Previously included (P02). [Source](https://doi.org/10.1145/3624354.3630585).
- **Post-Quantum Key Exchange in TLS 1.3: Further Analysis on Performance of New Cryptographic Standards** (2025) — Previously included (P23). [Source](https://www.mdpi.com/2410-387X/9/4/73).
- **A Systems-Level Performance Study of Post-Quantum TLS with ML-KEM and ML-DSA in Modern OpenSSL** (2026) — Additional candidate. [Source](https://www.mdpi.com/2078-2489/17/11/1098).

## How to interpret
These checks confirm discoverability of some previously included papers, not a reproducible original selection-flow count. To report exact database hit counts in Section II and Figure 1, run recorded searches directly inside an academic search database, note its search-result count as displayed, and retain dates/filters/screenshots or exports. Do not use 18 as an original screened count or 10 as the number of papers originally included.
