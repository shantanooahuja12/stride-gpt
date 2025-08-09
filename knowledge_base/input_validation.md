# Input Validation Best Practices

Input validation is a critical security control that protects against a variety of attacks, including Cross-Site Scripting (XSS), SQL Injection, and buffer overflows. All user-supplied input should be treated as untrusted. Implement robust input validation on both the client-side and server-side. Use allow-lists (whitelisting) to define acceptable input patterns and reject all other input. Sanitize and encode output to prevent XSS. Use parameterized queries (prepared statements) to prevent SQL Injection.
