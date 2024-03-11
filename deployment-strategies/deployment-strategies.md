##  Deployment strategy:
- A deployment strategy is technic for updating/changing a running application from one version  to other version
### why deployment strategy
- Zero Downtime
- reduced time-to-market
- faster rollback
- more frequency
### Deployment strategies types
1. Recreate
2. Rolling update
3. blue-green 
4. canary
5. A/B 
6. shadow 
### Recreate
- This strategy involves replacing the existing instances of the application with the new ones


## 𝐓𝐨𝐩 𝟓 𝐃𝐞𝐩𝐥𝐨𝐲𝐦𝐞𝐧𝐭 𝐏𝐚𝐭𝐭𝐞𝐫𝐧𝐬 𝐲𝐨𝐮 𝐧𝐞𝐞𝐝 𝐭𝐨 𝐤𝐧𝐨𝐰 𝐢𝐧 𝟐𝟎𝟐𝟑 !!


🌟𝗖𝗮𝗻𝗮𝗿𝘆 𝗥𝗲𝗹𝗲𝗮𝘀𝗲𝘀 🦜 Introduce new features to a small group of users first 👀 to test their performance and identify any issues ⚠ before rolling them out to everyone. This is like dipping your toe in the water before diving in headfirst 👣.

🌟𝗕𝗹𝘂𝗲/𝗚𝗿𝗲𝗲𝗻 𝗗𝗲𝗽𝗹𝗼𝘆𝗺𝗲𝗻𝘁: Create two identical production environments, one for live traffic 🚦 and one for testing 🧪. When you're ready to release a new feature, simply switch traffic from the blue environment to the green environment 🔄. This ensures a seamless transition with minimal downtime 🕑.

🌟𝗙𝗲𝗮𝘁𝘂𝗿𝗲 𝗧𝗼𝗴𝗴𝗹𝗲𝘀: Enable or disable features on demand 🚦, giving you flexibility in how and when you release new features. This is like having a superpower to control what your users see and experience 🧙♂.

🌟𝗔/𝗕 𝗧𝗲𝘀𝘁𝗶𝗻𝗴: Compare two versions of a feature to see which one performs better ⚖. This is like running a poll to gauge your users' preferences 📊.

🌟𝗗𝗮𝗿𝗸 𝗟𝗮𝘂𝗻𝗰𝗵𝗲𝘀: Release new features to a select group of users without any fanfare 🤫. This is like testing out a new outfit before you wear it in public .