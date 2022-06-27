---
title: OpenSSL update assessment, and Node.js project plans
blogAuthors: ['node-js-website']
category: 'vulnerabilities'
---

## Summary

The vulnerabilities in the OpenSSL Security releases of Jun 21 2022 do not affect any active Node.js release lines.

## Analysis

Our assessment of the [security advisory](https://mta.openssl.org/pipermail/openssl-announce/2022-June/000228.html) is:

### The `c_rehash` script allows command injection (CVE-2022-2068)

Node.js doesn't use or ship the `c_rehash` script. Therefore, Node.js is not affected

### Contact and future updates

The current Node.js security policy can be found at <https://github.com/nodejs/node/blob/HEAD/SECURITY.md#security>,
including information on how to report a vulnerability in Node.js.

Subscribe to the low-volume announcement-only **nodejs-sec** mailing list at
<https://groups.google.com/forum/#!forum/nodejs-sec> to stay up to date on
security vulnerabilities and security-related releases of Node.js and the
projects maintained in the
[nodejs GitHub organization](https://github.com/nodejs).