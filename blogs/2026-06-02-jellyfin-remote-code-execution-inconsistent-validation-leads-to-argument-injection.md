---
title: "Jellyfin remote code execution: Inconsistent validation leads to argument injection"
url: "https://www.sonarsource.com/blog/jellyfin-remote-code-execution/"
date: "2026-06-02"
author: "Paul Gerste"
feed_url: "https://www.sonarsource.com/blog/"
---
A validation bypass in Jellyfin's transcoding parameter processing (CVE-2026-35033) permits attackers to inject arbitrary FFmpeg arguments, enabling remote code execution on instances prior to version 10.11.7. The vulnerability exploits inconsistent input validation between individual query parameters and semicolon-separated parameter lists, allowing attackers to manipulate file operations and ultimately write shellcode to the .NET JIT compiler's memfd backing store for execution.
