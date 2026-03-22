# Security Advisories of Vulnerabilities in owntone-server (2026)

This document describes multiple vulnerabilities identified in owntone-server in January 2026.

At the time of disclosure, all issues have been fixed in upstream commits.

---

## CVE-2026-26828

**Description**

A NULL pointer dereference in the daap_reply_playlists function (src/httpd_daap.c) of owntone-server commit 3d1652d allows attackers to cause a Denial of Service (DoS) via sending a crafted DAAP request to the server.

**Affected Versions**

- owntone-server through commit 3d1652d

**Impact**

- Denial of Service

**Fix**

- Fixed in commit: https://github.com/owntone/owntone-server/commit/9ac54f0b42491c4862791db4c5368ff80c4000d3

**References**

- Issue discussion: https://github.com/owntone/owntone-server/issues/1961

**Disclosure Timeline**

- 2026-01: CVE ID requested
- 2026-02: CVE ID assigned

---

## CVE-2026-26829

**Description**

A NULL pointer dereference in the safe_atou64 function (src/misc.c) of owntone-server through commit c4d57aa allows attackers to cause a Denial of Service (DoS) via sending a series of crafted HTTP requests to the server.

**Affected Versions**

- owntone-server through commit c4d57aa

**Impact**

- Denial of Service

**Fix**

- Fixed in commit: https://github.com/owntone/owntone-server/commit/41e3733cccd527918a08cf05694c5493341bb70f

**References**

- Proof of concept: https://github.com/archersec/poc/tree/master/owntone-server-2

**Disclosure Timeline**

- 2026-01: CVE ID requested
- 2026-02: CVE ID assigned

