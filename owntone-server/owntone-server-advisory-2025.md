# Security Advisories of Vulnerabilities in owntone-server (2025)

This document describes multiple vulnerabilities identified in owntone-server from July 2025 to October 2025.

At the time of disclosure, all issues have been fixed in upstream commits.

---

## CVE-2025-57155

**Description**

NULL pointer dereference in the daap_reply_groups function in src/httpd_daap.c in owntone-server through commit 5e6f19a (newer commit after version 28.2) allows remote attackers to cause a Denial of Service.

**Affected Versions**

- owntone-server through commit 5e6f19a

**Impact**

- Denial of Service

**Fix**

- Fixed in commit: https://github.com/owntone/owntone-server/commit/d857116e4143a500d6a1ea13f4baa057ba3b0028

**References**

- Proof of concept: https://github.com/archersec/poc/tree/master/owntone-server-CVE-2025-57155

**Disclosure Timeline**

- 2025-07: CVE ID requested
- 2025-09: CVE ID assigned
- 2026-01: disclosed

---

## CVE-2025-57156

**Description**

NULL pointer dereference in the dacp_reply_playqueueedit_clear function in src/httpd_dacp.c in owntone-server through commit 6d604a1 (newer commit after version 28.12) allows remote attackers to cause a Denial of Service (crash).

**Affected Versions**

- owntone-server through commit 6d604a1

**Impact**

- Denial of Service

**Fix**

- Fixed in commit: https://github.com/owntone/owntone-server/commit/5e4d40ee03ae22ab79534bb1410fa9db96c9fabd

**References**

- Issue discussion: https://github.com/owntone/owntone-server/issues/1907

**Disclosure Timeline**

- 2025-07: CVE ID requested
- 2025-09: CVE ID assigned
- 2026-01: disclosed

---

## CVE-2025-63647

**Description**

A NULL pointer dereference in the parse_meta function (src/httpd_daap.c) of owntone-server commit 334beb allows attackers to cause a Denial of Service (DoS) via sending a crafted DAAP request to the server.

**Affected Versions**

- owntone-server through commit 334beb1

**Impact**

- Denial of Service

**Fix**

- Fixed in commit: https://github.com/owntone/owntone-server/commit/53ee9a3c3921e5448f502800c4dfa787865f6cb7

**References**

- Proof of concept: https://github.com/archersec/poc/tree/master/owntone-server

**Disclosure Timeline**

- 2025-10: CVE ID requested
- 2025-10: CVE ID assigned
- 2026-01: disclosed

---

## CVE-2025-63648

**Description**

A NULL pointer dereference in the dacp_reply_playqueueedit_move function (src/httpd_dacp.c) of owntone-server commit b7e385f allows attackers to cause a Denial of Service (DoS) via sending a crafted DACP request to the server.

**Affected Versions**

- owntone-server through commit b7e385f

**Impact**

- Denial of Service

**Fix**

- Fixed in commit: https://github.com/owntone/owntone-server/commit/5f526c7a7e08c567a5c72421d74a79dafdd07621

**References**

- Issue discussion: https://github.com/owntone/owntone-server/issues/1933

**Disclosure Timeline**

- 2025-10: CVE ID requested
- 2025-10: CVE ID assigned
- 2026-01: disclosed
