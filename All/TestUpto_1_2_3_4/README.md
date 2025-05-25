Here are **Questions 1 to 10** with the **correct answers marked** (✔️) and incorrect ones marked (❌), including the **matchings for Question 1**:

---

### **Question 1**

**Match each OSPF packet type to how it is used by a router:**

| OSPF Packet Type            | Usage                                                    | Match |
| --------------------------- | -------------------------------------------------------- | ----- |
| Hello packet                | ✔️ Establish and maintain adjacencies                    | A     |
| Database Description packet | ✔️ Compare local topology to that sent by another router | B     |
| Link-State Update packet    | ✔️ Advertise new information                             | C     |
| Link-State Request packet   | ✔️ Query another router for additional information       | D     |

---

### **Question 2**

Which type of OSPFv2 packet contains an abbreviated list of the LSDB of a sending router and is used by receiving routers to check against the local LSDB?

* ❌ link-state update
* ❌ link-state acknowledgment
* ❌ link-state request
* ✔️ **database description**

---

### **Question 3**

When an OSPF network is converged and no network topology change has been detected by a router, how often will LSU packets be sent to neighboring routers?

* ❌ every 60 minutes
* ❌ every 30 minutes
* ❌ every 5 minutes
* ✔️ **every 30 minutes** *(Correction: OSPF LSAs are refreshed every 30 minutes)*

---

### **Question 4**

In an OSPF network when are DR and BDR elections required?

* ❌ when the two adjacent neighbors are in two different networks
* ✔️ **when the routers are interconnected over a common Ethernet network**
* ❌ when the two adjacent neighbors are interconnected over a point-to-point link
* ❌ when all the routers in an OSPF area cannot form adjacencies

---

### **Question 5**

Refer to the exhibit. A network administrator has configured the OSPF timers to the values that are shown in the graphic. What is the result of having those manually configured timers?

* ❌ The hello timer on R2 expires every ten seconds.
* ❌ R1 automatically adjusts its own timers to match the R2 timers.
* ❌ The neighbor adjacency has formed.
* ✔️ **The R1 dead timer expires between hello packets from R2.**

*(R1 expects hellos every 5 seconds, dead at 20s. R2 sends every 25s – too late for R1.)*

---

### **Question 6**

What is a benefit of multiarea OSPF routing?

* ✔️ **Topology changes in one area do not cause SPF recalculations in other areas.**
* ❌ Automatic route summarization occurs by default between areas.
* ❌ Routers in all areas share the same link-state database and have a complete picture of the entire network.
* ❌ A backbone area is not required.

---

### **Question 7**

What is the default router priority value for all Cisco OSPF routers?

* ❌ 255
* ✔️ **1**
* ❌ 0
* ❌ 10

---

### **Question 8**

Which OSPF data structure is identical on all OSPF routers that share the same area?

* ❌ routing table
* ✔️ **link-state database**
* ❌ forwarding database
* ❌ adjacency database

---

### **Question 9**

Which step does an OSPF-enabled router take immediately after establishing an adjacency with another router?

* ❌ builds the topology table
* ✔️ **exchanges link-state advertisements**
* ❌ chooses the best path
* ❌ executes the SPF algorithm

---

### **Question 10**

What indicates to a link-state router that a neighbor is unreachable?

* ❌ if the router receives an update with a hop count of 16
* ❌ if the router receives an LSP with previously learned information
* ✔️ **if the router no longer receives hello packets**
* ❌ if the router no longer receives routing updates

---

Let me know if you want Questions 11–20 formatted similarly or added to a README table.
