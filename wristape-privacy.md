[English](#wristape-privacy-policy) · [简体中文](#腕声隐私政策)

# Wristape Privacy Policy

Last updated: October 20, 2026

Developer: Jorn

Wristape records your day on Apple Watch and helps you look back on it on iPhone. It has no server of its own, no account and no ads. Recordings, transcripts, reviews and memories stay on your own Apple Watch and iPhone; the developer never receives them. The only things the app sends the developer are anonymous usage statistics and crash reports, described below.

## What Wristape handles, and where

- **Microphone recordings.** Recorded on Apple Watch only when you start recording, sent to your iPhone over the system's watch connection, and deleted from the watch once they arrive.
- **Transcripts.** Made on your iPhone by Apple's on-device speech recognition, and kept only on that iPhone.
- **Voiceprints.** A set of numbers describing how each voice sounds, computed on your iPhone by a model built into the app, used only to tell speakers apart, and kept only on that iPhone. They are not used to identify who anyone is.
- **Heart rate.** Read from Health, only with your permission, to show it beside the day's transcript. Wristape never writes to Health.
- **Daily reviews and memories.** Made by Apple's on-device model by default, and kept only on your iPhone. You can edit, switch off or delete any memory.
- **Location, only if you add places.** Places are optional: quiet places, such as a clinic, where your Apple Watch stops recording, and places to record, such as the office, where it asks whether to start. When you add one, Wristape reads your iPhone's current location once, with your permission, and saves that point, a name and a radius on the iPhone. With "Always" permission, iOS tells Wristape when you arrive at or leave one of those places, even while it's closed. Wristape keeps no history of where you've been, and your location never leaves the iPhone: the watch is told only the place's name, so it can stop recording or ask to start. Delete a place, or turn off location for Wristape in Settings, at any time.
- **Calendar, only with your permission.** With "Brief me before meeting someone" on, Wristape reads upcoming events on this iPhone to find meetings with people you've named, and reminds you half an hour before of what's still open between you. With "Ask to record meetings" on, it finds the week's events with other people, and your Apple Watch asks a minute before each whether to record: for that, only each meeting's title and time go to your own Apple Watch. Nothing else from your calendar is stored, and nothing leaves your iPhone and watch. Turn either off in Settings, or remove calendar access in iOS Settings, at any time.
- **Day pictures, only if you turn them on.** With "Day pictures" on in Settings → AI and a cloud service you set up (OpenAI, Qwen or another), short descriptions of a comic page for a day, a panel for each part of it and one in the middle summing it up, are written from that day's review, from what Memory keeps about the people and things in your life so they look the same from day to day, and from the country people and places should look like (the one you choose, or else the one the language of your recordings suggests, or your iPhone's region), by the same model as the review. Only those descriptions, with the names you gave voices taken out, are sent to the service to draw the picture, straight from your iPhone with your own key. Once on, a picture is drawn after each of the last couple of days is reviewed, unless you turn that off too. The picture and its descriptions are kept only on this iPhone, outside iCloud backup, and go when you delete the day.
- **Search.** Transcripts are added to iOS's own search index on this iPhone, so the Home Screen's search can find what was said. The index never leaves the iPhone, and nothing is indexed while Wristape is locked.

Original audio is excluded from iCloud backup.

## Anonymous usage statistics

To learn which features are used and whether they work, the iPhone app sends anonymous events through Google Firebase Analytics: for example that a recording arrived from the watch (with its length in minutes and how many moments were marked), that a day was reviewed or a question answered (with which kind of model, and how many sentences the answer cited), that a backup was made (with or without audio and a password), or that something failed (with the kind of error only).

These events never contain recordings, transcripts, names, memories, your questions or their answers, places, or the text of error messages. The app doesn't collect the advertising identifier or the identifier for vendor, doesn't turn on advertising features, and doesn't track you across apps or websites. Firebase assigns the installation a random identifier that isn't linked to your identity; it also receives your device's model, system version, language and approximate region (from the network address), as all apps using it do. If the app crashes, a crash report is sent through Google Firebase Crashlytics: where in the app's code it happened, the device model, system version and free memory and storage. It contains nothing you recorded or wrote. Google processes the data under its own privacy policy (https://policies.google.com/privacy). Deleting the app removes the identifier.

## Cloud AI you choose yourself

In Settings you can switch to a cloud model, such as DeepSeek, Qwen, OpenAI or another compatible service, using your own API key. If you do:

- the transcript text needed for a review or an answer is sent directly from your iPhone to the provider you chose, with no Wristape server in between;
- audio never leaves your devices;
- the provider's own privacy policy applies to that text;
- your API key is kept in the iPhone's Keychain, on that device only.

The developer has no relationship with these providers and never receives this text.

## Backup files

You can make a backup file in Settings and save it wherever you choose. If you set a password, the file is encrypted with it, and nobody can open it without the password, the developer included; a forgotten password can't be recovered. Without a password the file isn't encrypted, so keep it somewhere private.

## Recording other people

Recording other people's conversations can require their consent, and the law differs from place to place. Let people know, and pause Wristape when a conversation isn't yours to keep. You are responsible for how you record.

## Deleting your data

You can delete a recording, a whole day, or everything at any time. Deleting the app removes everything it stored on your devices, except backup files you saved elsewhere.

## Children

Wristape isn't directed at children under 13.

## Changes

If this policy changes, this page will be updated along with the date above.

## Contact
Email bulayunkeji@gmail.com

---

# 腕声隐私政策

最后更新：2026 年 10 月 20 日

开发者：Jorn

腕声在 Apple Watch 上记录你的一天，并在 iPhone 上帮你回顾。它没有自己的服务器，没有账号，也没有广告。录音、转写、回顾和记忆只保存在你自己的 Apple Watch 和 iPhone 上，开发者永远拿不到。App 发给开发者的只有匿名使用统计和崩溃报告，详见下文。

## 腕声处理哪些信息，在哪里处理

- **麦克风录音。** 只有在你开始录音时才会在 Apple Watch 上录制，通过系统的手表连接传到你的 iPhone，送达后从手表上删除。
- **转写文字。** 由 Apple 的本机语音识别在你的 iPhone 上生成，只保存在这台 iPhone 上。
- **声纹。** 描述每个声音特征的一组数字，由 App 内置的模型在 iPhone 上计算，只用来分辨不同的说话人，只保存在这台 iPhone 上，不用于识别任何人的身份。
- **心率。** 在你允许后从"健康"读取，用来在当天的转写旁显示心率。腕声从不写入"健康"。
- **每日回顾和记忆。** 默认由 Apple 的本机模型生成，只保存在你的 iPhone 上。任何一条记忆你都可以修改、停用或删除。
- **位置（仅在你添加"不录音的地点"时）。** "不录音的地点"是可选功能，比如诊所，到了那里 Apple Watch 就停止录音。添加时，腕声在你允许后读取一次 iPhone 当前的位置，把这个点、名称和范围保存在 iPhone 上。如果你允许"始终"使用位置，iOS 会在你到达或离开这些地点时通知腕声，即使腕声没有打开。腕声不记录你去过哪里，你的位置也不会离开这台 iPhone：手表只会收到地点的名称，用来停止录音。你随时可以删除地点，或在"设置"里关闭腕声的位置权限。
- **日历（仅在你打开见面前提醒时）。** 打开"见面前提醒我聊过什么"并允许后，腕声会在这台 iPhone 上读取即将到来的日程，找出和你命名过的人的会面，提前半小时提醒你们之间还有哪些事没完成。日历内容不会被保存，也不会离开这台 iPhone。你随时可以在设置里关掉，或在 iOS 设置里取消日历权限。
- **搜索。** 转写会加入这台 iPhone 上 iOS 自己的搜索索引，在主屏幕搜索里就能搜到说过的话。索引不会离开这台 iPhone；腕声上锁时不建立索引。

原声音频不进入 iCloud 备份。

## 匿名使用统计

为了了解哪些功能有人用、是否正常工作，iPhone 上的 App 会通过 Google Firebase Analytics 发送匿名事件。例如：收到了一段手表录音（附带时长分钟数和标记了几处）、回顾了一天或回答了一个问题（附带用的是哪类模型、回答引用了几句原话）、做了一次备份（是否包含原声、是否设了密码），或者某个功能出错（只附带错误的类型）。

这些事件从不包含录音、转写、名字、记忆、你的问题和回答、地点，也不包含错误信息的文字。App 不收集广告标识符和供应商标识符，不开启任何广告功能，也不跨 App 或网站追踪你。Firebase 会给这次安装分配一个与你身份无关的随机标识符，并和所有使用它的 App 一样，收到设备型号、系统版本、语言和大致地区（根据网络地址推断）。如果 App 崩溃，会通过 Google Firebase Crashlytics 发送崩溃报告：崩溃发生在 App 代码的什么位置、设备型号、系统版本，以及剩余内存和存储空间。报告里没有任何你录下或写下的内容。Google 按其隐私政策处理这些数据（https://policies.google.com/privacy）。删除 App 即会删除这个标识符。

## 你自己选择的云端 AI

你可以在"设置"里改用云端模型，例如 DeepSeek、通义千问、OpenAI 或其他兼容服务，使用你自己的 API Key。这样做时：

- 生成回顾或回答问题需要的转写文字，会从你的 iPhone 直接发送给你选择的服务商，中间没有腕声的服务器；
- 音频从不离开你的设备；
- 这些文字适用该服务商自己的隐私政策；
- API Key 保存在 iPhone 的钥匙串里，仅限这台设备。

开发者与这些服务商没有合作关系，也不会收到这些文字。

## 备份文件

你可以在"设置"里制作备份文件，保存到你选择的位置。如果设了密码，备份文件会用这个密码加密，没有密码谁都打不开，包括开发者；密码忘了无法找回。不设密码的备份文件没有加密，请放在私密的地方。

## 录下他人

录下别人的谈话在一些地方需要对方同意，各地法律不同。请告知身边的人，在不属于你的谈话时暂停腕声。你需要对自己的录音方式负责。

## 删除数据

你可以随时删除一段录音、一整天或全部内容。删除 App 会删除它在你设备上保存的一切，你另存到别处的备份文件除外。

## 儿童

腕声不面向 13 岁以下儿童。

## 政策变更

本政策如有变更，会更新此页面和上方的日期。

## 联系方式
请发邮件至 bulayunkeji@gmail.com
