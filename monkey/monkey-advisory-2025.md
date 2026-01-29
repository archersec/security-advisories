# Security Advisories of Vulnerabilities in Monkey (2025)

This document describes multiple vulnerabilities identified in the Monkey HTTP Server in October 2025.

At the time of disclosure, none of the issues have been fixed.

---

## CVE-2025-63649

**Description**

An out-of-bounds read in the http_parser_transfer_encoding_chunked function (mk_server/mk_http_parser.c) of monkey commit f37e984 allows attackers to cause a Denial of Service (DoS) via sending a crafted POST request to the server. 

**Affected Versions**

- Monkey through commit f37e984

**Impact**

- Denial of Service

**Fix**

- Not fixed yet

**References**

- Issue discussion: https://github.com/monkey/monkey/issues/426


**Disclosure Timeline**

- 2025-10: CVE ID requested
- 2025-10: CVE ID assigned

---

## CVE-2025-63650

**Description**

An out-of-bounds read in the mk_ptr_to_buf function (mk_core/mk_memory.c) of monkey commit f37e984 allows attackers to cause a Denial of Service (DoS) via sending a crafted HTTP request to the server.

**Affected Versions**

- Monkey through commit f37e984

**Impact**

- Denial of Service

**Fix**

- Not fixed yet

**References**

- Issue discussion: https://github.com/monkey/monkey/issues/426

**Disclosure Timeline**

- 2025-10: CVE ID requested
- 2025-10: CVE ID assigned

---

## CVE-2025-63651

**Description**

A use-after-free in the mk_string_char_search function (mk_core/mk_string.c) of monkey commit f37e984 allows attackers to cause a Denial of Service (DoS) via sending a crafted HTTP request to the server.

**Affected Versions**

- Monkey through commit f37e984

**Impact**

- Denial of Service

**Fix**

- Not fixed yet

**References**

- Issue discussion: https://github.com/monkey/monkey/issues/426

**Disclosure Timeline**

- 2025-10: CVE ID requested
- 2025-10: CVE ID assigned

---

## CVE-2025-63652

**Description**

A use-after-free in the mk_http_request_end function (mk_server/mk_http.c) of monkey commit f37e984 allows attackers to cause a Denial of Service (DoS) via sending a crafted HTTP request to the server.

**Affected Versions**

- Monkey through commit f37e984

**Impact**

- Denial of Service

**Fix**

- Not fixed yet

**References**

- Issue discussion: https://github.com/monkey/monkey/issues/426

**Disclosure Timeline**

- 2025-10: CVE ID requested
- 2025-10: CVE ID assigned

---

## CVE-2025-63653

**Description**

An out-of-bounds read in the mk_vhost_fdt_close function (mk_server/mk_vhost.c) of monkey commit f37e984 allows attackers to cause a Denial of Service (DoS) via sending a crafted HTTP request to the server.

**Affected Versions**

- Monkey through commit f37e984

**Impact**

- Denial of Service

**Fix**

- Not fixed yet

**References**

- Issue discussion: https://github.com/monkey/monkey/issues/426

**Disclosure Timeline**

- 2025-10: CVE ID requested
- 2025-10: CVE ID assigned

---

## CVE-2025-63655

**Description**

A NULL pointer dereference in the mk_http_range_parse function (mk_server/mk_http.c) of monkey commit f37e984 allows attackers to cause a Denial of Service (DoS) via sending a crafted HTTP request to the server.

**Affected Versions**

- Monkey through commit f37e984

**Impact**

- Denial of Service

**Fix**

- Not fixed yet

**References**

- Issue discussion: https://github.com/monkey/monkey/issues/427

**Disclosure Timeline**

- 2025-10: CVE ID requested
- 2025-10: CVE ID assigned

---

## CVE-2025-63656

**Description**

An out-of-bounds read in the header_cmp function (mk_server/mk_http_parser.c) of monkey commit f37e984 allows attackers to cause a Denial of Service (DoS) via sending a crafted HTTP request to the server.

**Affected Versions**

- Monkey through commit f37e984

**Impact**

- Denial of Service

**Fix**

- Not fixed yet

**References**

- Issue discussion: https://github.com/monkey/monkey/issues/426

**Disclosure Timeline**

- 2025-10: CVE ID requested
- 2025-10: CVE ID assigned

---

## CVE-2025-63657

**Description**

An out-of-bounds read in the mk_mimetype_find function (mk_server/mk_mimetype.c) of monkey commit f37e984 allows attackers to cause a Denial of Service (DoS) via sending a crafted HTTP request to the server.

**Affected Versions**

- Monkey through commit f37e984

**Impact**

- Denial of Service

**Fix**

- Not fixed yet

**References**

- Issue discussion: https://github.com/monkey/monkey/issues/426

**Disclosure Timeline**

- 2025-10: CVE ID requested
- 2025-10: CVE ID assigned

---

## CVE-2025-63658

**Description**

A stack overflow in the mk_http_index_lookup function (mk_server/mk_http.c) of monkey commit f37e984 allows attackers to cause a Denial of Service (DoS) or potentially cause a Remote Code Execution via sending a crafted HTTP request to the server.

**Affected Versions**

- Monkey through commit f37e984

**Impact**

- Denial of Service
- Code Execution

**Fix**

- Not fixed yet

**References**

- Issue discussion: https://github.com/monkey/monkey/issues/427

**Disclosure Timeline**

- 2025-10: CVE ID requested
- 2025-10: CVE ID assigned

