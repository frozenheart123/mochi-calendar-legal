# Mochi 日历 隐私政策 / Mochi Calendar Privacy Policy

最后更新：2026 年 9 月 24 日 · Last updated: 24 September 2026

## 中文

### 我们是谁

Mochi 日历（应用 ID：`com.mochicalendar.app`）是一款可以和朋友共享的日历应用。

联系方式：**mochicalendar.app@gmail.com**

### 我们收集什么

| 数据 | 什么时候收集 | 用来做什么 | 是否必填 |
|---|---|---|---|
| 昵称、头像选择、心情签名 | 你在应用里填写时 | 显示给你和你的好友 | 昵称有默认值，可改 |
| 好友码 | 创建账号时自动生成 | 让朋友能找到你 | 自动 |
| 日程内容（标题、日期、时间、地点、备注、贴纸） | 你创建日程时 | 显示日历、提醒你、共享给你邀请的人 | 你自己决定写什么 |
| 共享日历与成员关系 | 你创建共享日历或加好友时 | 让日历能被共同查看 | 可选功能 |
| 邀约与回复状态 | 你发出或回应邀约时 | 让对方知道你去不去 | 可选功能 |
| 好友申请 | 你输入别人的好友码时 | 对方同意后你们才成为好友 | 可选功能 |
| 推送令牌（一串设备编号）和应用语言 | 你允许通知后 | 把好友的邀约、回复、好友申请通知送到你的手机 | 可在手机设置里关闭通知 |
| 应用设置（主题、语言、每周起始日、提醒时间） | 你修改设置时 | 让设置跟着账号走 | 自动 |
| 电子邮箱、Google 账号 ID | **仅当**你主动点击"用 Google 保存账号"时 | 让你换手机后还能登回同一个账号 | **可选**，不绑定也能用 |

### 我们不收集什么

- **不收集位置信息。**
- **不收集通讯录。**
- **不上传你的照片。** 你设置的日历背景图**只保存在你自己的手机里**，从不上传服务器。
- **没有广告，没有第三方广告 SDK。**
- **没有埋点统计、没有行为追踪、没有用户画像。**
- **不出售、不交换你的任何数据。**

### 游客模式

打开应用即可使用，**不需要注册**。这时系统会创建一个匿名账号，它不包含你的邮箱、姓名或任何可以识别你身份的信息，只是一串随机 ID。

代价是：**卸载应用或更换手机后，游客账号的数据无法找回**。如果希望数据长期保留，请绑定 Google 账号。

### 谁能看到你的数据

- **只有你**能看到自己日历里的内容。
- **你邀请的人**能看到你邀请他们参加的那个日程（标题、时间、地点、备注）。
- **共享日历的成员**能看到这个日历里的日程。
- 你的**昵称、头像、好友码、心情签名**对已加你为好友的人可见。
- 你向谁发了好友申请（或谁向你发了申请），对方在处理申请前能看到你的**昵称、头像和好友码**。

数据库层面启用了行级安全策略（Row Level Security）：每条数据在数据库里就限定了谁能读写，不依赖应用端判断。

### 数据存在哪

数据存储在 Supabase 平台（基于 Amazon Web Services），服务器位于**新加坡**。传输全程使用 HTTPS 加密。

### 通知

- **日程提醒**由**你的手机本地生成**，不经过服务器，也不需要联网。
- **好友的邀约、回复和好友申请**是推送通知：服务器通过 **Expo 推送服务**和 **Google Firebase 云消息（FCM）**把它送到你的手机。通知里只有对方的昵称和日程标题。Expo 和 Google 只负责送达，不用于广告或统计。
- 退出登录或删除账号时，这台手机的推送令牌会被删除。你也可以随时在手机设置里关掉通知。

### 删除你的数据

**应用内删除**：打开应用 → **装扮** → **账号** → **删除账号** → 确认。

点击后立即永久删除：账号、日历、全部日程、贴纸、好友关系和好友申请、你创建的共享日历、推送令牌。删除后**无法恢复**。

也可以发邮件到 **mochicalendar.app@gmail.com** 要求删除，我们会在 30 天内处理。

### 儿童

本应用不面向 13 岁以下儿童，不会刻意收集儿童信息。

### 政策变更

本政策如有更新，会修改本页顶部的"最后更新"日期。重大变更会在应用内提示。

---

## English

### Who we are

Mochi Calendar (app ID `com.mochicalendar.app`) is a calendar app you can share with friends.

Contact: **mochicalendar.app@gmail.com**

### What we collect

| Data | When | Why | Required |
|---|---|---|---|
| Display name, chosen avatar, status message | When you type it in | Shown to you and your friends | Name has a default, editable |
| Friend code | Generated when the account is created | So friends can add you | Automatic |
| Plans (title, day, time, location, note, sticker) | When you create a plan | To show your calendar, remind you, and share with people you invite | You choose what to write |
| Shared calendars and membership | When you create a shared calendar or add a friend | So a calendar can be viewed together | Optional feature |
| Invitations and replies | When you send or answer an invitation | So the other person knows if you're coming | Optional feature |
| Friend requests | When you enter someone's friend code | You only become friends once they accept | Optional feature |
| Push token (a device identifier) and app language | Once you allow notifications | To deliver friends' invites, replies and friend requests to your phone | Notifications can be turned off in phone settings |
| Settings (theme, language, week start, reminder timing) | When you change them | So settings follow your account | Automatic |
| Email address and Google account ID | **Only** if you tap "Save with Google" | So you can sign back in on a new phone | **Optional** — the app works without it |

### What we do not collect

- **No location data.**
- **No contacts.**
- **No photo uploads.** A background photo you pick **stays on your phone** and is never uploaded.
- **No ads and no advertising SDKs.**
- **No analytics, no behavioural tracking, no profiling.**
- **We never sell or trade your data.**

### Guest mode

The app works immediately, with **no sign-up**. An anonymous account is created that holds no email, no name and nothing that identifies you — just a random ID.

The trade-off: **data in a guest account cannot be recovered** if you uninstall the app or switch phones. Link a Google account if you want it kept.

### Who can see your data

- **Only you** see the contents of your own calendar.
- **People you invite** see the plan you invited them to (title, time, location, note).
- **Members of a shared calendar** see the plans in that calendar.
- Your **name, avatar, friend code and status message** are visible to people who have added you as a friend.
- When you send someone a friend request (or they send you one), they can see your **name, avatar and friend code** until it is answered.

The database enforces this with row level security.

### Where data is stored

Data is stored on Supabase (running on Amazon Web Services) with servers in **Singapore**. All traffic is encrypted with HTTPS.

### Notifications

- **Plan reminders** are generated **locally on your phone**. They do not go through our servers and work offline.
- **Friends' invites, replies and friend requests** are push notifications: our server sends them through the **Expo push service** and **Google Firebase Cloud Messaging (FCM)**. A notification contains only the other person's name and the plan title. Expo and Google only deliver it; it is not used for ads or analytics.
- Signing out or deleting your account removes this phone's push token. You can turn notifications off in your phone settings at any time.

### Deleting your data

**In the app**: open the app → **Studio** → **Account** → **Delete account** → confirm.

That immediately and permanently deletes your account, calendars, all plans, stickers, friendships and friend requests, the shared calendars you created, and push tokens. It **cannot be undone**.

You can also **email** mochicalendar.app@gmail.com to request deletion; we will action it within 30 days.

### Children

This app is not directed at children under 13 and we do not knowingly collect their data.

### Changes

If this policy changes, the "Last updated" date at the top of this page changes with it.
