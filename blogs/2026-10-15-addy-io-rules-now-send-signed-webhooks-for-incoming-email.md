---
title: "addy.io Rules now send signed webhooks for incoming email"
url: "https://alternativeto.net/news/2026/10/addy-io-rules-now-send-signed-webhooks-for-incoming-email/"
date: "2026-10-15"
feed_url: "https://alternativeto.net/feeds/news/"
---
addy.io Rules can now send a signed JSON webhook to a public HTTPS URL when a matching email is accepted. The payload includes alias, sender, subject and message type, with optional message body and headers, while attachments are represented by a file count. Repeated delivery failures pause the affected URL for one hour and trigger an email notification, but the Rule remains active.
