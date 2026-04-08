# 6-4-express-request-data-main — Feedback

## Submission

- **Lab:** 6-4-express-request-data-main
- **Deadline (Riyadh / UTC+03:00):** 2026-04-08T20:59:00+03:00
- **Last commit time (from git log):** 2026-04-08T08:58:26.314Z
- **Submission marks:** **20/20** (On time)


## Files Checked

- Repo root (cwd): C:\Users\ahmed\Desktop\Swe363_lab\6-3\6-4-express-request-data-ahmedAlromaih\6-4-express-request-data
- Detected project root: C:\Users\ahmed\Desktop\Swe363_lab\6-3\6-4-express-request-data-ahmedAlromaih\6-4-express-request-data
- Server: ✅ C:\Users\ahmed\Desktop\Swe363_lab\6-3\6-4-express-request-data-ahmedAlromaih\6-4-express-request-data\server.js

---

## TODO-by-TODO Feedback

### TODO 1: Server setup in server.js — **15/15**

**Checklist**
- ✅ Imports express using import express from "express"
- ✅ Creates the Express app using const app = express()
- ✅ Starts the server using app.listen(...)
- ✅ Logs startup message containing "API running at"

**Deductions / Notes**
- ✅ No deductions. Good job!

### TODO 2: Implement GET /echo using req.query — **20/20**

**Checklist**
- ✅ Defines GET route app.get("/echo", ...)
- ✅ Reads query params from req.query
- ✅ Checks for missing name or age and returns status 400
- ✅ Returns error JSON with ok:false and "name & age required"
- ✅ Returns success JSON with ok:true and includes name/age/msg

**Deductions / Notes**
- ✅ No deductions. Good job!

### TODO 3: Implement GET /profile/:first/:last using req.params — **15/15**

**Checklist**
- ✅ Defines GET route app.get("/profile/:first/:last", ...)
- ✅ Reads first and last from req.params
- ✅ Returns JSON with ok:true and fullName

**Deductions / Notes**
- ✅ No deductions. Good job!

### TODO 4: Implement app.param("userId") middleware — **15/15**

**Checklist**
- ✅ Defines app.param("userId", ...)
- ✅ Converts userId to a number
- ✅ Rejects invalid/non-positive userId with status 400 JSON error
- ✅ Stores numeric value in req.userIdNum and calls next()

**Deductions / Notes**
- ✅ No deductions. Good job!

### TODO 5: Implement GET /users/:userId route — **15/15**

**Checklist**
- ✅ Defines GET route app.get("/users/:userId", ...)
- ✅ Uses req.userIdNum in the route response
- ✅ Returns JSON with ok:true and userId

**Deductions / Notes**
- ✅ No deductions. Good job!

---

## How marks were deducted (rules)

- JS comments are ignored (so starter TODO comments do NOT count).
- Checks are intentionally lenient and verify top-level implementation only.
- Code can be in ANY order; repeated code is allowed.
- Common equivalents are accepted, and naming is flexible where possible.
- npm install commands and manual testing commands are NOT graded.
- Missing required items reduce marks proportionally within that TODO.
- Port 3000 is intentionally NOT graded.
- Route checks verify top-level logic only, not exact response wording beyond required fields/messages.
