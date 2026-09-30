[English](#playglow-privacy-policy) · [简体中文](#趣光隐私政策)

# Playglow Privacy Policy

Effective date: October 1, 2026

Developer: Ledi

Playglow ("the App") is built for playing, learning, and creating offline, with optional iCloud drawing sharing. This policy explains how the App handles information.

## Core Features and Optional Sharing

The core features don't require a developer account, show no ads, and don't track you across other apps or websites. Game records and drawing drafts stay on your device.

## Usage Statistics and Crash Reports

To learn which games and tools people enjoy, improve the membership purchase flow, and fix crashes, the App uses Firebase Analytics and Firebase Crashlytics from Google, which collect:

Which game or tool you open and how long you stay; game starts, endings, scores, and completed levels; membership page views, subscription actions, and their results (plan, whether it's a free trial, transaction amount and currency, but no payment details); a random instance identifier generated within the App; device model, system version, App version, language, and an approximate country or city derived from your IP address; crash logs when the App crashes.

This information doesn't include your name, email, Apple Account, photos, recordings, or drawings. It isn't linked to your identity, isn't used for advertising, and isn't used to track you across apps. The App doesn't access the advertising identifier (IDFA). The data is processed by Google and may be stored on servers outside your country or region. Statistics are kept for no more than 14 months, and crash logs for no more than 90 days.

## iCloud Drawing Sharing (Draw for You)

Only when you choose to use Draw for You does the App create a private shared canvas through Apple CloudKit. Both people need to be signed in to iCloud. When you create an invitation, the Apple Account email you enter for the other person is sent to Apple to find and invite that account; the App doesn't keep that email in its local drawing cache.

When you tap Send, the selected drawing image is uploaded to the creator's iCloud private database, and the invited account is given read and write access. Either person can update the latest drawing on the shared canvas. When you tap the widget's "Got it ❤️" button, the response for that drawing is synced to the other person; the shared record contains the drawing identifier, the sender's role in the connection, and the response status. The App uses CloudKit account and share record identifiers, update times, and device push notifications for access control and syncing. It doesn't automatically upload draft strokes, game records, or your entire photo library. These cloud services are provided by Apple.

To show drawings on the Home Screen, the App and its widget share the connection details and a cache of the latest drawing on the device. Disconnecting clears the local cache. If the creator disconnects, the shared canvas is deleted; if the invitee disconnects, they leave the share. The other person's offline device may keep showing the old cache until it next syncs, and images that were saved or captured can't be deleted remotely. Deleting the App doesn't guarantee that shared data in iCloud is deleted, so please disconnect before deleting the App.

## Data Stored on Your Device

Your game records, knowledge exploration progress, and unfinished drawings are stored only on your device so you can pick up where you left off. Deleting the App may remove this local data.

## Photos Permission

The App asks for "Add to Photos" permission only when you choose to save a drawing image or a stroke animation video to your photo library. This permission is used only to write the work you choose into your photo library. The App doesn't read your photos, and saving to Photos doesn't upload anything; a drawing is uploaded only if you separately send it with Draw for You.

## Camera and Microphone

The App uses the camera or microphone only while you're using a feature that needs it. Images and sound are processed on your device in real time. They are never uploaded to the developer's or any third party's servers, and never sent to Firebase.

The camera is used to: pick colors from the scene in Color Lab; take a photo and cut out the subject on your device in Sticker Maker; read scene brightness and exposure settings in Light Meter; follow your hand for air gestures in Knowledge Blocks, Free Draw, and Rhythm Flash; and power eye control (see "Face Data"). Apart from stickers you choose to save to your sticker collection, which stay on your device, the App doesn't keep camera images.

The microphone is used to: measure loudness in real time in Sound Meter, Shout Squad, and Sense Pilot, and recognize nearby sounds on your device in Sound Detective, none of which record audio; and record a short clip in Voice Changer to play back with effects. That clip is stored only on your device and is deleted when you leave the page. A sticker or voice clip is handed to another app only when you tap Share and choose that app.

## Face Data (TrueDepth Camera and ARKit Face Tracking)

**What is collected:** Only when you turn on eye control in Knowledge Blocks or Big Fish, or start a round of Sense Pilot, does the App use the TrueDepth camera through Apple's ARKit face tracking (on devices without TrueDepth, the front camera). The App reads only two kinds of values: where you are looking (ARKit's gaze point) and how closed each eye is. It immediately turns them into "looking left, center, or right" and "eyes closed or open". The App doesn't read or store face images, video, depth maps, face meshes, or any other face geometry.

**How it's used:** Only to control those games in real time, such as moving and rotating blocks, steering the fish toward where you look, and raising a shield when you close your eyes. Face data isn't used to identify or authenticate you, and isn't used for advertising, marketing, analytics, profiling, or tracking.

**Storage, retention, and deletion:** All processing happens in memory on your device in real time. Each frame's values are overwritten by the next frame as soon as the screen updates. Face tracking stops immediately when you turn off eye control, leave the game, or the App goes to the background. Face data is never written to device storage, never stored in iCloud, and never uploaded to any server, so there is no retention period and nothing to delete.

**Sharing:** Face data is never shared with, sold to, or disclosed to any third party, including Google Firebase. ARKit face tracking runs entirely on your device, so Apple doesn't receive it either.

You can turn off eye control at any time, or turn off the App's camera access in iPhone Settings > Privacy & Security > Camera. The other ways to play work without eye control.

## Playglow Plus Subscriptions

Playglow Plus is offered through Apple In-App Purchase as monthly and yearly auto-renewable subscriptions. Payment, renewal, free trials, and refunds are all handled by Apple, and the App doesn't collect or store your payment information. The App only reads from Apple whether a subscription is active, which plan it is, and when it expires, to show your membership status on your device; this isn't uploaded to the developer's servers. The plan and purchase results are sent to Firebase Analytics as anonymous statistics (see "Usage Statistics and Crash Reports"). You can manage or cancel your subscription at any time in iPhone Settings, under your Apple Account > Subscriptions.

## Children's Privacy

The core features don't require any personal information. Children using optional iCloud sharing should do so with a parent or guardian, and avoid including sensitive personal information in drawings.

## Changes to This Policy

If this policy changes materially, the effective date on this page will be updated.

## Contact Us

For privacy questions, please contact the developer, Ledi, through the support channel shown on the App Store product page.

---

# 趣光隐私政策

生效日期：2026 年 10 月 1 日

开发者：乐迪

趣光（“本 App”）是一款以离线玩、学、创造为主，并提供可选 iCloud 画作共享的应用。本政策说明本 App 如何处理信息。

## 核心玩法与可选共享

核心玩法不要求创建开发者账号，不包含广告，也不会跨 App 或网站跟踪你。游戏战绩与创作草稿保存在本机。

## 使用统计与崩溃报告

为了了解哪些游戏和工具更受欢迎、改进会员购买流程并修复闪退，本 App 使用 Google 提供的 Firebase Analytics 和 Firebase Crashlytics，收集以下信息：

打开了哪个游戏或工具及停留时长；游戏开局、结束、得分和过关；会员页面的浏览、订阅操作及结果（订阅方案、是否试用、交易金额与币种，不含任何付款信息）；App 内随机生成的实例标识符；设备型号、系统版本、App 版本、语言、由 IP 地址推算的大致国家或城市；发生闪退时的崩溃日志。

这些信息不包含姓名、邮箱、Apple 账户、照片、录音或画作，不与你的身份关联，不用于广告，也不用于跨 App 跟踪；本 App 不读取广告标识符（IDFA）。数据由 Google 处理，可能存储在你所在国家或地区以外的服务器上，统计数据保留不超过 14 个月，崩溃日志保留不超过 90 天。

## iCloud 双人画作共享

只有你主动使用「画给你」时，本 App 才通过 Apple CloudKit 创建私密共享画板。双方需要登录 iCloud。创建邀请时，你输入的对方 Apple 账户邮箱会提交给 Apple，用于查找并邀请该账户；本 App 不将该邮箱保存在本地画作缓存中。

点击发送后，所选画作图片上传到创建者的 iCloud 私有数据库，并对指定的受邀账户提供读写访问。双方都可以更新共享画板的最新画作。使用小组件的“收到啦 ❤️”按钮时，会将该画作的回应状态同步给对方；共享记录包含画作标识、发送方在连接中的角色及回应状态。本 App 使用 CloudKit 账户与共享记录标识、更新时间和设备推送机制完成访问控制与同步；不自动上传草稿笔迹、游戏战绩或整个相册。相关云服务由 Apple 提供。

为了在桌面显示画作，App 与小组件在设备上共享连接信息及最新画作缓存。解除连接会清除本机缓存；创建者解除连接也会删除该共享画板，受邀者解除连接则退出共享。对方的离线设备可能在下一次同步前仍显示旧缓存，已保存或截取的图片不会被远程删除。删除 App 不保证删除 iCloud 内的共享数据，请在删除 App 前使用解除连接功能。

## 设备本地数据

你的游戏战绩、知识探索进度和未完成画作仅保存在你的设备本地，用于让你下次继续使用。删除本 App 可能会移除这些本地数据。

## 照片权限

仅当你主动选择将画作图片或笔迹动画视频保存到系统相册时，本 App 会请求“添加到照片”权限。该权限只用于把你选择的作品写入系统照片图库；本 App 不会读取你的照片，不会因为保存到相册而上传作品；只有另行使用「画给你」发送时才上传所选画作。

## 相机与麦克风

本 App 只在你打开相关功能时使用相机或麦克风。画面和声音都在本机实时处理，不会上传到开发者或任何第三方的服务器，也不会发送给 Firebase。

相机用于：「色彩实验室」识别画面颜色；「抠图贴纸」拍照并在本机抠出主体；「测光表」读取画面亮度和曝光参数；「俄罗斯方块」「自由画画」「节奏闪击」的隔空手势识别手的位置；以及眼控（见“面部数据”）。除了你主动保存到贴纸收藏的贴纸图片保存在本机外，本 App 不保存相机画面。

麦克风用于：「分贝计」「大嗓门消防队」「三感星航」实时测量音量，「声音侦探」在本机识别周围的声音，这些功能都不录音；「变声器」录下一小段声音用于变声回放，录音只保存在本机，离开页面即删除。只有你主动点击分享时，所选贴纸或变声音频才会交给你选择的 App。

## 面部数据（原深感摄像头与 ARKit 面部追踪）

**收集什么**：只有你在「俄罗斯方块」或「大鱼吃小鱼」中打开眼控，或开始一局「三感星航」时，本 App 才通过 Apple ARKit 面部追踪使用原深感（TrueDepth）摄像头（不支持原深感的设备使用前置摄像头）。本 App 只读取两类数值：视线方向（ARKit 提供的注视点）和左右眼的闭眼程度，并立即换算成“向左、居中或向右看”和“是否闭眼”。本 App 不读取、不保存面部图像、视频、深度图、面部网格或其他面部几何数据。

**用途**：仅用于上述游戏的实时操控，例如移动和旋转方块、让小鱼游向你看的方向、闭眼开启护盾。面部数据不用于识别或验证身份，不用于广告、营销、数据分析或用户画像，也不用于跟踪。

**存储、保留与删除**：所有处理都在设备内存中实时完成，每一帧的数值在更新画面后即被下一帧覆盖丢弃；关闭眼控、离开游戏或 App 进入后台时，面部追踪立即停止。面部数据不写入设备存储，不存入 iCloud，也不上传到任何服务器，因此没有保留期，也没有需要删除的数据。

**共享**：面部数据不会与任何第三方（包括 Google Firebase）共享、出售或披露。ARKit 面部追踪完全在设备上运行，Apple 也不会收到这些数据。

你可以随时关闭眼控，或在 iPhone「设置」>「隐私与安全性」>「相机」中关闭本 App 的相机权限；不使用眼控不影响其他玩法。

## 趣光会员订阅

趣光会员通过 Apple 的 App 内购买提供，分为包月和包年两种自动续期订阅。付款、续订、免费试用和退款均由 Apple 处理，本 App 不会收集或保存你的付款信息。本 App 只从 Apple 读取订阅是否有效、订阅方案和到期时间，用于在本机显示会员状态，不会上传到开发者的服务器；订阅方案与购买结果会作为匿名统计发送给 Firebase Analytics（见“使用统计与崩溃报告”）。你可以随时在 iPhone「设置」中你的 Apple 账户下的「订阅」里管理或取消订阅。

## 儿童隐私

本 App 的核心玩法无需提供个人信息。儿童使用可选 iCloud 共享时，应在监护人指导下操作，避免在画作中包含个人敏感信息。

## 政策变更

如果本政策发生实质性变更，将在本页面更新生效日期。

## 联系我们

如有隐私问题，请通过 App Store Connect 产品页展示的技术支持渠道联系开发者乐迪。
