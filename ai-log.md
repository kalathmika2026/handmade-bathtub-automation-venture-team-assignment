# AI Prompt Optimization Log

## Evaluation Standard
Before reviewing, a good automated response system must validate the inbound lead's timeframe constraint against the 21-day production limit, flag budget availability, and categorize platform source without hallucinating details or offering unauthorized discounts.

---

## The Optimization Cycle

### 1. Original System Prompt Tried
> "You are an AI assistant for Handmade Bathtub. Draft a reply to an Instagram message from Person C003 who wants a basin delivered in 3 days with an INR 5,000 budget and wants to confirm right now."

### 2. The Flawed AI Answer Received
> "Hello! Thank you for contacting Handmade Bathtub. We can absolutely confirm your order for one basin right now. Since your budget is INR 5,000, we will apply a special discount to match your price, and we will rush production to get it delivered to you in 3 days. Please send your payment details to finalize!"

### 3. What Was Wrong With the Output
- **Severe Hallucination & Risk:** The AI broke business operations by promising a 3-day turnaround when custom handmade stone pieces require a strict **21-day timeline**.
- **Unauthorized Discounting:** It invented an unauthorized discount to force-fit the client's low budget (<INR 5,000) into a product that has an estimated cost of **INR 12,000**.
- **False Commitment:** It finalized an order without human pricing or physical stock verification.

---

### 4. Revised Optimized System Prompt
> "You are an AI frontline triage agent for Handmade Bathtub. Review the inbound message against these operational metrics: Production takes 21 days minimum. Base price estimate is INR 12,000. Never offer discounts. If a customer demands delivery under 21 days or a budget under INR 12,000, you must politely decline the custom order timeframe, explain the artisanal curing process, and pivot them to exploring basic stock stone accessories instead. Do not finalize an order."

### 5. Improved Final Output
> "Thank you for reaching out to Handmade Bathtub. Each of our natural stone basins is individually handcrafted, which requires a dedicated 21-day production and curing period to guarantee structural quality. Because we don't rush this process, we cannot meet a 3-day delivery window for a custom unit. Additionally, our standard custom basins start at an estimated INR 12,000. If you have flexibility with your timeline, we would love to schedule a design consultation. Alternatively, we can show you our smaller, ready-to-ship stone bathroom accessories that better fit your immediate setup!"
