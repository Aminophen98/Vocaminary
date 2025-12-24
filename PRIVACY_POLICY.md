# Privacy Policy for Vocaminary

**Last Updated:** December 14, 2025

## Introduction

Vocaminary ("we", "our", or "us") is a Chrome extension that enhances YouTube's closed captions with clickable words and AI-powered definitions to help language learners study vocabulary while watching videos.

This Privacy Policy explains what data we collect, how we use it, and your rights regarding your personal information.

## What Data We Collect

### 1. Account Information

When you create a Vocaminary account:

- **Email address** - For account authentication and communication
- **User ID** - Unique identifier for your account
- **Account tier** - Your subscription level (Free, Early Adopter, Active Founder, or Premium)

### 2. Vocabulary Data

When you save words using the extension:

- **Words saved** - The vocabulary words you click to save
- **Definitions** - AI-generated or user-provided word definitions
- **Pronunciations** - Phonetic pronunciations (IPA format)
- **Translations** - Translations in your target language
- **Context sentences** - The sentence where the word appeared
- **Video information** - Video ID and title where you encountered the word
- **Timestamps** - When you saved each word

### 3. Video Watch History

When you use the caption overlay:

- **Video IDs** - YouTube videos you've watched with the overlay enabled
- **Video titles** - Titles of videos you've watched
- **View timestamps** - When you watched each video
- **View counts** - How many times you've watched each video

### 4. AI Usage Data

When you request word definitions:

- **Words looked up** - Which words you clicked for definitions
- **AI model used** - Which AI model processed your request (GPT-3.5-turbo)
- **Tokens consumed** - Number of tokens used (for cost tracking)
- **Request timestamps** - When you made each request
- **Success/failure status** - Whether the request succeeded

### 5. Caption Fetch Logs

When you enable the overlay on videos:

- **Video IDs fetched** - Which videos you requested captions for
- **Fetch timestamps** - When you requested captions
- **Success/failure status** - Whether the fetch succeeded
- **Rate limit tracking** - For enforcing daily/hourly limits

### 6. Usage Statistics

Aggregate statistics about your activity:

- **Total words saved** - Count of vocabulary words in your collection
- **AI calls made** - Number of AI definitions requested (public vs. private API)
- **Active days count** - Number of days you've used the extension
- **Monthly AI usage** - AI requests made this month (for tier-based limits)

## What Data Stays on Your Device (Local Storage)

The following data is stored locally on your device and **never** sent to our servers:

- **OpenAI API key** - If you provide your own key (stored in Chrome sync storage)
- **Cached subtitles** - Temporarily cached for 7 days in IndexedDB
- **User preferences** - Theme, font size, target language, definition level
- **Temporary usage counters** - For client-side rate limiting

## How We Use Your Data

### Primary Uses

1. **Provide core features**

   - Sync your saved words across all your devices
   - Display your vocabulary collection on the web dashboard
   - Generate AI-powered word definitions
   - Track your learning progress

2. **Enforce fair usage limits**

   - Apply tier-based monthly limits for AI definitions
   - Prevent abuse of shared resources
   - Rate limit caption fetching to protect server capacity

3. **Improve the service**
   - Analyze aggregate usage patterns (e.g., most popular videos across all users)
   - Identify common errors to improve reliability
   - Track total AI usage for cost management

### We DO NOT:

- ❌ Sell your data to third parties
- ❌ Use your data for advertising
- ❌ Share your individual saved words or watch history with anyone
- ❌ Track your browsing activity outside of YouTube
- ❌ Access your YouTube account or subscriptions

## Third-Party Services

We use the following third-party services to operate Vocaminary:

### 1. **Supabase** (Database Hosting)

- **What they process:** All user data listed above
- **Why:** Secure cloud database for storing your vocabulary and account
- **Privacy policy:** https://supabase.com/privacy
- **Location:** United States
- **Security:** Data encrypted at rest and in transit

### 2. **OpenAI API** (AI Definitions)

- **What they process:** Word + context sentence when you request definitions
- **Why:** Generate accurate word definitions, pronunciations, and translations
- **Privacy policy:** https://openai.com/privacy
- **Note:** OpenAI may use API requests for service improvement (per their policy)
- **Your API key:** If you provide your own OpenAI key, we never see it (stored locally only)

### 3. **Vocabumin-API** (Caption Fetching)

- **What they process:** YouTube video IDs when you enable the overlay
- **Why:** Fetch word-level synchronized captions from YouTube
- **Location:** Your own VPS server (api.vocaminary.com)
- **Caching:** Captions cached for 90 days to improve performance

## Data Security

We take security seriously:

- ✅ **Encryption** - All data encrypted in transit (HTTPS) and at rest (Supabase encryption)
- ✅ **Authentication** - Secure JWT token-based authentication
- ✅ **Access control** - User data isolated by authentication (you can only access your own data)
- ✅ **Secure storage** - Passwords hashed with industry-standard algorithms
- ✅ **Regular updates** - Extension and backend kept up to date with security patches

## Data Retention

- **Active accounts:** Data retained as long as your account exists
- **Deleted accounts:** All user data permanently deleted within 30 days
- **Cached subtitles:** Automatically deleted after 90 days (vocabumin-api) or 7 days (local)
- **Error logs:** Retained for 90 days for debugging, then automatically deleted

## Your Rights

You have the following rights regarding your data:

### 1. **Access Your Data**

- View all your saved words on the web dashboard at app.vocaminary.com
- See your video watch history and learning statistics
- Review your account tier and usage limits

### 2. **Export Your Data**

- Download all your saved words as CSV/JSON
- Available at: Dashboard → Settings → Export Data
- Includes: words, definitions, translations, video titles, dates

### 3. **Delete Your Data**

You can delete your data in two ways:

**Option A: Delete Account (deletes everything)**

- Go to app.vocaminary.com/settings
- Click "Delete Account"
- Confirm deletion
- All data permanently removed within 30 days

**Option B: Delete Individual Words**

- Click the trash icon next to any saved word
- Word removed immediately from all devices

### 4. **Request Data Deletion**

- Email support@vocaminary.com
- We'll respond within 7 days
- Data deleted within 30 days

### 5. **Opt Out of Analytics**

- We only collect service-essential analytics (usage limits, error tracking)
- No third-party tracking or advertising analytics
- No opt-out needed - we don't use invasive analytics

## Children's Privacy

Vocaminary is not directed at children under 13. We do not knowingly collect data from children under 13. If you believe a child under 13 has created an account, please contact us immediately at aminophendev@gmail.com.

## Changes to This Policy

We may update this Privacy Policy from time to time. We will notify you of any changes by:

- Updating the "Last Updated" date at the top
- Posting a notice on the extension or website
- Sending an email to your registered email address (for major changes)

Your continued use of Vocaminary after changes become effective constitutes acceptance of the updated policy.

## Legal Basis for Processing (GDPR)

For users in the European Union, we process your data under the following legal bases:

- **Contract performance** - To provide the services you signed up for
- **Legitimate interests** - To improve our service and prevent abuse
- **Consent** - For optional features (you can withdraw consent anytime)

## International Data Transfers

Your data may be transferred to and stored on servers outside your country of residence, including the United States. We ensure adequate safeguards are in place to protect your data in accordance with this Privacy Policy and applicable laws.

## Contact Us

If you have questions about this Privacy Policy or your data:

**Email:** aminophendev@gmail.com
**Website:** https://vocaminary.com
**GitHub:** https://github.com/aminophen98/vocaminary (for extension source code)

**Response time:** We typically respond within 7 business days.

## Summary (TL;DR)

✅ **What we collect:** Saved words, video watch history, AI usage (to provide vocabulary learning)
✅ **How we use it:** Sync across devices, show progress, enforce fair limits
✅ **What we don't do:** Sell data, track browsing, share with advertisers
✅ **Your rights:** Delete account anytime, export all data, request deletion
✅ **Security:** Encrypted database, secure authentication, regular updates

**Bottom line:** We only collect what's necessary to make Vocaminary work. Your vocabulary learning is private and secure.

---

_This policy is effective as of December 14, 2025 and applies to all users of the Vocaminary Chrome extension._
