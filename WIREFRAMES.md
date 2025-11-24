# UI/UX Wireframes: AI Skincare App

## 1. User Flow Overview

```
[Splash] --> [Onboarding] --> [Home Dashboard]
                                    |
              +---------------------+---------------------+
              |                     |                     |
        [Skin Scan]          [My Profile]          [Products]
              |                     |                     |
        [Analysis]           [History]            [Details]
              |                     |                     |
        [Recommendations]    [Progress]           [Purchase]
```

## 2. Screen Descriptions

### 2.1 Onboarding Flow

| Screen | Elements | Purpose |
|--------|----------|--------|
| Welcome | Logo, tagline, Get Started button | Brand introduction |
| Skin Quiz 1 | Skin type selection (oily/dry/combo/normal/sensitive) | Profile setup |
| Skin Quiz 2 | Skin concerns checklist (acne, aging, dark spots, etc.) | Personalization |
| Skin Quiz 3 | Allergies/sensitivities input | Safety |
| Permissions | Camera, notifications, health data access | Feature enablement |
| Profile Complete | Summary, Start Analyzing button | Confirmation |

### 2.2 Home Dashboard

```
+------------------------------------------+
|  [Menu]     SkinAI          [Notifications]|
+------------------------------------------+
|                                          |
|   +----------------------------------+   |
|   |     TODAY'S SKIN SCORE           |   |
|   |         [85/100]                 |   |
|   |    Hydration: Good               |   |
|   |    Clarity: Improving            |   |
|   +----------------------------------+   |
|                                          |
|   [  SCAN NOW  ]  (Primary CTA Button)   |
|                                          |
|   +----------------------------------+   |
|   |  DAILY ROUTINE                   |   |
|   |  Morning: 3 steps  [View]        |   |
|   |  Evening: 4 steps  [View]        |   |
|   +----------------------------------+   |
|                                          |
|   +----------------------------------+   |
|   |  PROGRESS THIS WEEK              |   |
|   |  [Graph: 7-day trend]            |   |
|   +----------------------------------+   |
|                                          |
+------------------------------------------+
|  [Home]  [Scan]  [Products]  [Profile]   |
+------------------------------------------+
```

### 2.3 Skin Scan Screen

```
+------------------------------------------+
|  [Back]       SKIN SCAN        [Help]    |
+------------------------------------------+
|                                          |
|   +----------------------------------+   |
|   |                                  |   |
|   |        [CAMERA VIEWFINDER]       |   |
|   |                                  |   |
|   |     Face outline guide overlay   |   |
|   |                                  |   |
|   +----------------------------------+   |
|                                          |
|   Lighting: [Good]  Distance: [OK]       |
|                                          |
|   Tips:                                  |
|   - Remove makeup for best results       |
|   - Use natural lighting                 |
|   - Hold device at arm's length          |
|                                          |
|          [  CAPTURE  ]                   |
|                                          |
|   [Gallery] [Switch Camera] [Flash]      |
|                                          |
+------------------------------------------+
```

### 2.4 Analysis Results Screen

```
+------------------------------------------+
|  [Back]      RESULTS         [Share]     |
+------------------------------------------+
|                                          |
|   +----------------------------------+   |
|   |  [Analyzed Photo with Overlays]  |   |
|   |   - Red zones: problem areas     |   |
|   |   - Green zones: healthy         |   |
|   +----------------------------------+   |
|                                          |
|   OVERALL SCORE: 78/100                  |
|                                          |
|   DETECTED CONDITIONS:                   |
|   +----------------------------------+   |
|   |  Acne (Mild)        [-->]        |   |
|   |  Forehead, Chin                  |   |
|   +----------------------------------+   |
|   |  Dryness (Moderate) [-->]        |   |
|   |  Cheeks                          |   |
|   +----------------------------------+   |
|   |  Dark Spots (Few)   [-->]        |   |
|   |  Under eyes                      |   |
|   +----------------------------------+   |
|                                          |
|   [  VIEW RECOMMENDATIONS  ]             |
|                                          |
+------------------------------------------+
```

### 2.5 Product Recommendations

```
+------------------------------------------+
|  [Back]    RECOMMENDATIONS               |
+------------------------------------------+
|                                          |
|   FOR YOUR: Mild Acne + Dryness          |
|                                          |
|   MORNING ROUTINE:                       |
|   +----------------------------------+   |
|   | [Img] Gentle Cleanser            |   |
|   |       Brand X - $24              |   |
|   |       Match: 95%   [Add]         |   |
|   +----------------------------------+   |
|   | [Img] Hydrating Serum            |   |
|   |       Brand Y - $38              |   |
|   |       Match: 92%   [Add]         |   |
|   +----------------------------------+   |
|   | [Img] SPF Moisturizer            |   |
|   |       Brand Z - $32              |   |
|   |       Match: 89%   [Add]         |   |
|   +----------------------------------+   |
|                                          |
|   EVENING ROUTINE:                       |
|   [Similar product cards...]             |
|                                          |
|   [  SAVE ROUTINE  ]  [  BUY ALL  ]      |
|                                          |
+------------------------------------------+
```

### 2.6 Progress Tracking

```
+------------------------------------------+
|  [Back]      MY PROGRESS                 |
+------------------------------------------+
|                                          |
|   [Week] [Month] [3 Months] [Year]       |
|                                          |
|   +----------------------------------+   |
|   |  SKIN SCORE TREND                |   |
|   |  [Line graph over time]          |   |
|   |  Current: 85  |  Start: 62       |   |
|   +----------------------------------+   |
|                                          |
|   IMPROVEMENTS:                          |
|   - Acne: -45% severity                  |
|   - Hydration: +30%                      |
|   - Dark spots: -20%                     |
|                                          |
|   PHOTO COMPARISON:                      |
|   +---------------+  +---------------+   |
|   |  [Week 1]     |  |  [Current]    |   |
|   |  Before photo |  |  After photo  |   |
|   +---------------+  +---------------+   |
|                                          |
|   [  EXPORT REPORT  ]                    |
|                                          |
+------------------------------------------+
```

### 2.7 Virtual Try-On (AR)

```
+------------------------------------------+
|  [Back]     VIRTUAL TRY-ON               |
+------------------------------------------+
|                                          |
|   +----------------------------------+   |
|   |                                  |   |
|   |   [LIVE CAMERA WITH AR OVERLAY]  |   |
|   |                                  |   |
|   |   Showing: Predicted results     |   |
|   |   after 4 weeks of treatment     |   |
|   |                                  |   |
|   +----------------------------------+   |
|                                          |
|   Timeline:                              |
|   [Now] [2wk] [4wk] [8wk] [12wk]         |
|                                          |
|   Product being simulated:               |
|   [Img] Retinol Serum - Brand X          |
|                                          |
|   [  TRY DIFFERENT PRODUCT  ]            |
|                                          |
+------------------------------------------+
```

## 3. Design System

### 3.1 Color Palette

| Color | Hex | Usage |
|-------|-----|------|
| Primary | #4A90D9 | CTAs, highlights |
| Secondary | #7ED9A6 | Success, healthy |
| Warning | #F5A623 | Caution, attention |
| Error | #D0021B | Problems, alerts |
| Background | #F8F9FA | Main background |
| Text | #2C3E50 | Primary text |

### 3.2 Typography

| Element | Font | Size | Weight |
|---------|------|------|--------|
| H1 | SF Pro / Roboto | 28px | Bold |
| H2 | SF Pro / Roboto | 22px | Semibold |
| Body | SF Pro / Roboto | 16px | Regular |
| Caption | SF Pro / Roboto | 12px | Regular |

### 3.3 Components

- **Buttons:** Rounded corners (8px), min height 48px
- **Cards:** Subtle shadow, 12px border radius
- **Icons:** Outlined style, 24px default size
- **Inputs:** 48px height, clear labels, validation states

## 4. Accessibility

- WCAG 2.1 AA compliant
- VoiceOver/TalkBack support
- Dynamic text sizing
- High contrast mode
- Haptic feedback for key actions

---

**Version:** 1.0  
**Last Updated:** November 24, 2025
