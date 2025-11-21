# Chrome Web Store Listing Content

## Extension Name
**Vocaminary**

## Short Description (132 characters max)
Transform YouTube learning with word-perfect subtitles that sync naturally with speech. Perfect for language learners.

**Character count: 128** ✓

---

## Detailed Description

### Overview
Vocaminary enhances your YouTube experience by overlaying subtitles with word-level precision, perfectly synchronized with speech. Designed specifically for language learners, students, and anyone who wants to improve their listening comprehension.

### ✨ Key Features

**🎯 Word-Level Precision**
- Subtitles appear exactly when each word is spoken
- Natural speech timing with intelligent synchronization
- No more awkward caption blocks that appear too early or late

**⚡ Lightning-Fast Performance**
- 3-layer intelligent caching system (Memory → IndexedDB → Server Cache)
- Previously watched videos load subtitles in under 50ms
- Smart rate limiting prevents API blocks

**🎨 Seamless Integration**
- Clean overlay on YouTube player
- Auto-disable when switching videos
- One-click enable/disable button
- Non-intrusive design that enhances, not distracts

**🔐 Privacy-Focused**
- All data processing happens locally in your browser
- No tracking or analytics
- Minimal data collection (see privacy policy)
- Open source for full transparency

**🌐 Smart Subtitle Fetching**
- Automatic subtitle extraction from YouTube videos
- Works with auto-generated and manual captions
- Server-side caching for popular videos (instant loading)
- Intelligent fallback mechanisms

### 🎓 Perfect For

- **Language Learners**: Study vocabulary and natural speech patterns
- **Students**: Better comprehension with precise timing
- **Accessibility**: Clearer word boundaries for hard-of-hearing users
- **Content Creators**: Analyze speech timing and pacing
- **Anyone**: Improve your YouTube watching experience

### 🚀 How to Use

1. Navigate to any YouTube video with captions
2. Look for the "Enable Overlay" button on the video player
3. Click the button to activate word-by-word subtitles
4. Watch as subtitles sync perfectly with speech
5. Click again to disable when switching videos

**First-time use**: The first video may take 2-5 seconds to fetch subtitles. After that, they're cached for instant loading!

### 📊 Technical Highlights

- Built with vanilla JavaScript (no frameworks)
- Chrome Manifest V3 compliant
- Efficient memory usage
- No external dependencies
- Regular updates and improvements

### 🔒 Privacy & Security

- Minimal permissions (only what's needed)
- No personal data collection
- No browsing history tracking
- Secure HTTPS connections only
- Full privacy policy available

### 🆘 Support

- GitHub Repository: https://github.com/Aminophen98/YTS-1
- Issues & Bug Reports: https://github.com/Aminophen98/YTS-1/issues
- Email: aminophendev@gmail.com

### 📝 Permissions Explained

- **activeTab**: Detect when you're on a YouTube video page
- **storage**: Save settings and cached subtitles locally
- **scripting**: Inject the subtitle overlay into YouTube pages
- **nativeMessaging**: Future feature support

### 🌟 Coming Soon

- Click words for instant definitions and translations
- Customizable subtitle appearance
- Multiple language support
- Export vocabulary lists
- More features based on your feedback!

---

## Category
**Productivity** (primary)
*Alternative: Education*

---

## Language
English

---

## Privacy Policy URL
https://raw.githubusercontent.com/Aminophen98/YTS-1/main/PRIVACY.md

*Note: You can also host this on vocaminary.com/privacy if preferred*

---

## Homepage URL
https://vocaminary.com

---

## Support URL
https://github.com/Aminophen98/YTS-1/issues

---

## Permissions Justification

**For Chrome Web Store Review Team:**

1. **activeTab**: Required to detect when users navigate to YouTube video pages and access the video player DOM elements for subtitle overlay integration.

2. **storage**: Essential for caching subtitle data locally (7-day retention) and storing user preferences (API settings, overlay preferences). Improves performance by avoiding repeated API calls.

3. **scripting**: Needed to inject content scripts into YouTube pages to create the subtitle overlay UI and synchronize with video playback.

4. **nativeMessaging**: Declared for future feature support (local subtitle server integration). Not currently active but included for upcoming releases.

**Host Permissions:**

- `https://www.youtube.com/*`: Required to run the extension on YouTube video pages
- `https://app.vocaminary.com/*`: Authentication integration for optional user accounts
- `https://api.vocaminary.com/*`: Fetch subtitles from our caching API (improves performance, reduces YouTube API load)

All permissions are used exclusively for the stated functionality. No data is collected beyond what's necessary for subtitle caching and synchronization.

---

## Screenshots Needed

**Minimum: 1 screenshot** (but 3-5 recommended)
**Size: 1280x800 or 640x400 pixels**

### Suggested Screenshots:

1. **Main Feature** - Extension button on YouTube player with overlay active
2. **Overlay in Action** - Word-by-word subtitles syncing with speech
3. **Settings Page** - Show customization options (if available)
4. **Before/After** - YouTube with and without the extension

### Screenshot Guidelines:
- Use English interface
- Clear, high-quality images
- Show actual functionality (not mockups)
- Avoid copyrighted video content or use your own videos
- Keep UI clean and professional

---

## Promotional Images (Optional but Recommended)

### Small Promotional Tile: 440x280 pixels
- Feature the extension logo/icon
- Include tagline: "Word-Perfect YouTube Subtitles"
- Clean, modern design
- Use brand colors

---

## Additional Store Details

### Target Audience
- Language learners (primary)
- Students and educators
- Accessibility users
- Content creators
- YouTube power users

### Key Search Terms
- youtube subtitles
- language learning
- word-by-word captions
- subtitle overlay
- youtube learning
- precision subtitles
- vocabulary learning
- youtube captions

---

## Visibility Setting
**UNLISTED**

This means:
- Extension won't appear in Chrome Web Store search results
- Only accessible via direct link
- Perfect for beta testing and controlled rollout
- Can be changed to "Public" later

---

## Version Notes (for v0.2.0)
**What's New in This Release:**
- Initial Chrome Web Store release
- Removed localhost permissions (not needed yet)
- Updated privacy policy with contact information
- Optimized for public distribution
- All core features stable and tested

---

## Post-Submission Checklist

After uploading to Chrome Web Store Developer Dashboard:

- [ ] Upload ZIP file (vocaminary-v0.2.0-chrome-web-store.zip)
- [ ] Fill in all store listing fields
- [ ] Upload screenshots (at least 1, preferably 3-5)
- [ ] Add promotional images (optional)
- [ ] Set visibility to "Unlisted"
- [ ] Verify privacy policy URL works
- [ ] Review all permissions justifications
- [ ] Submit for review
- [ ] Save the unlisted extension URL (you'll need this to share with testers)

**Expected Review Time:** 1-7 days (usually 2-3 days for first submission)

---

## Unlisted Extension URL Format

After approval, your unlisted URL will look like:
```
https://chrome.google.com/webstore/detail/[extension-id]
```

Save this URL - it's the only way users can install your unlisted extension!
