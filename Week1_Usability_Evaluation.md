# Week 1 Usability Evaluation Report

| | |
|---|---|
| **Student** | Maria Zafar |
| **Course** | Human-Computer Interaction (HCI) |
| **Method** | Heuristic evaluation using Nielsen's 10 Usability Heuristics |
| **Design 1** | [Food Delivery App UI Design](https://www.figma.com/community/file/1162667537030037428) by XongoLab Technologies |
| **Design 2** | [Dreams LMS: Free Figma UI Kit for Learning Management Systems](https://www.figma.com/community/file/1542911527930004020) |

---

## 1. Introduction
Food delivery apps and student/learning portals are used by many people every day, so clear and easy interaction is very important. The aim of this report is to identify usability flaws in two existing designs, link each flaw to a usability heuristic, rate its severity and suggest a fix.

## 2. Method
1. I opened each design from the Figma Community and reviewed its screens.
2. I considered typical user tasks and checked whether the interface supports them.
3. I compared each screen against Nielsen's 10 heuristics (visibility of system status, match with real world, user control and freedom, consistency and standards, error prevention, recognition rather than recall, flexibility and efficiency, aesthetic and minimalist design, error recovery, help and documentation).
4. I recorded each problem with its severity and a suggested fix.

**Severity scale:** 1 = Cosmetic, 2 = Minor, 3 = Major, 4 = Critical

---

## 3. Design 1: Food Delivery App UI Design (Mobile App)

**Type:** Mobile app (food ordering)
**Screens evaluated:** Explore, Restaurant menu, Restaurant details, Map/location, Cart/Checkout
**Tasks considered:**
1. Find a restaurant using the Explore screen and search
2. Open a restaurant menu and add an item to the cart
3. Check restaurant details (cuisine, opening hours)
4. Choose a delivery location and place an order

### Usability Flaws

| # | Screen | Problem | Heuristic violated | Severity (1-4) | Suggested fix |
|---|--------|---------|--------------------|----------------|---------------|
| 1 | Explore | Search bar text is very light grey and hard to see | Visibility / Aesthetic design | 3 | Use darker text and a clear border |
| 2 | Menu list | "Add to Cart" is a light outline button and does not look clickable | Recognition rather than recall | 3 | Use a solid orange button |
| 3 | Menu | An Indian restaurant shows "Sichuan Cuisine" and "Tea-Smoked Duck" | Match between system and real world / Consistency | 3 | Keep cuisine tabs and dishes consistent with the restaurant |
| 4 | Restaurant details | Opening hours and cuisine tags are small and light grey; tags are mixed (Guadeloupe, Dominican, Pakistani) | Aesthetic design / Consistency | 2 | Increase font size and contrast; show relevant tags only |
| 5 | Restaurant header | Name and rating sit on a busy food photo, reducing readability | Visibility | 2 | Add a dark overlay behind the text |
| 6 | Cart / Checkout | Price breakdown and promo code toggle are small and unclear; quantity editing is hard to find | Visibility / User control and freedom | 3 | Make the total bold; add clear +/- quantity controls |
| 7 | Checkout | No review or confirmation step before "Place your Order"; no clear back/cancel option | Error prevention / User control and freedom | 3 | Add an order review step and a visible back button |
| 8 | Map | "Explore Restaurants" button covers part of the map and address card; address text is very small | Visibility / Error prevention | 2 | Enlarge the address card; rename the button "Confirm Location" |

---

## 4. Design 2: Dreams LMS (Learning Management System, Web)

**Type:** Web learning portal (student/instructor dashboards)
**Screens evaluated:** Landing/home page (hero section) and Instructor Dashboard
**Tasks considered:**
1. Search for a course using category and search field
2. Find main navigation options
3. Read dashboard statistics (courses, students, earnings)
4. Understand the earnings chart and switch between dashboards

### Usability Flaws

| # | Screen | Problem | Heuristic violated | Severity (1-4) | Suggested fix |
|---|--------|---------|--------------------|----------------|---------------|
| 1 | Landing page (search) | The search field has a very faint placeholder and tiny "Select category" text; the red search button shows only an arrow with no label | Visibility / Recognition rather than recall | 2 | Use darker placeholder text, a larger font and a "Search" label on the button |
| 2 | Landing page (stats) | Statistics such as online courses, certified courses and tutors are tiny and low contrast on the dark blue background | Visibility / Aesthetic design | 2 | Increase size and use white or bright text |
| 3 | Top navigation | Menu items (Home, Courses, Dashboard, Pages, Blogs) are small and dim against the dark header | Visibility / Recognition rather than recall | 2 | Increase font size and contrast; highlight the active page |
| 4 | Dashboard (stat cards) | Card labels are tiny and light grey; the numbers have no explanation, so they are hard to scan | Aesthetic and minimalist design | 2 | Use larger labels, bold numbers and short descriptions |
| 5 | Dashboard (earnings chart) | The "Earnings by Year" bar chart has no clearly visible axis values, legend or labels on the bars | Visibility of system status / Recognition rather than recall | 3 | Add axis labels, values and a legend |
| 6 | Dashboard (banner) | An instructor dashboard shows both "Add New Course" and "Student Dashboard" buttons with similar styling, so the main action and the user role are unclear | Consistency and standards / Recognition rather than recall | 3 | Make one primary (filled) and one secondary (outline) button; label the role clearly |
| 7 | Sidebar (Main Menu) | Menu items are small and densely packed, making navigation harder | Recognition rather than recall | 2 | Increase spacing and font size; group related items |
| 8 | Whole kit | The landing page uses a dark theme while the dashboard is light, which makes the style inconsistent | Consistency and standards | 2 | Use one consistent colour scheme and component style |

---

## 5. Summary and Comparison

| Design | Type | Flaws found | Major (3) | Minor (2) |
|--------|------|-------------|-----------|-----------|
| Food Delivery App UI | Mobile app | 8 | 5 | 3 |
| Dreams LMS Dashboard | Web portal | 8 | 2 | 6 |

**Heuristics most affected**
- **Visibility:** low contrast and small text appear in both designs.
- **Recognition rather than recall:** weak button affordance (Design 1) and unlabeled charts and icons (Design 2).
- **Consistency and standards:** mismatched content (Design 1) and mixed themes and roles (Design 2).
- **User control and error prevention:** missing confirmation and back options in checkout (Design 1).

**Comparison:** The mobile food app has more major problems around checkout and button clarity, while the LMS web design mainly suffers from small, low-contrast text and unlabeled data.

## 6. Recommendations
1. Improve text contrast and font sizes on all screens.
2. Use clear, solid primary buttons and distinct secondary buttons.
3. Keep content, colours and components consistent.
4. Add confirmation and back options for important actions such as placing an order.
5. Label charts, icons and key numbers clearly.

## 7. Conclusion
Both designs look modern and attractive, but they share common usability problems such as low contrast, small text and unclear actions. Heuristic evaluation helped me find these problems early in the HCI life cycle. The suggested fixes will be used for redesign and iteration in the coming weeks.

## 8. References
- Nielsen, J. *10 Usability Heuristics for User Interface Design.* Nielsen Norman Group.
- *Food Delivery App UI Design*, XongoLab Technologies, Figma Community: https://www.figma.com/community/file/1162667537030037428
- *Dreams LMS: Free Figma UI Kit for Learning Management Systems*, Figma Community: https://www.figma.com/community/file/1542911527930004020
