# PortSwigger Web Security Academy — Lab Writeups

A collection of clean, detailed, and structured PDF writeups for various security labs from the **PortSwigger Web Security Academy**. These writeups cover vulnerability descriptions, step-by-step exploitation steps, proof of concept HTTP requests, impact analysis, and mitigations.

## 📂 Categories & Covered Labs

### 🌐 API Testing
* [Exploiting an API endpoint using documentation](API_Testing_Exploiting_an_API_endpoint_using_documentation.pdf)
* [Finding and exploiting an unused API endpoint](API_Testing_Finding_and_exploiting_an_unused_API_endpoint.pdf)

### 🔑 Access Control
* [Unprotected admin functionality](Access_Control_Unprotected_admin_functionality.pdf)
* [Unprotected admin functionality with unpredictable URL](Access_Control_Unprotected_admin_functionality_with_unpredictable_URL.pdf)

### 👤 Authentication
* [2FA simple bypass](Authentication_2FA_simple_bypass.pdf)
* [Username enumeration via different responses](Authentication_Username_enumeration_via_different_responses.pdf)

### 💼 Business Logic
* [Excessive trust in client-side controls](Business_Logic_Excessive_trust_in_client_side_controls.pdf)
* [High-level logic vulnerability](Business_Logic_High_level_logic_vulnerability.pdf)

### 🛡️ CSRF
* [CSRF vulnerability with no defenses](CSRF_CSRF_vulnerability_with_no_defenses.pdf)
* [CSRF where token validation depends on request method](CSRF_CSRF_where_token_validation_depends_on_request_method.pdf)

### 🖼️ Clickjacking
* [Basic clickjacking with CSRF token protection](Clickjacking_Basic_clickjacking_with_CSRF_token_protection.pdf)
* [Clickjacking with form input data prefilled from URL parameter](Clickjacking_Clickjacking_with_form_input_data_prefilled_from_URL_parameter.pdf)

### 💻 Command Injection
* [Blind OS command injection with time delays](Command_Injection_Blind_OS_command_injection_with_time_delays.pdf)
* [OS command injection simple case](Command_Injection_OS_command_injection_simple_case.pdf)

### 🎫 JWT
* [JWT authentication bypass via flawed signature verification](JWT_JWT_authentication_bypass_via_flawed_signature_verification.pdf)
* [JWT authentication bypass via unverified signature](JWT_JWT_authentication_bypass_via_unverified_signature.pdf)

### 🗄️ SQL Injection
* [SQL injection vulnerability allowing login bypass](SQL_Injection_SQL_injection_vulnerability_allowing_login_bypass.pdf)
* [SQL injection vulnerability in WHERE clause](SQL_Injection_SQL_injection_vulnerability_in_WHERE_clause.pdf)

### 🖥️ SSRF (Server-Side Request Forgery)
* [Basic SSRF against another back-end system](SSRF_Basic_SSRF_against_another_back_end_system.pdf)
* [Basic SSRF against the local server](SSRF_Basic_SSRF_against_the_local_server.pdf)

### 📑 SSTI (Server-Side Template Injection)
* [Basic server-side template injection](SSTI_Basic_server_side_template_injection.pdf)
* [Basic server-side template injection (code context)](SSTI_Basic_server_side_template_injection_code_context.pdf)

### 🧪 XSS (Cross-Site Scripting)
* [Reflected XSS into HTML context with nothing encoded](XSS_Reflected_XSS_into_HTML_context_with_nothing_encoded.pdf)
* [Stored XSS into HTML context with nothing encoded](XSS_Stored_XSS_into_HTML_context_with_nothing_encoded.pdf)

### 📂 XXE (XML External Entity)
* [Exploiting XXE to perform SSRF attacks](XXE_Exploiting_XXE_to_perform_SSRF_attacks.pdf)
* [Exploiting XXE using external entities to retrieve files](XXE_Exploiting_XXE_using_external_entities_to_retrieve_files.pdf)

---

## 📝 Document Structure
Each writeup is structured for maximum clarity and includes:
- **Description:** Explanation of the vulnerability and its core mechanism.
- **Steps to Exploit:** Step-by-step guidance on reproducing the vulnerability.
- **Proof of Concept:** Actual HTTP requests/responses or code blocks illustrating the exploit.
- **Impact:** Analysis of risks associated with the security issue.
- **Mitigation / Remediation:** Recommendations and best practices for securing the application.
- **CVSS Score & Justification:** Comprehensive CVSS v3.1 rating and vector.
