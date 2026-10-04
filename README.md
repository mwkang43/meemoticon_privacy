# Avaticon 개인정보처리방침 (Privacy Policy)

[한국어](#1-개요) · [English](#english-version)

## 1. 개요

Avaticon(이하 ‘앱’)은 사진으로 캐릭터와 이모티콘을 만드는 서비스이며, 이용자의 개인정보를 대한민국 「개인정보 보호법」, 유럽 일반개인정보보호법(GDPR) 등 관련 법령에 따라 처리합니다.

이 방침은 앱이 어떤 정보를 왜 수집하고, 누구와 공유하며, 얼마나 보관하는지와 이용자가 행사할 수 있는 권리를 설명합니다.

- 개인정보 처리자(운영자): [강민우]
- 연락처: mwkang43@gmail.com
- 적용 대상: Google Play에서 배포되는 Avaticon Android 앱과 앱이 사용하는 서버 기능

## 2. 수집하는 개인정보와 수집 방법

앱은 서비스 제공에 필요한 최소한의 정보만 수집하며, 항목별 수집 시점과 저장 위치는 아래와 같습니다.

| 항목 | 내용 | 수집 시점 | 저장 위치 |
| --- | --- | --- | --- |
| 익명 계정 식별자 | 앱이 자동 발급하는 사용자 ID | 앱 최초 실행 시 | 서버(Firebase) |
| 구글 계정 정보 (선택) | 이메일 주소, 이름, 프로필 사진, 구글 계정 식별자 | 구글 계정 연동 시 | 서버(Firebase) |
| 사진 | 캐릭터 생성을 위해 이용자가 촬영하거나 선택한 얼굴 사진 | 캐릭터 생성 시 | 기기 (AI 처리를 위해 일시 전송, 4장 참고) |
| 생성물과 입력 문구 | AI로 만든 캐릭터·이모티콘 이미지, 상황 설명·삽입 문구, 캐릭터 이름 | 생성 시 | 기기 |
| 클라우드 백업 데이터 (선택) | 백업을 선택한 캐릭터·이모티콘 이미지와 설정 값 | 백업 실행 시 | 서버(Firebase) |
| 생년월 | 태어난 연도와 월 | 앱 최초 실행 시 | **기기에만 저장** (서버로 전송하지 않음) |
| 코인 및 보상 기록 | 코인 잔액, 보상 거래 ID·금액·광고 네트워크·시각 | 보상 지급·사용 시 | 서버(Firebase) |
| 텔레그램 연동 정보 (선택) | 텔레그램 사용자 ID | 텔레그램 연동 시 | 서버(Firebase) |
| 자동 수집 정보 | 광고 ID, IP 주소, 기기 모델·OS 버전, 앱 이용 기록, 오류 기록 | 앱 이용 중 | 앱 서버 및 광고·오퍼월 업체 |
| 동의 기록 | 맞춤형 광고 동의 여부(IAB TCF 표준 값) | 동의 화면 응답 시 | 기기 |

앱은 이용자의 외부 계정 비밀번호, 연락처 목록, 개인 대화 내용, 정밀 위치 정보를 수집하지 않습니다.

설문 서비스(RapidoReach)를 이용하는 경우, 설문 프로필과 응답은 앱이 아닌 해당 업체가 직접 수집합니다.

## 3. 개인정보 이용 목적과 처리 근거

수집한 정보는 아래 목적에만 사용하며, 유럽 이용자에 대해서는 각 목적에 표시한 GDPR상 처리 근거를 적용합니다.

| 목적 | 사용하는 정보 | 처리 근거 (GDPR) |
| --- | --- | --- |
| 캐릭터·이모티콘 생성 | 사진, 입력 문구 | 계약 이행 |
| 계정 유지, 기기 간 복원, 클라우드 백업 | 계정 식별자, 구글 계정 정보, 백업 데이터 | 계약 이행 |
| 코인 지급·차감, 보상 내역 관리 | 코인 및 보상 기록 | 계약 이행 |
| 부정 보상 방지, 보안, 오류 분석 | 거래 기록, IP 주소, 기기 정보, 오류 기록 | 정당한 이익 |
| 광고 표시 및 보상형 광고 제공 | 광고 ID, 기기 정보 | 비맞춤 광고: 정당한 이익 / 맞춤형 광고: **동의** |
| 연령에 맞는 기능 제공 | 생년월(기기 내 판단), 국가 코드 | 법적 의무 준수 |
| 외부 앱으로 스티커 내보내기 | 선택한 이모티콘 이미지, 텔레그램 사용자 ID | 계약 이행 |

앱은 이용자의 개인정보를 판매하지 않으며, 사진을 얼굴 인식을 통한 신원 확인이나 다른 사람 식별에 사용하지 않습니다.

## 4. 사진과 AI 처리

이용자가 올린 사진은 캐릭터·이모티콘 생성을 위해서만 외부 AI 서비스로 전송되며, 앱 운영자의 서버에는 별도로 저장되지 않습니다.

1. **기기 안 처리**: 얼굴 위치를 찾고 사진을 자르는 작업은 기기 안에서(Google ML Kit) 이루어지며, 이 단계에서는 사진이 외부로 전송되지 않습니다.
2. **외부 AI 처리**: 잘라낸 사진과 입력 문구는 앱의 서버 함수를 거쳐 아래 AI 서비스에 전송되고, 결과 이미지만 기기로 돌아옵니다.
   - Google Gemini: 사진 특징 분석, 문구 번역, 이미지 생성
   - Novita AI: 이미지 편집·생성
   - Replicate: 이미지 배경 제거
3. **보관**: 원본 사진의 임시 파일은 처리 후 기기에서 삭제되고, 생성된 캐릭터·이모티콘은 기기에 저장됩니다. 이용자가 클라우드 백업을 선택한 경우에만 생성물이 서버(Firebase Storage)에 저장됩니다.

각 AI 서비스 업체가 요청 데이터를 보관하는 기간과 방식은 해당 업체의 정책을 따릅니다.

**타인과 자녀의 사진**: 다른 사람의 사진은 본인의 동의를 받은 경우에만 올려야 합니다. 만 13세 미만 자녀의 사진은 부모 또는 법정대리인이 직접 올리는 경우에만 사용할 수 있습니다.

**부적절한 결과 신고**: AI가 부적절한 이미지를 만들었다면 앱 안의 신고 기능 또는 아래 문의처로 알려 주세요.

## 5. 제3자 서비스와 처리 위탁

앱은 서비스 운영과 보상 제공을 위해 아래 업체에 개인정보 처리를 맡기거나 제공하며, 각 업체는 자체 개인정보처리방침에 따라 정보를 처리합니다.

| 업체 | 역할 | 처리하는 정보 |
| --- | --- | --- |
| Google (Firebase) | 로그인, 데이터베이스, 파일 저장, 서버 함수, 앱 무결성 확인 | 계정 정보, 코인·보상 기록, 백업 데이터, 기기 정보 |
| Google (Gemini) | AI 사진 분석·번역·이미지 생성 | 사진, 입력 문구 |
| Novita AI | AI 이미지 편집·생성 | 사진, 입력 문구 |
| Replicate | 이미지 배경 제거 | 생성된 이미지 |
| Google (AdMob) | 배너·보상형 광고, 동의 관리(UMP) | 광고 ID, IP 주소, 기기 정보, 동의 상태 |
| Unity Technologies (Unity Ads) | AdMob을 통한 광고 입찰·제공 | 광고 ID, IP 주소, 기기 정보 |
| Meta (Audience Network) | AdMob을 통한 광고 입찰·제공 (활성화 시) | 광고 ID, IP 주소, 기기 정보 |
| Tapjoy (Unity Technologies 계열) | 미션 오퍼월, 보상 확인 | 앱 사용자 ID, 광고 ID, IP 주소, 미션 수행 기록 |
| RapidoReach | 설문 오퍼월, 보상 확인 | 앱 사용자 ID, 설문 프로필·응답, 기기 정보 |
| BitLabs (Prodege) | 설문 오퍼월 (활성화 시) | 앱 사용자 ID, 설문 프로필·응답, 기기 정보 |
| Telegram | 스티커팩 생성 (연동 시) | 텔레그램 사용자 ID, 선택한 이모티콘 이미지 |
| WhatsApp | 스티커팩 추가 (기기 안에서 전달) | 선택한 이모티콘 이미지 |

미션·설문 오퍼월은 연령 기준(7장)을 충족하는 이용자의 기기에서만 활성화됩니다. 새로운 업체를 추가하면 이 목록을 갱신합니다.

업체가 법령에 따라 수사기관 등에 정보를 제공해야 하는 경우를 제외하면, 앱은 위 목적 외에 개인정보를 제3자에게 제공하지 않습니다.

## 6. 광고와 동의 관리

앱은 무료로 제공되며 광고와 보상형 미션으로 운영되고, 맞춤형 광고는 이용자가 동의한 경우에만 표시됩니다.

- **동의 화면**: 유럽경제지역(EEA), 영국, 스위스 등 법적으로 필요한 지역의 이용자에게는 처음 실행 시 Google 인증 동의 관리 도구(UMP)로 동의 여부를 묻습니다.
- **동의하지 않는 경우**: 앱은 계속 이용할 수 있으며, 광고는 비맞춤 또는 제한된 형태로 표시됩니다.
- **동의 변경·철회**: 코인 충전소 하단의 ‘개인정보 및 광고 설정’에서 언제든지 바꿀 수 있으며, 바꾼 내용은 이후 요청되는 광고부터 적용됩니다.
- **미국 주별 규정**: 해당 지역 이용자는 개인정보를 맞춤형 광고에 활용하는 것을 거부할 수 있습니다.
- **광고 ID 재설정**: 기기의 설정 → Google → 광고에서 광고 ID를 재설정하거나 삭제할 수 있습니다.

동의 결과는 IAB 투명성 및 동의 프레임워크(TCF) 표준 형식으로 기기에 저장되며, 앱은 이를 광고·미션 업체에 전달합니다.

## 7. 이용 연령 기준

앱은 만 13세 이상을 대상으로 하며, 처음 실행 시 입력한 생년월과 이용 지역에 따라 이용할 수 있는 기능이 달라집니다.

| 대상 | 미션 (Tapjoy) | 설문 (RapidoReach 등) | 광고 |
| --- | --- | --- | --- |
| 만 13세 미만 | 앱 이용 불가 | 앱 이용 불가 | 앱 이용 불가 |
| 만 13~15세 | 이용 불가 | 이용 불가 | 청소년 등급 광고 |
| 만 16~17세 | 이용 가능 | 이용 불가 | 청소년 등급 광고 |
| 만 18세 이상 | 이용 가능 | 이용 가능 | 모든 광고 (동의 시 맞춤형) |
| 유럽 국가별 디지털 동의 연령 미만 | 이용 불가 | 이용 불가 | 비맞춤 광고만 |

생년월은 기기에만 저장되며 서버로 전송되지 않습니다. 잘못 입력한 경우 코인 충전소의 ‘생년월 수정’에서 제한된 횟수 안에서 고칠 수 있습니다.

앱은 만 13세 미만 아동의 개인정보를 알면서 수집하지 않습니다. 아동의 정보가 수집된 사실을 알게 되면 문의처로 알려 주세요. 확인 즉시 삭제합니다.

## 8. 보유 기간, 파기, 계정 삭제

개인정보는 이용 목적이 달성되거나 이용자가 삭제를 요청하면 지체 없이 파기합니다.

| 정보 | 보유 기간 |
| --- | --- |
| 계정 정보, 코인 잔액, 백업 데이터 | 계정 삭제 시까지 |
| 보상 거래 기록 | 부정 지급 방지 및 문의 대응을 위해 거래 후 1년 |
| 기기에 저장된 사진·생성물·생년월 | 앱 삭제 또는 앱 데이터 삭제 시까지 |
| 광고·오퍼월 업체가 수집한 정보 | 각 업체의 개인정보처리방침에 따름 |
| 서버 접속·오류 로그 (IP 주소 포함) | 수집 후 30일 (서비스 운영·보안 점검 목적) |

**계정과 데이터 삭제 요청**: 아래 문의처 이메일로 앱에 표시된 계정 정보(구글 계정 이메일 또는 사용자 ID)와 함께 삭제를 요청하면, 본인 확인 후 30일 이내에 계정, 코인, 클라우드 백업 데이터를 삭제합니다. 법령상 보관 의무가 있는 정보는 해당 기간만 분리 보관합니다.

계정을 삭제하면 보유한 코인과 클라우드 백업은 복구할 수 없습니다.

## 9. 이용자의 권리

이용자는 언제든지 자신의 개인정보에 대해 아래 권리를 행사할 수 있으며, 문의처로 요청하면 30일 이내에 답변합니다.

- 열람: 앱이 보유한 내 정보를 확인할 권리
- 정정: 틀린 정보를 고칠 권리
- 삭제: 정보와 계정의 삭제를 요구할 권리 (8장 참고)
- 처리 제한·이의 제기: 특정 처리의 중단을 요구할 권리
- 이동: 내 정보를 기계가 읽을 수 있는 형태로 받을 권리
- 동의 철회: 맞춤형 광고 등 동의에 기반한 처리를 언제든 철회할 권리 (6장 참고)

유럽 이용자는 거주 국가의 개인정보 보호 감독기관에 민원을 제기할 수 있고, 대한민국 이용자는 개인정보분쟁조정위원회 또는 개인정보침해신고센터(국번 없이 118)에 도움을 요청할 수 있습니다.

## 10. 국외 이전

앱의 서버(Firebase)와 AI·광고 업체는 주로 미국에 있어, 이용자의 정보가 거주 국가 밖으로 이전됩니다.

- 이전 국가: 미국 등 각 업체의 서버 소재지
- 이전 시점·방법: 서비스 이용 시 암호화된 네트워크(HTTPS)로 전송
- 이전 항목과 목적: 2·3·5장에 적은 내용과 같음
- 유럽 이용자 보호: 각 업체가 채택한 표준계약조항(SCC) 등 GDPR이 인정하는 보호 조치에 따름

국외 이전을 원하지 않는 경우 서비스 이용을 중단하고 계정 삭제를 요청할 수 있습니다.

## 11. 안전성 확보 조치

앱은 개인정보 보호를 위해 아래 조치를 시행합니다.

- 모든 통신의 암호화(HTTPS)
- 사용자별 접근 제한: 이용자는 자신의 데이터에만 접근 가능
- 코인 지급은 서버에서만 처리하며 광고·오퍼월 업체의 서명을 검증
- API 키 등 비밀 정보는 앱이 아닌 서버에만 보관
- 생년월 등 민감할 수 있는 정보는 기기에만 저장

## 12. 방침 변경과 문의처

이 방침을 변경하면 시행 7일 전에(이용자에게 불리한 변경은 30일 전에) 앱 또는 이 페이지를 통해 알립니다.

- 앱 이름: Avaticon
- 개인정보 보호 책임자: [강민우]
- 이메일: mwkang43@gmail.com
- 최초 시행일: 2026년 9월 21일
- 최종 개정일: 2026년 10월 4일

---

## English version

### 1. Overview

Avaticon (the “App”) creates characters and stickers from your photos and processes personal data in line with the EU General Data Protection Regulation (GDPR), the Korean Personal Information Protection Act and other applicable laws.

- Controller: [Minwoo Kang]
- Contact: mwkang43@gmail.com
- Scope: the Avaticon Android app distributed on Google Play and its server functions

### 2. Data we collect

| Data | Details | When | Where stored |
| --- | --- | --- | --- |
| Anonymous account ID | User ID issued automatically by the App | First launch | Server (Firebase) |
| Google account data (optional) | Email, name, profile photo, Google account ID | When you link a Google account | Server (Firebase) |
| Photos | Face photos you take or choose to create a character | When creating a character | Device (sent temporarily for AI processing, see section 4) |
| Creations and text | AI-generated characters and stickers, situation text, sticker text, character names | When creating | Device |
| Cloud backup (optional) | Characters and stickers you choose to back up, and their settings | When you run a backup | Server (Firebase) |
| Year and month of birth | Birth year and month | First launch | **Device only** (never sent to our servers) |
| Coins and rewards | Coin balance, reward transaction ID, amount, ad network, time | When coins are earned or spent | Server (Firebase) |
| Telegram link (optional) | Telegram user ID | When you link Telegram | Server (Firebase) |
| Automatically collected | Advertising ID, IP address, device model, OS version, usage and error logs | While using the App | App servers and ad/offerwall partners |
| Consent record | Your ad consent choices (IAB TCF standard values) | When you answer the consent form | Device |

We do not collect passwords for other services, contacts, private messages or precise location. If you use the survey service (RapidoReach), your survey profile and answers are collected directly by that provider, not by the App.

### 3. Purposes and legal bases

| Purpose | Data used | Legal basis (GDPR) |
| --- | --- | --- |
| Creating characters and stickers | Photos, text | Contract |
| Account, restore across devices, cloud backup | Account ID, Google account data, backup data | Contract |
| Granting and spending coins | Coin and reward records | Contract |
| Fraud prevention, security, error analysis | Transaction records, IP address, device data, error logs | Legitimate interests |
| Showing ads and rewarded ads | Advertising ID, device data | Non-personalized ads: legitimate interests / Personalized ads: **consent** |
| Age-appropriate features | Birth year and month (checked on device), country code | Legal obligation |
| Exporting stickers to other apps | Selected sticker images, Telegram user ID | Contract |

We do not sell your personal data, and we do not use photos to identify you or anyone else through facial recognition.

### 4. Photos and AI processing

Photos are sent to external AI services only to create characters and stickers, and are not stored separately on our servers.

1. **On-device processing**: Finding and cropping the face is done on your device (Google ML Kit); the photo is not sent anywhere at this step.
2. **External AI processing**: The cropped photo and your text are sent through our server functions to the AI services below, and only the resulting image is returned to your device.
   - Google Gemini: photo analysis, text translation, image generation
   - Novita AI: image editing and generation
   - Replicate: background removal
3. **Storage**: Temporary copies of the original photo are deleted from your device after processing. Generated characters and stickers are stored on your device, and on our server (Firebase Storage) only if you choose cloud backup.

How long each AI provider keeps request data follows that provider’s own policy.

**Photos of others and of children**: Only upload photos of other people with their permission. Photos of children under 13 may only be uploaded by their parent or legal guardian.

**Reporting inappropriate results**: If the AI creates an inappropriate image, please report it through the in-app report option or the contact below.

### 5. Third-party services and processors

| Provider | Role | Data processed |
| --- | --- | --- |
| Google (Firebase) | Sign-in, database, file storage, server functions, app integrity | Account data, coin and reward records, backup data, device data |
| Google (Gemini) | AI photo analysis, translation, image generation | Photos, text |
| Novita AI | AI image editing and generation | Photos, text |
| Replicate | Background removal | Generated images |
| Google (AdMob) | Banner and rewarded ads, consent management (UMP) | Advertising ID, IP address, device data, consent status |
| Unity Technologies (Unity Ads) | Ad bidding and delivery through AdMob | Advertising ID, IP address, device data |
| Meta (Audience Network) | Ad bidding and delivery through AdMob (when enabled) | Advertising ID, IP address, device data |
| Tapjoy (a Unity Technologies company) | Mission offerwall, reward verification | App user ID, advertising ID, IP address, mission activity |
| RapidoReach | Survey offerwall, reward verification | App user ID, survey profile and answers, device data |
| BitLabs (Prodege) | Survey offerwall (when enabled) | App user ID, survey profile and answers, device data |
| Telegram | Sticker set creation (when linked) | Telegram user ID, selected sticker images |
| WhatsApp | Adding sticker packs (handed over on your device) | Selected sticker images |

Mission and survey offerwalls are only activated on devices of users who meet the age requirements in section 7. We will update this list when we add new providers. Apart from disclosures required by law, we do not share personal data with third parties for any other purpose.

### 6. Ads and consent

The App is free and funded by ads and rewarded missions. Personalized ads are shown only with your consent.

- **Consent form**: Users in the EEA, the UK, Switzerland and other regions where it is required are asked for consent on first launch through Google’s certified consent tool (UMP).
- **If you do not consent**: You can keep using the App; ads are shown in a non-personalized or limited form.
- **Changing or withdrawing consent**: Use “Privacy & ad settings” at the bottom of the Coin Station at any time. Changes apply to ads requested afterwards.
- **US state privacy laws**: Users in these states can opt out of the use of their data for personalized ads.
- **Advertising ID**: You can reset or delete it in your device’s Settings → Google → Ads.

### 7. Age requirements

The App is intended for users aged 13 and older. Available features depend on the birth year and month entered at first launch and on your region.

| User | Missions (Tapjoy) | Surveys (RapidoReach, etc.) | Ads |
| --- | --- | --- | --- |
| Under 13 | Cannot use the App | Cannot use the App | Cannot use the App |
| 13–15 | Not available | Not available | Teen-rated ads |
| 16–17 | Available | Not available | Teen-rated ads |
| 18 and older | Available | Available | All ads (personalized with consent) |
| Below the digital age of consent in your European country | Not available | Not available | Non-personalized ads only |

Your birth year and month are stored only on your device. If you entered them by mistake, you can correct them a limited number of times under “Edit date of birth” in the Coin Station. We do not knowingly collect personal data from children under 13. If you believe we have, please contact us and we will delete it promptly.

### 8. Retention and account deletion

| Data | Retention |
| --- | --- |
| Account data, coin balance, backup data | Until the account is deleted |
| Reward transaction records | 1 year after the transaction, for fraud prevention and support |
| Photos, creations and birth date on your device | Until you uninstall the App or clear its data |
| Data collected by ad and offerwall partners | As set out in each partner’s privacy policy |
| Server access and error logs (including IP address) | 30 days after collection, for operation and security checks |

**Requesting deletion**: Email the contact below with your account details (Google account email or user ID shown in the App). After verifying your identity, we will delete your account, coins and cloud backup within 30 days. Data we must keep by law is stored separately only for the required period. Deleted coins and backups cannot be restored.

### 9. Your rights

You can exercise the following rights at any time by contacting us; we respond within 30 days.

- Access: see the data we hold about you
- Rectification: correct inaccurate data
- Erasure: have your data and account deleted (see section 8)
- Restriction and objection: ask us to stop certain processing
- Portability: receive your data in a machine-readable format
- Withdrawal of consent: withdraw consent-based processing such as personalized ads (see section 6)

Users in Europe may lodge a complaint with the data protection authority in their country of residence.

### 10. International transfers

Our servers (Firebase) and AI and ad providers are mainly located in the United States, so your data is transferred outside your country of residence. Data is sent over encrypted connections (HTTPS) when you use the service. For users in Europe, transfers rely on safeguards recognized under the GDPR, such as the Standard Contractual Clauses adopted by each provider.

### 11. Security

- All communication is encrypted (HTTPS)
- Per-user access control: you can only access your own data
- Coins are granted only on our servers, after verifying signatures from ad and offerwall partners
- Secrets such as API keys are kept on our servers, not in the App
- Potentially sensitive data such as your birth date is stored only on your device

### 12. Changes and contact

We will announce changes to this policy in the App or on this page at least 7 days before they take effect (30 days for changes that reduce your rights).

- App: Avaticon
- Privacy contact: [Minwoo Kang]
- Email: mwkang43@gmail.com
- First effective date: 21 September 2026
- Last updated: 4 October 2026
