# Runbooks

---

##  Deploy New Version

**When to use:** New release ready for deployment

**Steps:**
1. Ensure pipeline build is successful
2. Verify tests passed
3. Approve deployment stage
4. Monitor logs and metrics
5. Confirm `/health` endpoint returns healthy

---

##  Rollback Deployment

**When to use:** Deployment failure or errors

**Steps:**
1. Trigger rollback pipeline or script
2. Revert to previous stable version
3. Verify application is working
4. Monitor system stability

---

##  Scale Application

**When to use:** High traffic or performance issues

**Steps:**
1. Check monitoring dashboard (Datadog)
2. Increase number of replicas
3. Monitor CPU and memory usage
4. Scale down when traffic normalizes

---

##  Incident Response

**When to use:** System outage or failure

**Steps:**
1. Identify issue from logs/alerts
2. Notify team
3. Apply fix or rollback
4. Document incident
5. Review root cause

---