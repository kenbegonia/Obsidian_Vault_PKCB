# 🧪 Exploratory Testing Session - {{ Feature Name }}
**Date:** YYYY-MM-DD  
**Tester:** Ken  
**Session Charter:** Explore the {{ area of the app }} to discover bugs, inconsistencies, or unexpected behavior.

---

## 🔍 Scope / Focus Area
- [ ] Feature:
- [ ] Flow:
- [ ] URL / Page:
- [ ] Devices/Browsers (if applicable):

---

## ⏳ Timebox
**Planned Duration:** XX minutes  
**Start Time:** HH:MM  
**End Time:** HH:MM  
**Actual Duration:** XX minutes

---

## 🎯 Testing Goals
- [ ] What do I want to learn?
- [ ] What kinds of bugs am I looking for?
- [ ] What kind of data or input am I using?

---

## 🧭 Test Notes / Observations
_Bullet points, stream-of-consciousness notes, things you tried, patterns you noticed, etc._

- Inputting long strings into the email field returns 500 error
- UI crashes when submitting with no password
- Error message disappears too fast to read
- Autofocus missing on login form
- Unexpected redirect when clicking “Back” on mobile

---

## 🐞 Bugs Found
| ID      | Title                          | Severity | Steps to Reproduce     | Status |
| ------- | ------------------------------ | -------- | ---------------------- | ------ |
| BUG-001 | Login fails with correct creds | High     | 1.<br><br>2.<br><br>3. | Open   |
| BUG-002 | UI glitch on dashboard load    | Low      | 1.<br><br>2.<br><br>3. | Open   |


---

## 💡 Insights / Questions / Risks
- Are error messages consistent across forms?
- Found multiple 500s — are logs being captured?
- Could user data be leaking on URL params?

---

## ✅ Next Steps / Follow-ups
- [ ] Report all confirmed bugs to Basecamp / issue tracker
- [ ] Re-test after patch
- [ ] Ask dev about backend validations for file uploads

---

## 🔁 Session Reflection
- What worked well?
- What confused or slowed you down?
- What would you do differently in the next session?
