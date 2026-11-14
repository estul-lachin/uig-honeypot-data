# uig-honeypot-data

Aggregated, privacy-safe output of the honeypot described in
https://github.com/estul-lachin/uig-honeypot, read by https://honeypot.uig.me.
Replaced every minute by a single force-pushed commit. No IP addresses.
recent.json (the last hour of events) is rebuilt every minute; the other files every hour.
reports/ holds one file per finished ISO week (UTC) and an index.json.
detections.json counts where the https://detections.uig.me rules fired in the last 30 days.
network.json summarizes the Suricata IDS alerts of the last 30 days (counts only).
IP geolocation by DB-IP (https://db-ip.com), CC BY 4.0.
