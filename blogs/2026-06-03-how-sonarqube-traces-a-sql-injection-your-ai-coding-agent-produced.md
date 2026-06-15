---
title: "How SonarQube traces a SQL injection your AI coding agent produced"
url: "https://www.sonarsource.com/blog/how-sonarqube-traces-a-sql-injection-your-ai-coding-agent-produced/"
date: "2026-06-03"
author: "Killian Carlsen-Phelan"
feed_url: "https://www.sonarsource.com/blog/"
---
SonarQube's taint analysis engine detects SQL injection vulnerabilities by building a data flow graph that follows data from where it enters the application to where it gets used in a dangerous operation. The article demonstrates how AI coding agents often reproduce insecure patterns because they lack visibility into data propagation across method boundaries, while SonarQube traces tainted user input through multiple files to pinpoint where it reaches vulnerable database calls.
