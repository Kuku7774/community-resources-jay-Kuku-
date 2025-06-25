# 🎫 Ticket System – SOP for Web3 Community Servers

This is a standard ticketing flow I've used in projects like GunStart Metaverse, Bitfinity, and Dmail — for support, reporting, collab requests, and feedback.

---

## 🛠️ Tools Used

- **TicketsBot** / **TypeForm + ModMail**  
- Optional: `@Ticket Support` role with access control  
- Separate private category: `🎫 Open Tickets`

---

## 🗂️ Ticket Categories

1. 🔧 Technical Support  
2. 🎁 Giveaway Issues  
3. 🤝 Collab & Partnership  
4. 🗣️ Feedback/Suggestions  
5. ⚠️ Report User/Scam

---

## ✅ Setup Flow

1. Create `#create-ticket` channel  
2. Add embed message with button:
   - “Open a Ticket” → creates private thread  
3. Auto-message inside ticket with template:
   > Hi! Please explain your issue briefly. A moderator will assist you shortly.

---

## 🧠 Management Tips

- Set cooldown so users can’t spam ticket creation  
- Close stale tickets after 48 hours inactivity  
- Use tag-based sorting (giveaway, collab, etc.)  
- Create internal `#mod-ticket-log` to track all activity

---

## 🔐 Access Permissions

| Role         | Access to ticket? |
|--------------|-------------------|
| @Admin       | ✅ Always |
| @Moderator   | ✅ Yes |
| @Everyone    | ❌ No |
| @Ticket Support | ✅ Limited based on category |

---

## 📊 Result

- Reduced DMs to team by 80%  
- Structured query handling  
- Reusable SOP across multiple projects

---

> Use this as a base to quickly deploy your own secure ticket system for any Web3 server.
