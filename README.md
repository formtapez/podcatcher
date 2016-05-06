Simple Podcatcher
-----------------

This project is a simple podcatcher which downloads new content from your subscribed podcasts.

**Features:**

  - Very efficient: Just downloads new content and quits
  - Ideal for cronjobs
  - Depends on: bash, wget, grep, head

**Crontab example:**
  7 6 * * * /root/scripts/podcatcher > /dev/null 2>&1
