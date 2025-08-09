# Findings Analysis - Acunetix Scan on Metasploitable 2

## High Severity Issues
1. **MySQL Username Disclosure**
   - Risk: Could reveal database credentials.
   - Recommendation: Disable verbose error messages and restrict DB info disclosure.

2. **Vulnerable JavaScript Library**
   - Risk: Outdated libraries may allow XSS, CSRF, or other client-side attacks.
   - Recommendation: Update all JS libraries to latest versions.

3. **Cookie(s) Without HttpOnly Flag**
   - Risk: Increases risk of session hijacking via XSS.
   - Recommendation: Add `HttpOnly` attribute to session cookies.

4. **Error Message on Page**
   - Risk: Can reveal sensitive information about backend.
   - Recommendation: Display generic error messages.

## Medium & Low Severity
- Several outdated technologies detected.
- Informational alerts for security hardening.

## Conclusion
The scan confirms that Metasploitable 2 is highly insecure, making it suitable for penetration testing practice. These findings should never be ignored in production environments.
