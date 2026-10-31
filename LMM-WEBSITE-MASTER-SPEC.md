# LMM Website Master Specification
Version: 1.0
Status: Source-aligned build specification
Project: LMM Pet Memorial Art
Brand: LMM — LOVE • MEMORIES • MEMENTO
Slogan: 从爱开始，一生陪伴 / Begin With Love. Stay Forever.

## Build principles
- This is a new independent LMM website. Do not treat V1/V2/V2.2/V2.3/V2.4 local starter folders as approved finished websites; they are reference material only and were reported by the owner as incorrect.
- Chinese is the primary language; English is available as a language version/toggle. Keep navigation clean and hierarchical.
- Do not flatten all content onto the homepage. Each top-level directory opens its own page; each product category opens its own product page.
- Never label SHOP as “7大产品系列”; the seven category names are editable catalogue entries.
- Use only owner-approved LMM product photographs and original designer artwork. Do not generate, redraw, recolour, reshape or replace product photographs. The owner must be able to replace homepage images through admin.
- Customer-facing navigation must not expose Admin or Partner Portal controls.
- Clearly distinguish a front-end prototype from production backend features. Authentication, private uploads, cloud storage, order processing, email verification, payment proof storage, receipts, exports and role-based access require secure backend services.

## 01 HOME｜首页
- Homepage hero image: owner-designated image 8 from the 2026-10-30 conversation; use the exact original asset when recovered. Do not substitute.
- Hero text (Chinese):
  “爱引远方虹桥路，盅守人间归处家。”
  “每一段生命故事，都值得拥有独一无二的纪念。”
  “LMM 以 Resin 定制宠物陪伴纪念艺术，将最珍贵的毛孩子回忆，化作永恒的陪伴。”
  “Begin With Love. Stay Forever.”
- Hero text (English):
  “Beyond the Rainbow Bridge, Love Finds Its Way Home.”
  “Every life leaves a story worth remembering. Every bond deserves a tribute as unique as the love it holds.”
  “LMM creates bespoke Pet Companion Memorial Art through the artistry of resin, transforming precious memories into timeless keepsakes.”
  “Begin With Love. Stay Forever.”
- Include Peaceful Home concept and an immediately visible actual product showcase using owner-designated image 1 / approved product images, with clear “Explore Memorial Art” / order entry.
- Include selected product and brand content entry points. Homepage image slots must be editable in Admin.
- Include the “从爱开始到归宿” narrative section.

## 02 SHOP｜产品目录
Show category cover tiles only on the directory page. Clicking a tile opens its independent product page.
1. Keepsake Collection｜成长珍藏
2. Memory Collection｜生活记忆
3. Pet Memorial Figurines｜宠物纪念摆件
4. Forever Collection｜永恒珍藏
5. Peaceful Home｜小屋子
6. Miniature Scene Accessories｜场景配件
7. Dreamcatcher Memorial Pendant｜捕梦网纪念吊坠
Each independent page may contain: introduction, original product photographs, styles, specifications, prices, product-specific FAQ, customisation process and purchase/contact entry. Category visibility and availability must be configurable; Dreamcatcher Memorial Pendant is currently not open for sale.

## 03 MY ACCOUNT｜会员中心
- My Account｜我的账户: profile, login and security.
- Shopping Cart｜购物车.
- Checkout｜确认订单: customer, selected pet and customisation details.
- Payment｜付款: bank details and unique payment reference per order.
- Upload Payment Proof｜上传付款证明.
- My Pets｜我的宠物: multiple independent pet profiles under one customer.
- My Orders｜我的订单: payment and production status.
- My Creations｜我的定制作品: customer's commissioned work record; public sharing must not expose custom prices.
- My Memories｜我的回忆: pet growth and life memories.
- LMM Rewards｜爪爪积分: reserved but disabled until the programme is officially launched.
- One Customer Account can own multiple Pet Profiles. Pet Member status is a separate per-pet qualification, not a login account. Pet status (Living/Memorial) is set by the owner, never inferred from an order.

## 04 OUR STORY｜认识 LMM
- LMM Concept｜LMM 品牌概念
- Brand Voice｜品牌声音
- About LMM｜关于 LMM
- Portfolio Story｜作品故事
- Founder Story｜创办人故事
- Use the original system-designer artwork 2–7 in their intended positions; retrieve and map exact original files before publishing. Do not recreate these graphics.

## 05 Q&A｜常见问题与网站政策
- FAQ｜常见问题, organised by product series, custom work, membership/account, ordering/payment.
- Custom Process｜客制流程.
- Ordering & Payment Guide｜订购与付款指南.
- Terms & Conditions｜条款与细则.
- Privacy Policy｜隐私政策.
- About Resin｜关于滴胶｜时间与回忆的载体.
- Keep general FAQ separate from Customer Care. Do not put policy content under Contact Us.

## 06 CUSTOMER CARE｜联系客服
- WhatsApp direct contact link only. No FAQ, terms or other policy pages in this section.

## 07 A SPACE OF LOVE｜爱的记忆空间
Public-facing independent feature landing page, visible to all visitors.
- A Space of Love｜public introduction and showcase.
- Our Memorial World｜宠物纪念世界.
- Public Memorials｜公开纪念空间.
- Send Flowers｜送花与纪念互动.
- My Pet Memorials｜我的电子纪念墓碑: member-only create/manage.
  - Pet profile
  - Life Timeline｜生命记录
  - My Story｜我的故事
  - Memory Home｜记忆之家
  - Private / Public visibility
  - Edit and manage memorial page
- The visual world should be warm, lively and welcoming, with multiple pet types; not lonely or gloomy.
- Each memorial allows only 1–2 owner-selected photos as initially specified. Privacy controls belong to the owner. Public visitors may view public memorials and send flowers subject to permissions.

## Footer
Show LMM Instagram, Facebook and Xiaohongshu links. Use only confirmed official URLs; do not invent social handles.

## Admin Dashboard
Separate protected admin login; never expose admin controls in public navigation.
- Manage homepage hero and all image slots (replace/upload, preview, alt text, enable/disable).
- Manage navigation, page sections and content blocks.
- Manage catalogue categories, product details, photos, specifications, pricing, availability and per-product FAQ.
- Each product page has configurable content blocks; do not force every product to use every field.
- Manage customer profiles, pet profiles, pet photos and permissions.
- Manage orders, custom requirements, payment proof, deposits/balances, production status and delivery.
- Generate customer receipts; export relevant business records to Excel; authorised photo/file download for production/backup.
- Editable homepage announcement/promotion panel with enable/disable and schedule.
- Admin can manage Agents and Workshops, assign partner IDs, agreements, orders/tasks, commission/settlement rules and statuses.

### Partner Agreement Management｜合作伙伴协议管理

LMM Admin must include a dedicated Partner Agreement Management module.

**1. Partner Agreements**
- Agent Partners and Workshop Partners must use separate partnership agreements.
- LMM Admin can upload, create, and update agreement documents.
- Every agreement must record an agreement version number, effective date, and applicable partner type.
- Each partner must be presented with the agreement applicable to their partner type and must review and formally accept it.

**2. Partner Review and Activation**
1. LMM Admin creates the partner profile.
2. Admin selects the partner type: Agent or Workshop Partner.
3. The system issues the corresponding partnership terms and agreement.
4. The partner reviews and accepts the applicable agreement.
5. LMM Admin reviews the partner application and, after approval, sets the partnership status to **Active**.
6. Partner Portal login access is enabled only after Admin approval and activation. Agreement acceptance alone must not automatically grant portal access.

**3. Agreement Records**
For each partner agreement, the system must retain:
- Partner ID
- Partner Type
- Agreement Version
- Acceptance Date
- Effective Date
- Agreement Status
- Partnership Termination Date (if applicable)

**4. Access Control**
- Agent Partners may view only their own referred customers, attributed orders, and commission records.
- Workshop Partners may view only production tasks assigned to them and the information necessary to complete those tasks.
- Partners must not access other partners' records or customers' private Memories.
- LMM Admin has full authorised access to view and manage all partner agreements and their records.
- Agreement status, partner activation status, and Partner Portal access status must be tracked separately so that a pending, expired, suspended, or terminated agreement cannot leave portal access active unintentionally.

## Hidden Agreement & Consent Confirmation｜隐藏式协议确认机制

All legal terms, agreements, and consent documents must be presented through a **hidden, system-triggered modal or secure in-flow panel**. They must not appear as permanent public navigation pages or be openly displayed unless the user reaches the relevant action. The system displays only the document applicable to that user's action and role.

**Required confirmation checkpoints**
1. **Customer registration / becoming an LMM member:** show the Membership Terms & Conditions and Privacy Policy & Personal Data Protection Notice. The user must actively tick an initially unchecked acceptance box before registration can be completed.
2. **Order and payment confirmation:** show the applicable Purchase Terms & Conditions and relevant product-specific terms before the customer submits the order or payment confirmation. The customer must actively accept before proceeding. This consent is separate from membership registration consent.
3. **Agent activation:** show the Agent Partnership Agreement. The Agent must review and accept it before the Admin approval and activation process can continue.
4. **Workshop Partner activation:** show the Workshop Partner Agreement. The Workshop Partner must review and accept it before the Admin approval and activation process can continue.

**Interaction and record requirements**
- The agreement panel is triggered only at the relevant registration, checkout/payment, or partner onboarding step; it is not a public-facing page in the main website menu.
- The complete applicable document must be readable in the panel, with access to the full text or document.
- Acceptance must be an explicit user action. The checkbox must never be pre-selected.
- If the user does not accept, the relevant action must be blocked: no membership registration, order/payment confirmation, or partner agreement submission.
- Store the user/customer/partner ID, role or partner type, document name, document version, acceptance timestamp, and the related registration/order/partner record.
- Admin must be able to retrieve the acceptance history for audit and dispute handling.
- If a material document revision requires renewed consent, prompt the affected users to accept the new version before they continue the relevant protected action.
- Partner agreement acceptance does not itself activate a partner account; LMM Admin approval and Active status are still required before Partner Portal access is granted.

## Roles and permissions
- Customer: own account, own pets, own orders and own private memories.
- Pet Member: per-pet membership status/entitlement, not a separate login.
- Agent: only own referrals, attributed orders and commission records.
- Workshop Partner: only assigned production tasks, necessary photos/requirements and own settlement records.
- Admin: full authorised administration.
- Partner Portal is separate from customer navigation. Agent and Workshop are distinct roles; neither may view other partners' records or customer private memories without explicit authorisation.

## Orders and payment
- Initial payment method: manual online bank transfer; customer uploads proof; Admin verifies manually. No payment gateway or TNG integration until separately enabled.
- Generate a unique payment reference for each order.
- Track order statuses: Pending Payment, Payment Verification, Paid, In Production, Ready, Shipped, Completed, Cancelled.
- Track payment statuses separately: Unpaid, Partially Paid, Pending Verification, Paid, Refunded.
- Preserve product-specific payment rules; do not impose one generic deposit rule across all categories.
- Custom price lines must be possible for individual orders without exposing custom prices publicly.

## Technical and safety requirements
- Static GitHub Pages preview is not a production commerce or member system.
- Real member login, password reset, private photo storage, payment proof uploads, receipts, Excel exports, order workflows and role permissions require backend, database, secure storage and access control.
- Six-digit numeric passwords, if retained, must be securely hashed, rate-limited and reset via time-limited email verification; never store plaintext passwords.
- Protect customer/pet photos and private memorial content; public display requires owner permission.
- Do not promise resin is permanent, waterproof forever, or that embedded materials will never change. Use the approved conservative material-care language.
