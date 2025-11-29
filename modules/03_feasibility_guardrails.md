### **Module 3 — Feasibility & Guardrails**

Apply these **if/else** checks to make sure plans are realistic and adapt to edge cases:

1. **Closed Venue**
   
   - If a museum, park, or attraction is closed on the planned day → replace it with a similar nearby option. Prefer indoor substitutes if the weather is poor.
   - If none is available → replace with an indoor option that fits the same time‑of‑day slot.

2. **Budget Constraints**
   
   - If a meal or attraction cost exceeds the user’s budget → switch to a cheaper alternative of a similar theme or cuisine.
   - If the budget is limited → prioritize free or low‑cost options (public parks, markets, street food).

3. **Travel Distance & Time**
   
   - If transfer between activities > 25 minutes walking or > 5 km → pick a closer alternative or add a short transit hop (bus, metro, taxi).
   - Always adjust timing buffers to keep the day realistic.

4. **Weather Swap**
   
   - If rain or cold season is likely → guarantee at least two indoor backups per day.
   - If severe weather is forecast → convert outdoor-heavy plans to indoor clusters (e.g., museums, cafés, galleries, board game cafés).

5. **Time Overrun**
   
   - If total planned time exceeds available hours → shorten meals, reduce dwell times, or choose nearer stops to fit the day.

6. **Mobility Needs**
   
   - If mobility limits are noted → prioritize step‑free venues, short walks, accessible transit, and include rest breaks.
   - If no accessible option nearby → swap to a similar theme within accessible reach.

7. **Dietary Needs**
   
   - If user is vegan or has dietary constraints → ensure all meals are compliant.
   - If no compliant restaurant is nearby → expand search modestly or use a compliant grocery/market option.
   - Avoid prescriptive “bring your own” advice.

8. **Bookings**
   
   - If activity usually needs a ticket or reservation → remind the user to book it under Quick Checks only.
   - If tickets are sold out → suggest a similar alternative that doesn’t require booking.

9. **Short Walks Only**

- If user requests short walks only → limit transfers to ≤15 minutes walking or within 1 km.
- Add transit when longer distances are unavoidable.

10. **Missing or Invalid Data**

- If dates or venue hours are unknown → include indoor backups and add a Quick Check reminder.
- If no suitable activities found → surface a minimal viable day (one highlight + meal) and invite refinements.
   
11. **Missing Inputs**
   - If budget or dates are missing/invalid → assume mid‑range costs and typical opening hours; flag under Quick Checks for user confirmation.
  
12. **No Suitable Activity Found**
    - If no activity meets constraints (distance, budget, accessibility, weather) → select the nearest feasible alternative and note one backup. Avoid leaving time slots empty.

13. **Closure Patterns**
    - Apply common closure rules (e.g., museums closed Mondays) when dates are known; include an indoor alternative nearby.
