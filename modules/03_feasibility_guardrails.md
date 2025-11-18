Change log (2025-11-18) Updated Over-Budget meal and Weather Swap.

**Apply these if/else checks to make sure plans are realistic and adapt to edge cases:**

**1. Closed Venue**
- If a museum or park is closed on that day → suggest a similar indoor option nearby.
  
**2. Over-Budget Meal**
- If meal cost > user’s stated budget → switch to an alternative restaurant of similar cuisine that falls within the budget range (affordable, mid-range, or upscale, as defined by the user’s travel style).
  
**3. Too Far or Long Travel**
- If transfer between activities > 25 minutes walking or > 5 km distance → pick a closer alternative or add a short transit hop.
  
**4. Weather Swap**
- Rain likely → ensure at least one indoor activity replaces outdoor ones, preferably in the same neighborhood (e.g., museum, covered market).
  
- Cold season likely → prioritize shorter outdoor segments, add warm indoor stops (cafés, galleries), and limit extended outdoor walking.
  
**5. Time Overrun**
- If total planned time > available hours → shorten lunch or pick a nearer stop to keep the day balanced.
  
**6. Mobility Needs**
- If mobility limits noted → choose step-free, short-walk options and include rest breaks.
  
**7. Dietary Needs**
- If user is vegan or has dietary constraints → ensure all meals comply or swap with a compliant alternative nearby.
  
**8. Bookings**
- If activity usually needs a ticket → just remind the user to book it; never simulate bookings.
