# COPWATCHDOG

Data pipeline for NYC police accountability.

🕵️ Track NYPD officer trials, complaints, lawsuits, and public records  
⚖️ Licensed under CopWatchDog Community License 1.0 (non-commercial, non-LEO only)

---

## System Architecture

**THOTH**        (Python/Playwright) → Scrapes NYPD trials + 50-a.org + NYC Payroll  (Public)
**HERMES**       (Bash/PostgreSQL)   → ETL pipeline, delta detection, data warehouse  (Private)
**CERBERUS_API** (Node.js/Express)   → REST middleware with auth & rate limiting  (Private)
**MERCURY**      (WordPress/PHP)     → Public frontend with search, filters, themes (Private)

---

## Repositories

- [**THOTH**](https://github.com/copwatchdog/THOTH)               - Data collection engine (v113)
- [**HERMES**](https://github.com/copwatchdog/HERMES)             - ETL & database (v1.7.0)
- [**CERBERUS_API**](https://github.com/copwatchdog/CERBERUS_API) - REST API (v2.4.0)
- [**MERCURY**](https://github.com/copwatchdog/MERCURY)           - WordPress plugin (v2.8.0)

--

## License Restrictions

❌ **NO commercial use**  
❌ **NO police, military, prison, or surveillance use**  
✅ **Community organizing & transparency only**

See [LICENSE](https://github.com/copwatchdog/THOTH/blob/main/LICENSE) for full terms.

---

🔗 [YUMYODA Initiative](https://github.com/YUMYODA) | 👤 [Stizzi](https://github.com/Stizzi) (Co-founder)

```
 ██████╗ ██████╗ ██████╗ ██╗    ██╗ █████╗ ████████╗ ██████╗ ██╗   ██╗██████╗   ██████╗  ██████╗
██╔════╝██╔═══██╗██╔══██║██║    ██║██╔══██╗╚══██╔══╝██╔════╝ ██║   ██║██╔═══██╗██╔═══██╗██╔════╝
██║     ██║   ██║██████╔╝██║ █╗ ██║███████║   ██║   ██║      ████████║██║   ██║██║   ██║██║  ███╗
██║     ██║   ██║██╔═══╝ ██║███╗██║██╔══██║   ██║   ██║      ██╔═══██║██║   ██║██║   ██║██║   ██║
╚██████╗╚██████╔╝██║     ╚███╔███╔╝██║  ██║   ██║   ╚██████╗ ██║   ██║██████╔╝ ╚██████╔╝╚██████╔╝
 ╚═════╝ ╚═════╝ ╚═╝      ╚══╝╚══╝ ╚═╝  ╚═╝   ╚═╝    ╚═════╝ ╚═╝   ╚═╝╚═════╝   ╚═════╝  ╚═════╝
```
