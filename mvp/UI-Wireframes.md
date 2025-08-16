# UI Wireframes - E-Commerce Platform MVP

## 1. Main Dashboard (Desktop 1200px+)

```
┌─────────────────────────────────────────────────────────────────────────────────┐
│ [LOGO]    Home > Dashboard                    🟢 AI Active    [Profile ▼]        │
├─────────────────────────────────────────────────────────────────────────────────┤
│ [+ New Order] [+ Add Product] [📱 Post to Social] [📧 Send Campaign]             │
├─────────────────────────────────────────────────────────────────────────────────┤
│                                                                                 │
│ ┌─────────────────────────────┐  ┌─────────────────────────────┐               │
│ │    📱 SOCIAL COMMERCE       │  │    📦 ORDER MANAGEMENT      │               │
│ │                             │  │                             │               │
│ │  💬 12 New Messages         │  │  📋 23 Pending Orders       │               │
│ │  📊 85% Response Rate       │  │  🚚 15 Ready to Ship        │               │
│ │  🤖 AI: 34 Auto-Replies    │  │  ⚠️  3 Urgent Orders        │               │
│ │                             │  │                             │               │
│ │  [View Inbox →]             │  │  [Process Orders →]         │               │
│ └─────────────────────────────┘  └─────────────────────────────┘               │
│                                                                                 │
│ ┌─────────────────────────────┐  ┌─────────────────────────────┐               │
│ │    📦 INVENTORY MANAGEMENT  │  │    📊 ANALYTICS & REPORTS   │               │
│ │                             │  │                             │               │
│ │  📊 1,247 Total Products    │  │  💰 ৳85,340 Today's Sales   │               │
│ │  ⚠️  23 Low Stock Items     │  │  📈 +12% vs Yesterday       │               │
│ │  📥 5 Pending Restocks      │  │  👥 167 Active Customers    │               │
│ │                             │  │                             │               │
│ │  [Manage Stock →]           │  │  [View Reports →]           │               │
│ └─────────────────────────────┘  └─────────────────────────────┘               │
│                                                                                 │
├─────────────────────────────────────────────────────────────────────────────────┤
│ Quick Stats: Orders (23) | Revenue (৳85K) | Stock Alerts (23) | Messages (12)  │
├─────────────────────────────────────────────────────────────────────────────────┤
│                                                                       [🔔 3] │
│ Role-based Widgets (Based on permissions):                                     │
│ ┌──────────────┐ ┌──────────────┐ ┌──────────────┐ ┌──────────────┐           │
│ │📈 Sales Today│ │👥 New Users  │ │📱 FB Reach   │ │🚚 Deliveries │           │
│ │   ৳12,340    │ │     8        │ │   2.1K       │ │    15        │           │
│ └──────────────┘ └──────────────┘ └──────────────┘ └──────────────┘           │
└─────────────────────────────────────────────────────────────────────────────────┘
```

## 2. Social Commerce Hub Detail View (Desktop)

```
┌─────────────────────────────────────────────────────────────────────────────────┐
│ [LOGO]    Home > Social Commerce Hub              🟡 AI Suggesting  [Profile ▼]  │
├─────────────────────────────────────────────────────────────────────────────────┤
│ 🤖 AI Mode: [●Auto] [○Manual]  |  Platform: [●FB] [○WA] [○IG]  |  [⚙️Settings]  │
├─────────────────────────────────────────────────────────────────────────────────┤
│                                                                                 │
│ ┌──────────────┐ ┌─────────────────────────────────┐ ┌─────────────────────────┐ │
│ │ CONVERSATIONS│ │           CHAT VIEW             │ │    CUSTOMER PROFILE     │ │
│ │              │ │                                 │ │                         │ │
│ │ 🔵 Ahmad     │ │ Ahmad Rahman                    │ │ 👤 Ahmad Rahman         │ │
│ │    "price?"  │ │ ┌─────────────────────────────┐ │ │ 📱 +880171234567       │ │
│ │    2m ago    │ │ │ price koto vai?             │ │ │ 📍 Dhaka, Bangladesh   │ │
│ │              │ │ └─────────────────────────────┘ │ │                         │ │
│ │ 🟢 Sarah     │ │                                 │ │ 🛒 Previous Orders: 3   │ │
│ │    "available│ │ 🤖 AI Suggests:                │ │ 💰 Total Spent: ৳4,500  │ │
│ │     ??"      │ │ ┌─────────────────────────────┐ │ │ ⭐ Rating: 4.8/5        │ │
│ │    5m ago    │ │ │"এই প্রোডাক্টের দাম ৳1,200।   │ │ │                         │ │
│ │              │ │ │ আজকে 10% ছাড় আছে!"        │ │ │ 📊 Interaction History │ │
│ │ 🔴 Karim     │ │ └─────────────────────────────┘ │ │ • FB Message: 5 times  │ │
│ │    Manual    │ │                                 │ │ • Orders: 3 completed  │ │
│ │    Mode      │ │ [Send] [Edit] [Use Template]    │ │ • Last active: 2h ago  │ │
│ │    15m ago   │ │                                 │ │                         │ │
│ │              │ │ ───────────────────────────────  │ │ [Create Order]          │ │
│ │ [+ New Chat] │ │                                 │ │ [View Full History]     │ │
│ │              │ │ Quick Reply Templates:          │ │ [Add Note]              │ │
│ │              │ │ • "Price is ৳X"                 │ │                         │ │
│ │              │ │ • "Available, order now"        │ │                         │ │
│ │              │ │ • "Delivery in Dhaka ৳60"      │ │                         │ │
│ └──────────────┘ └─────────────────────────────────┘ └─────────────────────────┘ │
└─────────────────────────────────────────────────────────────────────────────────┘
```

## 3. Mobile Dashboard View (375px)

```
┌───────────────────────────────────┐
│ ☰  Dashboard    🟢 AI   👤        │
├───────────────────────────────────┤
│ Home > Dashboard                  │
├───────────────────────────────────┤
│                                   │
│ ┌─────────────────────────────────┐ │
│ │     📱 SOCIAL COMMERCE          │ │
│ │                                 │ │
│ │ 💬 12 New Messages              │ │
│ │ 🤖 AI: 34 Auto-Replies         │ │
│ │ 📊 85% Response Rate            │ │
│ │                                 │ │
│ │         [View Inbox]            │ │
│ └─────────────────────────────────┘ │
│                                   │
│ ┌─────────────────────────────────┐ │
│ │     📦 ORDER MANAGEMENT         │ │
│ │                                 │ │
│ │ 📋 23 Pending Orders            │ │
│ │ 🚚 15 Ready to Ship             │ │
│ │ ⚠️  3 Urgent Orders             │ │
│ │                                 │ │
│ │       [Process Orders]          │ │
│ └─────────────────────────────────┘ │
│                                   │
│ ┌─────────────────────────────────┐ │
│ │    📦 INVENTORY MANAGEMENT      │ │
│ │                                 │ │
│ │ 📊 1,247 Total Products         │ │
│ │ ⚠️  23 Low Stock Items          │ │
│ │ 📥 5 Pending Restocks           │ │
│ │                                 │ │
│ │        [Manage Stock]           │ │
│ └─────────────────────────────────┘ │
│                                   │
│ ┌─────────────────────────────────┐ │
│ │    📊 ANALYTICS & REPORTS       │ │
│ │                                 │ │
│ │ 💰 ৳85,340 Today's Sales        │ │
│ │ 📈 +12% vs Yesterday            │ │
│ │ 👥 167 Active Customers         │ │
│ │                                 │ │
│ │        [View Reports]           │ │
│ └─────────────────────────────────┘ │
│                                   │
├───────────────────────────────────┤
│        [🚀] Floating Action       │
│                                   │
└───────────────────────────────────┘
```

## 4. AI Status Indicators & Modes

```
AI Status Indicator Examples:
┌─────────────────────────────────────────────────────────────┐
│                                                             │
│ 🟢 AI Active         🟡 AI Suggesting      🔴 Manual Control│
│ "Auto-responding     "Human review         "Agent handling  │
│  to customers"        required"            conversation"    │
│                                                             │
│ ┌─────────────────┐  ┌─────────────────┐  ┌───────────────┐ │
│ │ AUTO MODE       │  │ HYBRID MODE     │  │ MANUAL MODE   │ │
│ │                 │  │                 │  │               │ │
│ │ 🤖 AI handles   │  │ 🤖 AI suggests │  │ 👤 Human only │ │
│ │ all messages    │  │ 👤 Human sends │  │ AI disabled   │ │
│ │ instantly       │  │ final response  │  │ for this chat │ │
│ │                 │  │                 │  │               │ │
│ │ [Switch Manual] │  │ [Go Full Auto]  │  │ [Enable AI]   │ │
│ └─────────────────┘  └─────────────────┘  └───────────────┘ │
└─────────────────────────────────────────────────────────────┘
```

## 5. Order Management Hub Detail View

```
┌─────────────────────────────────────────────────────────────────────────────────┐
│ [LOGO]    Home > Order Management                   🟢 AI Active    [Profile ▼]  │
├─────────────────────────────────────────────────────────────────────────────────┤
│ [+ Manual Order] [Bulk Actions] [Export] [Filter ▼] [Search: Order #...]        │
├─────────────────────────────────────────────────────────────────────────────────┤
│                                                                                 │
│ ┌─────────────────────────────────────┐ ┌───────────────────────────────────────┐ │
│ │           ORDER QUEUE               │ │           ORDER DETAILS               │ │
│ │                                     │ │                                       │ │
│ │ [🔥 Urgent] [📋 Pending] [🚚 Ship]  │ │ Order #ORD-2024-001234               │ │
│ │                                     │ │ ───────────────────────────────────   │ │
│ │ 🔥 ORD-001234  Ahmad Rahman         │ │ 👤 Customer: Ahmad Rahman             │ │
│ │    ৳2,400 • COD • Dhaka            │ │ 📱 Phone: +880171234567              │ │
│ │    📱 From: Facebook                │ │ 📍 Address: Dhanmondi, Dhaka         │ │
│ │    ⏰ 2 hours ago                   │ │                                       │ │
│ │                                     │ │ 🛒 Items:                            │ │
│ │ 📋 ORD-001235  Sarah Ahmed          │ │ • Red T-Shirt (L) × 2 = ৳1,600      │ │
│ │    ৳1,800 • bKash • Chittagong     │ │ • Blue Jeans (32) × 1 = ৳800         │ │
│ │    📱 From: WhatsApp                │ │                                       │ │
│ │    ⏰ 3 hours ago                   │ │ 💰 Subtotal: ৳2,400                  │ │
│ │                                     │ │ 🚚 Delivery: ৳60 (Dhaka)            │ │
│ │ 🚚 ORD-001236  Karim Hassan         │ │ 💳 Total: ৳2,460                     │ │
│ │    ৳3,200 • Card • Sylhet          │ │ 💵 Payment: COD                      │ │
│ │    🛒 From: Website                 │ │                                       │ │
│ │    ⏰ 5 hours ago                   │ │ 📊 Status: Pending Confirmation      │ │
│ │                                     │ │                                       │ │
│ │ [Load More...]                      │ │ [✅ Confirm] [📞 Call] [📝 Note]     │ │
│ │                                     │ │ [🚚 Ship] [❌ Cancel] [📧 Email]     │ │
│ └─────────────────────────────────────┘ └───────────────────────────────────────┘ │
│                                                                                 │
├─────────────────────────────────────────────────────────────────────────────────┤
│ Quick Actions: [Mark as Urgent] [Bulk Confirm] [Print Labels] [Export CSV]     │
└─────────────────────────────────────────────────────────────────────────────────┘
```

## 6. Breadcrumb Navigation Examples

```
Navigation Breadcrumb Patterns:
┌─────────────────────────────────────────────────────────────────────────────────┐
│                                                                                 │
│ Dashboard View:                                                                 │
│ Home > Dashboard                                                                │
│                                                                                 │
│ Social Commerce Hub:                                                            │
│ Home > Social Commerce > Facebook Inbox                                        │
│                                                                                 │
│ Specific Conversation:                                                          │
│ Home > Social Commerce > Facebook Inbox > Ahmad Rahman                         │
│                                                                                 │
│ Order Management:                                                               │
│ Home > Order Management > Pending Orders                                       │
│                                                                                 │
│ Specific Order:                                                                 │
│ Home > Order Management > Order Details > #ORD-001234                          │
│                                                                                 │
│ Inventory Management:                                                           │
│ Home > Inventory > Stock Management > Low Stock Items                          │
│                                                                                 │
│ Product Management:                                                             │
│ Home > Inventory > Products > Edit Product > "Red T-Shirt"                     │
│                                                                                 │
│ Analytics:                                                                      │
│ Home > Analytics > Sales Reports > Daily Sales                                 │
│                                                                                 │
└─────────────────────────────────────────────────────────────────────────────────┘
```

## Key Wireframe Notes:

### Hub-Based Design Features:
1. **Color-coded hubs** for quick visual identification
2. **Real-time metrics** displayed on each hub tile
3. **Quick action buttons** prominently placed
4. **Role-based widgets** appear based on user permissions

### Social Commerce Integration:
1. **Platform prioritization** (Facebook > WhatsApp > Instagram)
2. **AI status clearly visible** with traffic light system
3. **Unified inbox** with conversation threading
4. **Customer profile** sidebar with interaction history

### Mobile Adaptation:
1. **Single column stack** for hub tiles
2. **Swipe navigation** between hubs
3. **Floating action button** for quick access
4. **Touch-optimized** interface elements

### AI Integration:
1. **Clear mode indicators** (Auto/Hybrid/Manual)
2. **Suggestion overlay** for human review
3. **One-click mode switching**
4. **Configuration access** via gear icon

These wireframes demonstrate the key concepts from the UIDD in visual form, showing how the hub-based dashboard, AI integration, and responsive design work together.