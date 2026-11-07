# Privacy Policy - AkkyApps / プライバシーポリシー

**Last updated: November 8, 2026**

## 日本語

AkkyApps（以下「当方」）は、個人開発者として iOS、iPadOS、watchOS、macOS アプリを開発しています。このプライバシーポリシーは、AkkyApps 名義で公開しているすべてのアプリに適用されます。

### アプリデータの保存

利用者が入力したテキスト、設定、環境設定、アプリ固有のコンテンツなどのデータは、原則として端末内、またはアプリやOSの設定により有効な場合はAppleが提供するiCloud等のサービスに保存されます。アプリ内の「ご意見・ご要望」または「お問い合わせ」フォームから利用者が送信した情報を除き、これらのデータをAkkyAppsが運営する外部サービスへ送信しません。

### 熱でた？の体温記録

熱でた？は、人物名、アバター、体温、測定日時、入力途中の内容をiPhone内に保存します。これらの記録をAkkyAppsのサーバーへ自動送信しません。アカウント登録、広告、行動分析、トラッキングはありません。

Infoに表示するAkkyAppsのアプリ一覧を更新するため、GitHub Pagesから公開一覧を取得します。この通信に人物名、アバター、体温、測定日時、記録ID、ヘルスケア情報は含めません。受信した一覧と更新確認用の情報は端末内に保存します。GitHubは、GitHub Pagesへの接続元IPアドレスをセキュリティ目的で記録・保存すると説明しています。通信先での情報の扱いは[GitHubのプライバシーステートメント](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement)をご確認ください。

アプリ独自のiCloud同期は行いません。記録用フォルダにはOSのバックアップから除外する設定を適用します。この設定は、以前のバックアップを削除するものではありません。利用者自身がエクスポートしたファイルや、Appleヘルスケアに保存したデータの扱いは、選んだサービスやOSの設定によります。

Appleヘルスケア連携は任意で、このiPhoneの本人の体温と測定日時を対象とします。重複防止と更新のため、記録の識別情報・更新情報・タイムゾーンも使用します。保存連携をオンにすると、過去の記録や、その後の訂正・アーカイブ・復元も反映します。取得は利用者の操作時だけ行い、無料版は今日を含む30暦日、Plusは読み取りを許可された全期間が対象です。外部由来の取得済みコピーを編集しても、元のヘルスケア記録は変更しません。権限を取り消しても、取得済みコピーはアプリ内に残ります。ヘルスケアの情報を広告やマーケティングに使用しません。

エクスポートでは、人物名、アバター、体温、日時、記録と取得元の識別情報を含むファイルを、利用者が選んだ保存先や共有先へ渡します。アーカイブした人物と記録は復元のため保持します。端末内のアプリデータはアプリの削除で削除できます。Appleヘルスケア内のデータと、保存・共有済みのファイルは別途管理してください。

### ご意見・ご要望／お問い合わせ

対応アプリのフォームで利用者が送信ボタンを押した場合に限り、次の情報をAkkyAppsのサポート受付へ送信します。

- 入力した本文と選択したカテゴリ
- 返信を希望する場合に任意で入力したメールアドレス
- アプリ名、アプリID、Bundle ID、バージョン、ビルド番号
- OSバージョン、端末モデル、言語・地域設定

これらの情報はCloudflare上の非公開受付サービスへ暗号化通信で送られ、Cloudflare D1に一時保存された後、AkkyAppsSupportの非公開GitHub Issuesへ配送されます。食品リスト、音声データ、支払い情報はこのフォームから送信されません。送信内容を広告、利用者の追跡、行動分析に使用しません。

配送に成功した問い合わせ本文、任意のメールアドレス、アプリ・端末情報はD1から7日後に削除し、受付ID、アプリID、カテゴリ、配送状態、日時、非公開Issue番号などの配送メタデータは30日後に削除します。非公開GitHub Issueは、問い合わせ対応、経緯の確認、削除依頼への対応に必要な期間だけ保持します。削除を希望する場合は、下記の連絡先へご連絡ください。

不正利用防止のため、接続元IPアドレスから作成した不可逆なHMAC値を時間・日単位の送信回数制限に使用します。生のIPアドレスは保存せず、HMAC値は各制限期間の終了後に削除します。

### 筆算マスターの手書き学習

「たし算ひき算の筆算マスター」「かけ算の筆算マスター」「わり算の筆算マスター」では、見直し時に利用者が認識結果を修正した数字の画像を、手書き認識の調整に使用できます。修正画像、修正履歴、端末ごとの個人用認識モデルは、そのiPadのアプリ内だけに保存されます。AkkyAppsや第三者のサーバーには送信されません。

この学習機能はアプリの設定から停止でき、保存した修正画像と個人用認識モデルはいつでも削除できます。

### Pantryの音声入力

Pantryの音声入力はAppleの音声認識で文字に変換します。対応端末でPrivate Cloud Computeが利用できる場合は、食品を分け、食品・調味料の分類を確認するため、話した内容の文字起こしと言語をAppleのPrivate Cloud Computeへ送信します。文字起こしには、話した食品名、数量、期限などが含まれる場合があります。この確認のために録音音声自体をPrivate Cloud Computeへ送信することはありません。利用できない場合や確認が完了しない場合は、既存の解析処理で登録します。AkkyAppsのサーバーへ音声や文字起こしを送信することはありません。Appleによる処理にはAppleのプライバシーポリシーが適用されます。

### PantryのAIレシピ

PantryでAIレシピを依頼すると、食品・調味料の名前、期限までの日数、人数、味の好み、依頼内容、言語、直近の会話、在庫を参照する短い番号をAppleのPrivate Cloud Computeへ送信します。生成した下書きレシピも品質の見直しのため同じサービスへ送信します。登録した食品の数量と端末内の在庫UUIDは送信しません。AIレシピを依頼した時だけ送信し、AkkyAppsのサーバーではレシピ生成を行いません。会話履歴とピン留めしたレシピは端末内に保存します。共有在庫は参加者のiCloudへ保存します。Appleによる処理にはAppleのプライバシーポリシーが適用されます。

### 第三者サービス

当方のアプリは、第三者の分析、広告、トラッキングサービスを使用しません。上記のサポート受付にはCloudflareとGitHubを使用します。また、アプリの機能に応じてAppleのiCloud、音声認識、StoreKit等を使用します。各サービスによる処理には各社のプライバシーポリシーが適用されます。

### アプリ内課金

アプリ内課金を含むアプリでは、AppleのStoreKitフレームワークを使用します。購入処理はAppleにより行われます。当方は、支払い情報を受け取ったり保存したりしません。

### お問い合わせ

本ポリシーに関するお問い合わせは、以下へご連絡ください。

**Email:** akkyapps@icloud.com

### 変更について

本ポリシーは必要に応じて更新される場合があります。変更があった場合は、上記の「Last updated」の日付を更新します。

---

## English

AkkyApps ("we", "our") develops iOS, iPadOS, watchOS, and macOS applications as an individual developer. This privacy policy applies to all apps published under the AkkyApps name.

## App Data Storage

Data you enter, such as text, settings, preferences, and app-specific content, is generally stored locally on your device or in Apple-provided services such as iCloud when enabled by the app or the system. Except for information you choose to submit through an in-app Feedback or Contact form, this data is not sent to external services operated by AkkyApps.

## Temperature Records in NetsuDeta

NetsuDeta stores names, avatars, temperatures, measurement dates, and unfinished input on your iPhone. It does not automatically upload these records to AkkyApps servers. The app has no account registration, advertising, behavioral analytics, or tracking.

To update the AkkyApps list in Info, NetsuDeta fetches a public catalog from GitHub Pages. The request does not include names, avatars, temperatures, measurement dates, record identifiers, or Health data. The catalog and information used to check for updates are stored on your device. GitHub states that it logs and stores GitHub Pages visitors' IP addresses for security purposes. See [GitHub's Privacy Statement](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement) for its handling of network request information.

The app does not provide its own iCloud sync. Its record folder is configured to be excluded from OS backups. This setting does not delete earlier backups. Files you export and data saved to Apple Health are managed according to the services you choose and your OS settings.

Apple Health integration is optional and applies to this iPhone user's temperature records and measurement dates. Record identifiers, revision information, and time zones are also used to prevent duplicates and apply updates. Enabling write sync also applies past records and subsequent edits, archives, and restores. Imports run only when you request them: the free version covers 30 calendar days including today, while Plus covers all history you authorize. Editing an imported external copy does not change the original in Apple Health. Revoking permission does not remove copies already imported into NetsuDeta. Health data is not used for advertising or marketing.

Export creates a file containing the person's name, avatar, temperatures, dates, and record and source identifiers for a destination you choose. Archived people and records are retained for restoration. Deleting the app removes its local app data. Manage data in Apple Health and files already saved or shared separately.

## Feedback and Support Inquiries

Only when you tap Send in a supported app's Feedback or Contact form, the following information is sent to the AkkyApps support intake service:

- The message you enter and the category you select
- An optional email address if you want a reply
- App name, app ID, bundle ID, version, and build number
- OS version, device model, and locale

This information is transmitted over an encrypted connection to a private intake service on Cloudflare, stored temporarily in Cloudflare D1, and then delivered to private GitHub Issues in the AkkyAppsSupport repository. Your food list, voice data, and payment information are not sent by this form. We do not use inquiry data for advertising, tracking, or behavioral analytics.

After successful delivery, the inquiry message, optional email address, and app/device information are removed from D1 after 7 days. Delivery metadata—such as the submission ID, app ID, category, delivery status, timestamps, and private Issue number—is removed after 30 days. A private GitHub Issue is retained only as long as needed to handle the inquiry, maintain necessary support context, and respond to deletion requests. To request deletion, contact us at the address below.

To prevent abuse, an irreversible HMAC derived from the connecting IP address is used for hourly and daily rate limits. The raw IP address is not stored, and the HMAC is deleted after its rate-limit window expires.

## Handwriting Learning in Written Calculation Master Apps

In Add & Subtract Master, Written Multiplication Master, and Long Division Master, images of digits corrected during review may be used to adapt handwriting recognition. Correction images, correction history, and the personal recognition model are stored only inside the app on that iPad. They are not sent to AkkyApps or any third-party server.

Handwriting learning can be turned off in the app's settings. Saved correction images and the personal recognition model can be deleted at any time.

## Voice Entry in Pantry

Pantry converts speech to text using Apple's speech recognition. On supported devices, when Private Cloud Compute is available, the transcript and language are sent to Apple's Private Cloud Compute to separate food items and check food and seasoning categories. The transcript may include food names, quantities and dates you mention. The recording itself is not sent to Private Cloud Compute for this check. If the service is unavailable or the check does not finish, Pantry uses its existing parsing to register the items. Audio and transcripts are not sent to AkkyApps servers. Apple's privacy policy applies to its processing.

## AI Recipes in Pantry

When you request an AI recipe in Pantry, food and seasoning names, days until expiry, servings, flavor preferences, your request, language, recent conversation, and short inventory reference numbers are sent to Apple's Private Cloud Compute. Draft recipes are also sent to the same service for review. Recorded inventory amounts and local inventory UUIDs are not sent. Data is sent only when you request an AI recipe; AkkyApps servers do not generate recipes. Chat history and pinned recipes are stored on your device. Shared inventory is stored in participants' iCloud accounts. Apple's privacy policy applies to its processing.

## Third-Party Services

Our apps do not use third-party analytics, advertising, or tracking services. Cloudflare and GitHub are used for the support intake described above. Depending on the app's features, Apple services such as iCloud, speech recognition, and StoreKit may also be used. Processing by those services is governed by their respective privacy policies.

## In-App Purchases

Apps that include in-app purchases use Apple's StoreKit framework. Purchase transactions are processed by Apple. We do not receive or store your payment information.

## Contact

If you have questions about this privacy policy, please contact us:

**Email:** akkyapps@icloud.com

## Changes to This Policy

We may update this policy from time to time. Any changes will be reflected by updating the "Last updated" date above.
