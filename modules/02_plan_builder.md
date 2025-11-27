> **Change Log (2025-11-26):**  
> - Added concrete distance thresholds (≤1km/15min morning, ≤2km/20min midday)  
> - Required opening hours verification before selection  
> - Included one alternate per time slot for fallback flexibility  
> - Implemented per-day budget tracking with lower-cost swap logic  
> - Added indoor/outdoor tagging with weather-aware substitution rules

---

## Candidate Activities

Each activity should include:
- **Type** (e.g., attraction, restaurant, park)  
- **Estimated duration**  
- **Cost range**  
- **Distance/time** from lodging or prior activity  
- **Opening hours** (must be verified before selection)  
- **Indoor/Outdoor tag** (for weather-aware substitution)

For each time slot, also prepare **one alternate activity** to allow fallback flexibility.

---

## Day-Building Loop

### Morning activity (near lodging)
- Select an activity within **≤1 km** or **≤15 minutes** walk from lodging.  
- Verify opening hours for the morning window.  
- Include one alternate option.

### Midday activity (close by)
- Choose an activity within **≤2 km** or **≤20 minutes** transit from the morning location.  
- Verify opening hours for midday.  
- Include one alternate option.

### Afternoon activity (different theme)
- Pick an activity with a theme distinct from morning/midday.  
- Verify opening hours for afternoon.  
- Include one alternate option.  
- If outdoor, prepare an indoor substitute for bad weather.

### Evening restaurant or optional event
- Select dining or an event near the afternoon location.  
- Verify opening hours or reservation needs.  
- Include one alternate option.  
- Respect dietary preferences and weather conditions.

---

## Budget Tracking
- Track cumulative daily costs across all activities.  
- If the total exceeds the daily budget target, swap in lower-cost alternates.

---

## Weather Handling
- Use **Indoor/Outdoor** tags to adapt the plan.  
- On adverse weather days, substitute outdoor activities with indoor alternates.

---

## Output

For each day, provide:
- Morning, Midday, Afternoon, Evening activity (with alternates)  
- Type, duration, cost range, distance/time, opening hours, indoor/outdoor tag  

**Daily summary**:
- Total estimated cost  
- Total time  
- Weather notes  
- Fallback options
