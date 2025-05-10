# 🇫🇮 AdGuard / Pi-hole Finnish Blocklist

This is a custom blocklist focused on **Finnish ad, analytics, and tracking domains**. It's meant to be used with AdGuard Home, Pi-hole, or similar DNS-level blocking tools.

---

## ⚠️ Early Stage – Feedback Welcome!

I'm pretty new to making blocklists, and this is my first attempt. I decided to create this because I couldn’t find a well-maintained, Finnish-specific list anywhere.

So far, it's been working fine for me — but it's still in the early stages. If you notice anything missing, broken, or over-blocked, pull requests and issues are very welcome!

---

## ✅ What It Blocks

- Finnish ad networks  
- Media trackers on Finnish sites  
- Affiliate and analytics domains  
- Some common international trackers  (Use *alongside* a general-purpose blocklist)

---

## 🛠️ How to Use

### With Pi-hole:

1. Go to your Pi-hole admin panel → Group Managment → Lists
2. Add the raw URL of this list (https://raw.githubusercontent.com/ImFromKazakstan/finnish-adguard/main/blocklist.txt)
3. Click Add, then run `´pihole -g` or click Update Gravity.

### With AdGuard Home:

1. Go to Filters → DNS blocklists
2. Click Add blocklist and then Add a custom list
3. Paste the raw URL (e.g. https://raw.githubusercontent.com/ImFromKazakstan/finnish-adguard/main/blocklist.txt)
4. Click Save, then Update
