# Heuristic Evaluation: Amazon

## Interface Overview

**Interface Name:** :contentReference[oaicite:0]{index=0}  
**URL:** :contentReference[oaicite:1]{index=1}  

**Intended Users:**  
General consumers, including online shoppers looking for products ranging from electronics to household goods.

**Primary Purpose:**  
To allow users to search for products, compare options, read reviews, and complete online purchases.

---

## Heuristic Evaluation Results

### 1. Visibility of System Status

**Issue:**  
During checkout, Amazon sometimes updates shipping options or prices after a user selects a delivery speed, without clearly highlighting what changed.

**Why this is a problem:**  
Users may not immediately notice that the total cost has changed, increasing cognitive load and reducing transparency.

**User impact:**  
Users may feel confused or lose trust if final prices differ from expected totals.

**Proposed improvement:**  
Highlight any price or shipping changes in a bold, clearly labeled update box that appears immediately after changes are made.

---

### 2. Match Between System and Real World

**Issue:**  
Some product pages use technical jargon such as “renewed,” “fulfilled by Amazon,” or “Prime eligible” without clear explanations.

**Why this is a problem:**  
New users may not understand these terms, reducing learnability.

**User impact:**  
Users may misinterpret product conditions or benefits and make poor purchasing decisions.

**Proposed improvement:**  
Add plain-language tooltips or short explanations next to unfamiliar terms.

---

### 3. User Control and Freedom

**Issue:**  
When navigating product pages, users may lose previously applied filters or search context when returning to results.

**Why this is a problem:**  
This increases cognitive load and reduces browsing efficiency.

**User impact:**  
Users may become frustrated and abandon product searches due to repetitive filtering.

**Proposed improvement:**  
Preserve filters and search state when users return to results pages.

---

### 4. Consistency and Standards

**Issue:**  
Product pages from third-party sellers sometimes vary in layout, image quality, and information structure.

**Why this is a problem:**  
Inconsistent presentation increases cognitive load because users must reinterpret layouts repeatedly.

**User impact:**  
Users may miss important information or struggle to compare products accurately.

**Proposed improvement:**  
Enforce stricter layout guidelines for product listings or provide standardized templates for sellers.

---

### 5. Error Prevention

**Issue:**  
The “1-Click Ordering” feature allows users to complete purchases with minimal confirmation.

**Why this is a problem:**  
It increases the risk of accidental purchases, especially for new or distracted users.

**User impact:**  
Users may feel frustration or regret after unintended orders, reducing trust in the system.

**Proposed improvement:**  
Require a confirmation step before finalizing orders or make 1-Click Ordering opt-in rather than default.

---

## Reflection

**Most useful heuristic:**  
Error Prevention was the most useful heuristic because it highlights how small interface decisions can have significant consequences for user trust and financial outcomes.

**Limitation of heuristic evaluation:**  
A key limitation is the lack of real user input. Heuristic evaluation cannot fully capture how actual users behave, where they struggle in practice, or how emotional responses influence usability.
