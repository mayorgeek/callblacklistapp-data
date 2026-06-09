# Privacy Policy for Call Blacklist

**Last updated: June 9, 2026**

This Privacy Policy describes how Call Blacklist ("we", "our", or "the app") collects, uses, and handles your information when you use our Android application.

## Information We Collect

### Phone Numbers and Contact Data
- The app stores phone numbers you manually add to your blacklist and whitelist locally on your device.
- When a call is blocked, the caller's phone number and the blocking rule applied are saved locally in a history log.
- The app can read your device's contacts and call log **only if you grant permission** and **only to help you select numbers** to add to your blacklist or whitelist. This data is never transmitted off your device.

### No Personal Information Collection
- We do **not** collect, transmit, or share any personal information, device identifiers, or usage data.
- The app has **no analytics, no crash reporting SDKs, no advertising libraries, and no network permissions**. All data remains exclusively on your device.

## Permissions We Use

| Permission | Purpose |
|---|---|
| `READ_CONTACTS` | Lets you pick contacts to add to your block/allow lists |
| `READ_CALL_LOG` | Lets you select recent callers to add to your lists |
| `READ_PHONE_STATE` | Detects incoming calls to apply blocking rules |
| `ANSWER_PHONE_CALLS` | Required by the system to enable call screening |
| `POST_NOTIFICATIONS` | Shows notifications when calls are blocked (Android 13+) |

All permissions are optional. The app's core call-blocking functionality works with only the call screening role granted. You can deny any permission through your device Settings at any time.

## Call Screening Service

The app uses Android's `CallScreeningService` API to block unwanted calls. When enabled, incoming call details (phone number) are checked against your local blacklist/whitelist. This happens entirely on-device. The app does **not** record call audio or transmit call metadata.

## Data Storage and Security

All data — blacklist entries, whitelist entries, and blocked call history — is stored locally using Room (SQLite) and SharedPreferences on your device. No data is sent to any external server.

## Data Deletion

You can delete individual entries within the app at any time. To delete all data, uninstall the application. No residual data remains on our servers because no data is ever sent to any server.

## Third-Party Services

This app does **not** use any third-party services, analytics, crash reporting, advertising, or cloud storage.

## Children's Privacy

This app is not directed at children under 13. We do not knowingly collect any information from children.

## Changes to This Policy

We may update this Privacy Policy from time to time. Changes will be reflected by the "Last updated" date at the top of this policy.

## Contact Us

If you have questions about this Privacy Policy, contact us at: **[your-email@example.com]**
