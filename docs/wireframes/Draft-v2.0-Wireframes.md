# Zaza Promptly v2.0 - Wireframe Documentation

**Version:** 2.0  
**Document Type:** UX/UI Wireframe Specifications  
**Target Platforms:** iOS, Android, Web (PWA)  
**Screen Sizes:** Mobile-first, responsive design  
**Date:** July 2025  

---

## Navigation Architecture

```
App Structure:
├── Authentication Flow
│   ├── Welcome/Onboarding
│   ├── Sign In/Sign Up
│   └── Subscription Selection
├── Main Application
│   ├── Home/Dashboard
│   ├── Message Composer
│   ├── Message History
│   ├── Analytics & Coaching
│   ├── Templates & Quick Actions
│   └── Settings & Profile
└── Subscription Management
    ├── Upgrade/Downgrade
    └── Billing & Usage
```

---

## Screen Specifications

### 1. Welcome & Onboarding Flow

#### 1.1 Welcome Screen
```
┌─────────────────────────────────────┐
│  [Zaza Draft Logo]               │
│                                     │
│  "AI-Powered Communication         │
│   for Confident Educators"         │
│                                     │
│  • Rewrite messages instantly      │
│  • Professional tone guaranteed    │
│  • Save hours every week           │
│                                     │
│  [Get Started] [I Have an Account] │
│                                     │
│  "Trusted by 10,000+ educators"    │
└─────────────────────────────────────┘
```

#### 1.2 Onboarding Carousel (3 screens)
```
Screen 1/3:
┌─────────────────────────────────────┐
│  [◉ ○ ○]                          │
│                                     │
│     [Illustration: Stressed         │
│      teacher at computer]           │
│                                     │
│  "From Stress to Success"          │
│                                     │
│  Turn awkward parent messages into  │
│  professional communication that    │
│  builds trust and confidence.       │
│                                     │
│                [Next]              │
└─────────────────────────────────────┘

Screen 2/3:
┌─────────────────────────────────────┐
│  [○ ◉ ○]                          │
│                                     │
│     [Illustration: AI rewriting     │
│      message with magic wand]       │
│                                     │
│  "AI That Understands Education"   │
│                                     │
│  Our AI knows the difference        │
│  between a behavior concern and     │
│  a celebration message.             │
│                                     │
│         [Back]    [Next]           │
└─────────────────────────────────────┘

Screen 3/3:
┌─────────────────────────────────────┐
│  [○ ○ ◉]                          │
│                                     │
│     [Illustration: Teacher          │
│      confidently sending message]   │
│                                     │
│  "Send With Confidence"            │
│                                     │
│  Every message is reviewed for      │
│  tone, clarity, and professionalism │
│  before you hit send.               │
│                                     │
│         [Back]    [Get Started]    │
└─────────────────────────────────────┘
```

#### 1.3 Account Creation
```
┌─────────────────────────────────────┐
│  [← Back]    Create Account         │
│                                     │
│  Email Address                      │
│  [email@school.edu            ]    │
│                                     │
│  Password                           │
│  [••••••••••••                ]    │
│                                     │
│  What's your role?                  │
│  ◉ Classroom Teacher                │
│  ○ Administrator                    │
│  ○ Specialist                       │
│  ○ Other                           │
│                                     │
│  Grade Level (Optional)             │
│  [Dropdown: K-12, PreK, etc.]      │
│                                     │
│  □ I agree to Terms & Privacy       │
│                                     │
│  [Create Account]                   │
│                                     │
│  Already have an account? [Sign In] │
└─────────────────────────────────────┘
```

#### 1.4 Subscription Selection
```
┌─────────────────────────────────────┐
│  Choose Your Plan                   │
│                                     │
│  ┌─────────────┐  ┌─────────────┐   │
│  │    FREE     │  │     PRO     │   │
│  │             │  │             │   │
│  │    $0       │  │   $9.99     │   │
│  │   /month    │  │   /month    │   │
│  │             │  │             │   │
│  │ 10 rewrites │  │ Unlimited   │   │
│  │ Basic tones │  │ All features│   │
│  │ Templates   │  │ Voice input │   │
│  │             │  │ Analytics   │   │
│  │             │  │             │   │
│  │[Start Free]│  │[Try 7 Days] │   │
│  └─────────────┘  └─────────────┘   │
│                                     │
│  ✓ Cancel anytime                   │
│  ✓ No commitment                    │
│                                     │
│  [Skip for now]                     │
└─────────────────────────────────────┘
```

---

### 2. Main Dashboard

#### 2.1 Home Screen
```
┌─────────────────────────────────────┐
│  Good morning, Sarah! 🌅           │
│                                     │
│  ┌─────────────────────────────────┐ │
│  │ Quick Actions                   │ │
│  │                                 │ │
│  │ [📝 New Message] [⚡ Templates]│ │
│  │                                 │ │
│  │ [🆘 Panic Button] [📱 Voice]   │ │
│  └─────────────────────────────────┘ │
│                                     │
│  This Week                          │
│  ┌─────────────────────────────────┐ │
│  │ 12 messages improved            │ │
│  │ 2.5 hours saved                 │ │
│  │ 95% confidence score            │ │
│  └─────────────────────────────────┘ │
│                                     │
│  Recent Messages                    │
│  ┌─────────────────────────────────┐ │
│  │ Re: Alex's homework - 2h ago    │ │
│  │ "Thank you for bringing this... │ │
│  └─────────────────────────────────┘ │
│  ┌─────────────────────────────────┐ │
│  │ Pickup reminder - Yesterday     │ │
│  │ "I wanted to remind you that... │ │
│  └─────────────────────────────────┘ │
│                                     │
│  ────────────────────────────────── │
│  [🏠] [✏️] [📊] [⚙️]              │
└─────────────────────────────────────┘
```

---

### 3. Message Composer

#### 3.1 Main Composer Screen
```
┌─────────────────────────────────────┐
│  [← Back]    New Message            │
│                                     │
│  To: Parent/Guardian                │
│  [Search or type name...      ] [+] │
│                                     │
│  Subject                            │
│  [Re: Alex's behavior today    ]    │
│                                     │
│  Your Message                       │
│  ┌─────────────────────────────────┐ │
│  │ Alex was really disruptive in   │ │
│  │ class today and I'm frustrated. │ │
│  │ He kept talking and wouldn't    │ │
│  │ listen when I asked him to stop.│ │
│  │ This is becoming a problem.     │ │
│  │                                 │ │
│  │                                 │ │
│  └─────────────────────────────────┘ │
│  Characters: 183/1000               │
│                                     │
│  [🎤 Voice] [📋 Template] [✨ Rewrite] │
│                                     │
│  Message Type: Behavior Concern ▼   │
│  Tone: Professional ▼               │
└─────────────────────────────────────┘
```

#### 3.2 Rewrite Results Screen
```
┌─────────────────────────────────────┐
│  [← Back]    Rewrite Results        │
│                                     │
│  Original vs. Improved              │
│                                     │
│  ┌─────────────────────────────────┐ │
│  │ BEFORE                          │ │
│  │ Alex was really disruptive in   │ │
│  │ class today and I'm frustrated..│ │
│  └─────────────────────────────────┘ │
│                                     │
│  ┌─────────────────────────────────┐ │
│  │ AFTER ✨ AI Assistant          │ │
│  │ I wanted to discuss Alex's      │ │
│  │ classroom behavior today. He    │ │
│  │ had difficulty staying focused  │ │
│  │ and following directions. Could │ │
│  │ we schedule a brief chat?       │ │
│  │                                 │ │
│  │ Confidence: 94% ✅              │ │
│  └─────────────────────────────────┘ │
│                                     │
│  Key Improvements:                  │
│  • More professional tone          │
│  • Solution-focused language       │
│  • Removes emotional language      │
│                                     │
│  [✏️ Edit] [↩️ Try Again] [✅ Use This] │
└─────────────────────────────────────┘
```

#### 3.3 Alternative Suggestions
```
┌─────────────────────────────────────┐
│  Choose Your Approach               │
│                                     │
│  ┌─────────────────────────────────┐ │
│  │ 1. COLLABORATIVE 🤝            │ │
│  │ Confidence: 96%                 │ │
│  │                                 │ │
│  │ I'd love to partner with you... │ │
│  │ [Preview]                [Use]  │ │
│  └─────────────────────────────────┘ │
│                                     │
│  ┌─────────────────────────────────┐ │
│  │ 2. DIRECT 📋                   │ │
│  │ Confidence: 91%                 │ │
│  │                                 │ │
│  │ Alex had behavior challenges... │ │
│  │ [Preview]                [Use]  │ │
│  └─────────────────────────────────┘ │
│                                     │
│  ┌─────────────────────────────────┐ │
│  │ 3. WARM 💛                     │ │
│  │ Confidence: 88%                 │ │
│  │                                 │ │
│  │ I hope you're having a great... │ │
│  │ [Preview]                [Use]  │ │
│  └─────────────────────────────────┘ │
│                                     │
│  [← Back to Editor]                 │
└─────────────────────────────────────┘
```

#### 3.4 Send Confirmation
```
┌─────────────────────────────────────┐
│  Ready to Send?                     │
│                                     │
│  To: Maria Rodriguez                │
│  Subject: Re: Alex's behavior today │
│                                     │
│  ┌─────────────────────────────────┐ │
│  │ I wanted to discuss Alex's      │ │
│  │ classroom behavior today. He    │ │
│  │ had difficulty staying focused  │ │
│  │ and following directions. Could │ │
│  │ we schedule a brief chat to     │ │
│  │ discuss strategies that might   │ │
│  │ help him succeed?               │ │
│  │                                 │ │
│  │ Thank you,                      │ │
│  │ Ms. Johnson                     │ │
│  └─────────────────────────────────┘ │
│                                     │
│  □ Save as template                 │
│  □ Add to follow-up reminders       │
│                                     │
│  [← Edit More] [📤 Send Message]    │
│                                     │
│  ✨ Improved by AI Assistant        │
└─────────────────────────────────────┘
```

---

### 4. Quick Actions & Templates

#### 4.1 Template Library
```
┌─────────────────────────────────────┐
│  [← Back]    Message Templates      │
│                                     │
│  [Search templates...]              │
│                                     │
│  Quick Actions                      │
│  ┌─────────────────────────────────┐ │
│  │ 🆘 Need help now?              │ │
│  │ [Emergency Response]            │ │
│  └─────────────────────────────────┘ │
│                                     │
│  By Category                        │
│                                     │
│  📚 Academics (12)                  │
│  ┌─────────────────────────────────┐ │
│  │ Missing Assignment              │ │
│  │ Grade Update                    │ │
│  │ Extra Help Needed               │ │
│  └─────────────────────────────────┘ │
│                                     │
│  👥 Behavior (8)                    │
│  ┌─────────────────────────────────┐ │
│  │ Positive Behavior Note          │ │
│  │ Concern Discussion              │ │
│  │ Improvement Plan                │ │
│  └─────────────────────────────────┘ │
│                                     │
│  📅 Administrative (6)              │
│  ┌─────────────────────────────────┐ │
│  │ Pickup Reminder                 │ │
│  │ Field Trip Permission           │ │
│  │ Conference Request              │ │
│  └─────────────────────────────────┘ │
└─────────────────────────────────────┘
```

#### 4.2 Template Preview & Customize
```
┌─────────────────────────────────────┐
│  [← Back]    Missing Assignment     │
│                                     │
│  Preview                            │
│  ┌─────────────────────────────────┐ │
│  │ Hi [PARENT_NAME],               │ │
│  │                                 │ │
│  │ I wanted to let you know that   │ │
│  │ [STUDENT_NAME] hasn't turned in │ │
│  │ the [ASSIGNMENT_NAME] that was  │ │
│  │ due on [DUE_DATE].              │ │
│  │                                 │ │
│  │ [STUDENT_NAME] can still submit │ │
│  │ it for partial credit until     │ │
│  │ [LATE_DEADLINE].                │ │
│  │                                 │ │
│  │ Please let me know if there are │ │
│  │ any questions or if we need to  │ │
│  │ discuss this further.           │ │
│  │                                 │ │
│  │ Best regards,                   │ │
│  │ [TEACHER_NAME]                  │ │
│  └─────────────────────────────────┘ │
│                                     │
│  Tone: Professional ▼               │
│  Used 127 times by educators        │
│  ⭐⭐⭐⭐⭐ 4.8/5 rating            │
│                                     │
│  [Customize] [Use Template]         │
└─────────────────────────────────────┘
```

#### 4.3 Panic Button Flow
```
┌─────────────────────────────────────┐
│  🆘 Emergency Response              │
│                                     │
│  What's happening?                  │
│                                     │
│  ◉ Parent is upset/angry            │
│  ○ Student emergency/incident       │
│  ○ Missed deadline/forgot something │
│  ○ Complaint about my teaching      │
│  ○ Other urgent situation           │
│                                     │
│  Quick context (optional):          │
│  ┌─────────────────────────────────┐ │
│  │ Parent called me incompetent in │ │
│  │ front of other parents at       │ │
│  │ pickup...                       │ │
│  └─────────────────────────────────┘ │
│                                     │
│  [Generate Response]                │
│                                     │
│  ⏱️ Response ready in 3 seconds      │
│                                     │
│  Need to talk to someone?           │
│  [Contact Support] [Find Resources] │
└─────────────────────────────────────┘
```

---

### 5. Message History & Analytics

#### 5.1 Message History
```
┌─────────────────────────────────────┐
│  Message History                    │
│                                     │
│  [🔍 Search] [📅 Filter] [↗️ Export]│
│                                     │
│  Today                              │
│  ┌─────────────────────────────────┐ │
│  │ 2:30 PM • Re: Alex's behavior   │ │
│  │ To: Maria Rodriguez             │ │
│  │ ✨ AI Improved • Sent ✓        │ │
│  │ "I wanted to discuss Alex's..." │ │
│  └─────────────────────────────────┘ │
│                                     │
│  ┌─────────────────────────────────┐ │
│  │ 10:15 AM • Homework reminder    │ │
│  │ To: Multiple parents            │ │
│  │ 📋 Template • Sent ✓           │ │
│  │ "This is a friendly reminder..." │ │
│  └─────────────────────────────────┘ │
│                                     │
│  Yesterday                          │
│  ┌─────────────────────────────────┐ │
│  │ 4:45 PM • Great work today!     │ │
│  │ To: Jennifer Smith              │ │
│  │ ✨ AI Improved • Sent ✓        │ │
│  │ "I wanted to share some..."     │ │
│  └─────────────────────────────────┘ │
│                                     │
│  ────────────────────────────────── │
│  [🏠] [✏️] [📊] [⚙️]              │
└─────────────────────────────────────┘
```

#### 5.2 Message Detail View
```
┌─────────────────────────────────────┐
│  [← Back]    Message Details        │
│                                     │
│  To: Maria Rodriguez                │
│  Sent: Today, 2:30 PM               │
│  Subject: Re: Alex's behavior       │
│                                     │
│  Original Message                   │
│  ┌─────────────────────────────────┐ │
│  │ Alex was really disruptive in   │ │
│  │ class today and I'm frustrated. │ │
│  │ He kept talking and wouldn't... │ │
│  └─────────────────────────────────┘ │
│                                     │
│  AI Improved Version (Sent)         │
│  ┌─────────────────────────────────┐ │
│  │ I wanted to discuss Alex's      │ │
│  │ classroom behavior today. He    │ │
│  │ had difficulty staying focused..│ │
│  └─────────────────────────────────┘ │
│                                     │
│  Improvements Made:                 │
│  • Removed emotional language       │
│  • Added solution-focused approach  │
│  • Professional tone maintained     │
│                                     │
│  How did this message perform?      │
│  Response received: ✅ Yes (2h)      │
│  Tone was: ◉ Just right ○ Too soft  │
│              ○ Too formal           │
│                                     │
│  [💾 Save as Template] [🔄 Reuse]   │
└─────────────────────────────────────┘
```

---

### 6. Analytics & Coaching Dashboard

#### 6.1 Analytics Overview
```
┌─────────────────────────────────────┐
│  Your Communication Insights        │
│                                     │
│  This Week                          │
│  ┌─────────────────────────────────┐ │
│  │    15 Messages    2.5 Hours     │ │
│  │    Improved       Saved         │ │
│  │                                 │ │
│  │      94%          12            │ │
│  │  Confidence     Responses       │ │
│  └─────────────────────────────────┘ │
│                                     │
│  Communication Quality Trend        │
│  ┌─────────────────────────────────┐ │
│  │      ✨ 94%                    │ │
│  │     ╱                           │ │
│  │    ╱   92%                      │ │
│  │   ╱                             │ │
│  │  ╱     89%                      │ │
│  │ ╱                               │ │
│  │ Mon  Tue  Wed  Thu  Fri         │ │
│  └─────────────────────────────────┘ │
│                                     │
│  Message Types This Week            │
│  🎉 Positive (40%) ████████████     │
│  📚 Academic (35%) ██████████       │
│  👥 Behavior (15%) ████             │
│  📅 Admin (10%) ███                 │
│                                     │
│  [View Full Report]                 │
└─────────────────────────────────────┘
```

#### 6.2 Coaching Insights
```
┌─────────────────────────────────────┐
│  Personal Growth Coaching           │
│                                     │
│  Communication Strengths 💪         │
│  ┌─────────────────────────────────┐ │
│  │ ✅ Clear and concise writing    │ │
│  │ ✅ Professional tone            │ │
│  │ ✅ Solution-focused approach    │ │
│  └─────────────────────────────────┘ │
│                                     │
│  Growth Opportunities 🌱            │
│  ┌─────────────────────────────────┐ │
│  │ 💡 Try more collaborative      │ │
│  │    language in behavior msgs   │ │
│  │                                │ │
│  │ 💡 Add more specific examples  │ │
│  │    in academic discussions     │ │
│  └─────────────────────────────────┘ │
│                                     │
│  This Week's Reflection             │
│  ┌─────────────────────────────────┐ │
│  │ "How confident did you feel     │ │
│  │  with your communications?"     │ │
│  │                                 │ │
│  │  1  2  3  4  5  6  7  8  9  10  │ │
│  │  ○  ○  ○  ○  ○  ○  ○  ◉  ○  ○   │ │
│  │                                 │ │
│  │  What went well this week?      │ │
│  │  [Text input...]               │ │
│  └─────────────────────────────────┘ │
│                                     │
│  [Save Reflection]                  │
└─────────────────────────────────────┘
```

---

### 7. Settings & Profile

#### 7.1 Profile Settings
```
┌─────────────────────────────────────┐
│  [← Back]    Profile & Settings     │
│                                     │
│  Account Information                │
│  ┌─────────────────────────────────┐ │
│  │ Name: Sarah Johnson             │ │
│  │ Email: s.johnson@school.edu     │ │
│  │ Role: 3rd Grade Teacher         │ │
│  │ School: Elmwood Elementary      │ │
│  │                                 │ │
│  │ [Edit Profile]                  │ │
│  └─────────────────────────────────┘ │
│                                     │
│  Communication Preferences          │
│  ┌─────────────────────────────────┐ │
│  │ Default Tone: Professional ▼    │ │
│  │ Language: English ▼             │ │
│  │ Voice Input: ◉ On  ○ Off        │ │
│  │ Auto-save drafts: ◉ On  ○ Off   │ │
│  └─────────────────────────────────┘ │
│                                     │
│  Subscription                       │
│  ┌─────────────────────────────────┐ │
│  │ Current Plan: Pro ($9.99/mo)    │ │
│  │ Usage: 47/∞ messages            │ │
│  │ Renews: August 15, 2025         │ │
│  │                                 │ │
│  │ [Manage Subscription]           │ │
│  └─────────────────────────────────┘ │
│                                     │
│  [Help & Support] [Privacy Policy]  │
│  [Terms of Service] [Sign Out]      │
└─────────────────────────────────────┘
```

#### 7.2 Subscription Management
```
┌─────────────────────────────────────┐
│  [← Back]    Subscription           │
│                                     │
│  Current Plan: Pro                  │
│                                     │
│  ✅ Unlimited message rewrites      │
│  ✅ All tone options                │
│  ✅ Voice input                     │      
│  ✅ Analytics dashboard             │
│  ✅ Priority support                │
│                                     │
│  Usage This Month                   │
│  ┌─────────────────────────────────┐ │
│  │ Messages Improved: 47           │ │
│  │ Time Saved: 8.2 hours           │ │
│  │ Templates Used: 12              │ │
│  │ Voice Messages: 8               │ │
│  └─────────────────────────────────┘ │
│                                     │
│  Billing                            │
│  ┌─────────────────────────────────┐ │
│  │ Next charge: $9.99              │ │
│  │ Date: August 15, 2025           │ │
│  │ Method: •••• 4242               │ │
│  │                                 │ │
│  │ [Update Payment Method]         │ │
│  └─────────────────────────────────┘ │
│                                     │
│  [Upgrade to Premium] [Cancel Plan] │
│                                     │
│  Questions? [Contact Support]       │
└─────────────────────────────────────┘
```

---

### 8. Responsive Design Notes

#### Mobile Portrait (Primary)
- All wireframes above optimized for 375px width
- Single column layout
- Bottom navigation bar
- Swipe gestures for navigation
- Touch-friendly 44px minimum touch targets

#### Mobile Landscape
- Utilize horizontal space for side-by-side comparisons
- Keyboard overlay considerations
- Maintain primary navigation accessibility

#### Tablet & Desktop (Progressive Enhancement)
- Two-column layouts where appropriate
- Expanded template previews
- Enhanced analytics visualizations
- Keyboard shortcuts overlay

---

### 9. Key UX Principles

#### Accessibility
- WCAG 2.1 AA compliance
- Screen reader optimization
- High contrast mode support
- Large text support
- Voice control compatibility

#### Performance
- Loading states for AI processing
- Offline draft saving
- Progressive image loading
- Smooth animations (60fps)

#### Trust & Transparency
- Clear AI attribution
- Confidence scoring visibility
- Explanation of improvements
- User control over final content

#### Error Handling
- Graceful degradation for network issues
- Clear error messages with recovery options
- Auto-save draft recovery
- Alternative input methods when voice fails

---

*This wireframe document serves as the definitive UX/UI specification for Zaza Promptly v2.0. All screen designs should follow these layouts and principles while allowing for platform-specific design system adaptations.*