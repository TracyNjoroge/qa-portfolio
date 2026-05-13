## Test Cases for Home section on https://tracynjoroge.vercel.app/

![Portfolio Hero page screenshot](./images/hero.png)

## Summary

| Test ID | Title | Type | Status |
|---------|-------|------|--------|
| TCH001 | Verify Static Elements| Positive |  |
| TCH002 | Verify Animated text starts on page load| Positive |  |
| TCH003 | Verify Resume button| Positive |  |

---

**Test ID:** TCH001

**Test Title:** Verify Hero section static elements display correctly

**Description:** Verify Hero section static elements display correctly on page load

**Preconditions:**
- Website https://tracynjoroge.vercel.app/ is open in a desktop browser
- Internet connection is available
- User is currently viewing the Hero section

**Steps:**
1. Check the subheading "Hey there, I'm" is visible
2. Check the heading "Tracy Njoroge" is visible
3. Check the description paragraph is fully visible

**Expected Result:** 
- Subheading "Hey there, I'm" is fully visible and readable against the dark background
- Heading "Tracy Njoroge" is fully visible and readable against the dark background
- Description paragraph is fully visible, readable and not cut off

**Post Condition:** User is now viewing the Hero section

**Test Type:** Positive

**Status:**

---

**Test ID:** TCH002

**Test Title:** Verify Hero section animated text starts on page load

**Description:** Verify Hero section animated text starts automatically and cycles through all expected texts smoothly on page load

**Preconditions:**
- Website https://tracynjoroge.vercel.app/ is open in a desktop browser
- Internet connection is available
- User is currently viewing the Hero section

**Steps:**
1. Observe the animated text through one full cycle

**Expected Result:** 
- Animated text starts automatically without any interaction
- Both texts "A Front-end Developer" and "A Lifelong Learner" appear during the cycle
- No texts appear consecutively more than once in a single cycle
- Each text transitions smoothly and fully from the first letter to the last letter

**Post Condition:** User is now viewing the Hero section

**Test Type:** Positive

**Status:**

---

**Test ID:** TCH003

**Test Title:** Verify Resume button opens the correct file

**Description:** Verify Resume button opens a Resume PDF file in a new tab when clicked

**Preconditions:**
- Website https://tracynjoroge.vercel.app/ is open in a desktop browser
- Internet connection is available
- User is currently viewing the Hero section

**Steps:**
1. Click the Resume button  
2. Observe what happens

**Expected Result:** 
- Resume PDF file opens in new browser tab 
- The PDF displays the correct resume content
- Portfolio website remains open in the original tab

**Post Condition:**
- Resume PDF is open in a new browser tab
- Portfolio website remains open in the original tab

**Test Type:** Positive

**Status:**

---