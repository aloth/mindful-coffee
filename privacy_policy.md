# Privacy Policy for Mindful Coffee

**Effective Date:** November 4, 2026

At Mindful Coffee ("we," "us," or "our"), operated by Alexander Loth, we are committed to protecting your privacy and ensuring that your data is handled responsibly. This Privacy Policy explains how we collect, use, and share information when you use our mobile application, Mindful Coffee ("App"), on iPhone, iPad, Mac and Apple Watch, including its widgets. We comply with applicable privacy laws and regulations including the General Data Protection Regulation (GDPR), California Consumer Privacy Act (CCPA), California Privacy Rights Act (CPRA), California Online Privacy Protection Act (CalOPPA), Virginia Consumer Data Protection Act (CDPA), the Children’s Online Privacy Protection Act (COPPA), and other relevant privacy laws.

## Summary

-   Your caffeine log, brew journal, settings and the Apple Health data the App reads stay on your device, or in your own private iCloud database if you turn on iCloud sync.
-   There is no account, no advertising, no tracking and no third-party analytics in the App.
-   The App contacts three services, none of which receives your caffeine log or health data: RevenueCat (purchases), a Firebase Cloud Function (only when you redeem an organization code) and our offer server (to show a current offer in Settings).

## 1. Information We Collect

We are committed to minimizing data collection. The information we handle can be categorized as follows:

### 1.1. Data You Provide and Store on Your Device
All data you enter into the App, such as caffeine logs, drinks, brew journal entries, recipes, notes and personal settings (e.g., metabolism preferences, thresholds, bedtime), is **stored on your device using SwiftData**. Widgets and the Apple Watch app use a shared container on your device and Apple's on-device Watch connection to show and log drinks. We do not transmit this data to our servers, and we do not have access to it.

AI Insights use Apple Intelligence (Foundation Models), which runs on your device. Your data is not sent to us or to any third-party AI service for this feature.

### 1.2. iCloud Sync (Optional, Off by Default)
If you turn on iCloud sync in the App's settings, your App data is synchronized through Apple's CloudKit to the **private database of your own iCloud account**, so it is available on your other devices signed in to the same Apple Account. This data is stored and protected by Apple under Apple's terms and privacy policy. We cannot access your private iCloud database. If you leave iCloud sync off, your data is stored only on the device.

### 1.3. Apple Health Integration (Optional)
With your explicit permission, the App integrates with Apple Health (HealthKit). You can grant or deny each data type individually.

The App **reads**:
-   **Dietary caffeine**, to import caffeine that other apps logged (optional setting).
-   **Sleep analysis**, to show how caffeine relates to your sleep and to estimate your usual wake time.
-   **Resting heart rate**, for caffeine correlation insights.
-   **Workouts**, to suggest caffeine timing around your training.

The App **writes** only **dietary caffeine**: one caffeine sample for each drink you log (optional setting), and it deletes that sample when you delete the drink in the App. The App does not write water, drink volume or any other Health data type, and it does not access clinical health records.

Health data read by the App is processed on your device. It is never sent to us, to RevenueCat, to Firebase or to any other third party, and it is never used for advertising or marketing.

### 1.4. In-App Purchases (RevenueCat)
To offer and manage premium features via in-app purchases (subscriptions or a one-time purchase), we use **RevenueCat** as a service provider.
-   **What RevenueCat Handles:** RevenueCat validates purchases, manages your subscription status and tells the App which features you have access to.
-   **Information Processed by RevenueCat:** Apple processes your payment; we never see or store your payment details. The App uses RevenueCat's anonymous app user ID, a random identifier created by RevenueCat that is not linked to your name, email or Apple Account. RevenueCat receives this ID together with your App Store purchase information (products, transactions, subscription status) and technical information needed to process requests, such as the App version, device type, OS version, storefront and IP address.
-   **What RevenueCat Does Not Receive:** The App does not send your caffeine log, brew journal or any health data to RevenueCat.
-   For more information, see **RevenueCat's Privacy Policy:** [https://www.revenuecat.com/privacy](https://www.revenuecat.com/privacy).

### 1.5. Organization Codes (Firebase Cloud Functions, Only When You Redeem a Code)
If your organization gives you an access code and you enter it in the App, the App sends the **organization name, the code and your anonymous RevenueCat app user ID** to a Cloud Function hosted on Google Firebase. The function checks the code and, if it is valid, grants access to the matching features through RevenueCat. This request is made only when you redeem a code. Firebase is used solely for this function; Firebase Analytics and advertising features are not included in the App. Google processes the request, including technical data such as your IP address, under its terms: [https://firebase.google.com/support/privacy](https://firebase.google.com/support/privacy).

### 1.6. Offer Badge
When you open the App's settings, the App may request the current offer from our server (gutscheinhub.de) to decide whether to show an offer badge. The request contains only the App identifier, the App version and your purchase tier (free, plus or pro). It contains no identifier for you or your device and no App data. As with any web request, the server receives your IP address, which is used only to deliver the response.

### 1.7. No Tracking, No Advertising, No Analytics
The App contains no advertising, no third-party analytics and no attribution or tracking SDK. It does not access the advertising identifier (IDFA), does not track you across apps or websites, and does not combine your data with data from other companies. Crash reports are only available to us if you choose to share them with developers through Apple's device settings; Apple provides them in aggregated, anonymized form.

## 2. How We Use Your Information

-   **To Provide App Functionality:** Your data on your device is used solely to deliver the App's features, such as tracking caffeine, predicting sleep readiness, analyzing trends and showing insights.
-   **To Manage Purchases:** Information processed by RevenueCat (section 1.4) and the organization code request (section 1.5) are used only to verify and manage your access to premium features.
-   **To Show Offers:** The offer badge request (section 1.6) is used only to decide whether an offer is shown.

## 3. Sharing of Your Information

-   **No Sale or Sharing of Personal Data:** We do not sell, rent, trade or share your personal data for advertising.
-   **Your App Data:** Your caffeine log, brew journal and health data remain on your device or in your private iCloud database and are not shared by us with any third party.
-   **Service Providers:**
    *   **Apple:** In-App Purchase payments, iCloud (CloudKit) sync, Apple Health and Apple Intelligence, according to Apple's terms and privacy policy.
    *   **RevenueCat:** Purchase and subscription management (section 1.4).
    *   **Google Firebase:** Organization code validation (section 1.5).
-   **Legal Requirements:** We may disclose information if required to do so by law or in the good faith belief that such action is necessary to comply with a legal obligation, protect and defend our rights or property, prevent fraud, act in urgent circumstances to protect the personal safety of users of the App, or protect against legal liability.

## 4. Data Security

Your App data is protected by your device's security and, if you use iCloud sync, by Apple's iCloud security. All calculations, analysis and AI insights run on your device. All network requests made by the App use encrypted HTTPS connections. However, no method of transmission over the Internet or method of electronic storage is 100% secure. Data managed by Apple, RevenueCat and Google Firebase is subject to their respective security practices.

## 5. Children's Privacy

Our App is not intended for children under the age of 16 (or a higher age threshold if stipulated by local law, e.g., in the EU). We do not knowingly collect personal data from children under this age. If we become aware that we have collected personal data from a child without verification of parental consent, we will take steps to delete that information. If you believe we might have any information from or about a child under the relevant age, please contact us.

## 6. Your Privacy Rights and Data Deletion

Depending on your location and applicable laws, you may have certain rights regarding your personal data. Because your App data stays on your device or in your iCloud, you can exercise most of these rights directly:
-   **Access and Correction:** View and edit your entries directly in the App.
-   **Deletion on Your Device:** Delete individual entries in the App, or delete the App to remove all data stored on the device.
-   **Deletion in iCloud:** If you used iCloud sync, deleting the App does not remove the synced copy. You can delete it in your device's Settings under your Apple Account, iCloud, Manage Account Storage (or Manage Storage), Mindful Coffee.
-   **Deletion in Apple Health:** Caffeine samples written by the App are removed when you delete the drink in the App. You can also delete them, and revoke the App's access, in the Health app or in Settings, Health, Data Access & Devices.
-   **Data Portability:** You can export your history as a CSV file (a premium feature).
-   **Purchase Data:** Manage subscriptions in your App Store account settings. To request access to or deletion of the purchase data RevenueCat holds for your anonymous app user ID, contact us (see section 10); we will forward the request to RevenueCat.

For residents of specific regions:
-   **EU/EEA/UK Residents (GDPR/UK GDPR):** You have rights including access, rectification, erasure, restriction of processing, data portability, and the right to object to processing.
-   **California Residents (CCPA/CPRA):** You have rights including the right to know what personal information is collected, used, and disclosed, the right to delete personal information, the right to opt out of the sale or sharing of personal information (we do not sell or share personal information), the right to correct inaccurate personal information, and the right to limit use and disclosure of sensitive personal information.

## 7. Data Retention

App data stays on your device until you delete it or the App, and in your private iCloud database until you delete it there. Purchase data held by RevenueCat and Apple is retained according to their policies. Organization code requests and offer badge requests are not used to build a profile of you; any server logs they create are retained only as long as needed for operation and security. Support emails are kept only as long as needed to answer your request.

## 8. International Data Transfers

Your App data resides on your device or in your iCloud. Service providers such as Apple, RevenueCat and Google may process the limited data described above in countries other than your own. We and our service providers take steps to ensure that any such transfers comply with applicable data protection laws.

## 9. Changes to This Privacy Policy

We may update this Privacy Policy from time to time to reflect changes in our practices, the App's functionality, or applicable laws. The updated policy will be posted in the App and/or on our website, and the "Effective Date" at the top will be revised. We encourage you to review this policy periodically. Your continued use of the App after any changes or revisions to this Privacy Policy shall indicate your agreement with the terms of such revised Privacy Policy.

## 10. Contact Us

If you have any questions, concerns, or requests regarding this Privacy Policy or our data practices, please contact:

-   **Alexander Loth**
    -   By email: [home@alexloth.com](mailto:home@alexloth.com)
    -   By visiting this page on our website: https://github.com/aloth/mindful-coffee

By using Mindful Coffee, you acknowledge that you have read and understood this Privacy Policy. If you do not agree with the terms of this policy, please do not use the App.
