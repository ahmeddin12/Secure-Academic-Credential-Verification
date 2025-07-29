# Secure-Academic-Credential-Verification
Build a platform where universities issue digitally signed certificates (via VeriFayda OIDC).  Employers/recruiters can instantly verify authenticity without contacting the institution.
# 🎓 SecureCredVerify: Tamper-Proof Academic Credential Verification

Contributors: 
- AHMED MAHMUD ABTEW  

Project Synopsis 

Problem Statement
Fake degrees/certificates are a global issue, with [1 in 3 employers reporting hiring someone with fraudulent credentials](https://www.forbes.com). Manual verification is slow, expensive, and prone to human error.  

Planned Solution
✅ A decentralized platform where:  
Universities issue digitally signed certificates (using VeriFayda OIDC for issuer authentication).  
Employers instantly verify credentials via a cryptographic proof (no need to contact the institution).  
Students own and share their credentials securely via QR codes or shareable links.  

Expected Outcome*
- A working prototype with:  
  - Issuer portal (for universities).  
  - Verifier dashboard (for employers).  
  - Student credential wallet (mobile-friendly).  
- Reduced verification time from weeks to seconds.  

Fayda's Role
VeriFayda OIDC ensures:  
1. Tamper-proof issuance: Only authorized universities can issue credentials.  
2. Zero-trust verification: Employers cryptographically verify authenticity without relying on a central database.  

---

Tech Stack  
| Component       | Technology |  
|-----------------|------------|  
| Frontend        | React.js + Chakra UI |  
| Backend         | Node.js (Express) |  
| Database        | PostgreSQL (for credential metadata) |  
| Authentication  | **VeriFayda OIDC** |  
| Security        | JSON Web Tokens (JWT), Digital Signatures (EdDSA) |  
| Deployment      | Docker + AWS EC2 |  



