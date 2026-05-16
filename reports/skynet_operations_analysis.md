# Skynet Operations & Efficiency Analysis Report
**Flight Training Organization (FTO) Performance Review** *Generated on: 2026-05-16 12:20:46*

---

## 1. Aircraft Utilization Analysis

 Aircraft-Wise Utilization Profile
| Aircraft ID | Registration | Type | Base | Flown Hours | Available Hours | Utilization Rate | Defect Count | Maintenance Downtime (Hrs) |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| A001 | VT-TRL | C152 | B03 | 11.92 | 102.0 | 11.7% | 12 | 96 |
| A002 | VT-YRG | C152 | B03 | 13.33 | 165.0 | 8.1% | 9 | 63 |
| A003 | VT-JZI | N/A | B02 | 13.95 | 138.0 | 10.1% | 12 | 48 |
| A004 | VT-BXF | DA42 | B01 | 13.10 | 150.0 | 8.7% | 0 | 0 |
| A005 | VT-OBB | DA40 | B01 | 8.87 | 158.0 | 5.6% | 1 | 4 |
| A006 | VT-AZV | C152 | B03 | 7.80 | 107.0 | 7.3% | 12 | 96 |
| A007 | VT-MHM | C172 | B02 | 9.47 | 108.0 | 8.8% | 5 | 40 |
| A008 | VT-XEF | C152 | B03 | 8.07 | 101.0 | 8.0% | 12 | 84 |
| A009 | VT-ICI | DA42 | B01 | 0.00 | 135.0 | 0.0% | 1 | 8 |
| A010 | VT-GDW | C172 | B01 | 14.97 | 103.0 | 14.5% | 4 | 32 |

### Base-Wise Utilization Matrix
| Base ID | Combined Flown Hours | Combined Available Hours | Aggregate Utilization Rate |
| :--- | :--- | :--- | :--- |
| B01 | 36.93 | 546.0 | 6.8% |
| B02 | 23.42 | 246.0 | 9.5% |
| B03 | 41.12 | 475.0 | 8.7% |

### Operational Asset Flags
* **Underutilized Aircraft (<5.0% Efficiency Index):** A009
* **Aircraft with High Defect Counts (>= 8 Incidents):** A001 (12 defects), A002 (9 defects), A003 (12 defects), A006 (12 defects), A008 (12 defects)
* **Maintenance Downtime Impact:** The fleet suffered a total loss of **471 hours** due to reactive technical maintenance.
* **Aircraft Flagged for Operational Review:** A001, A002, A003, A006, A008, A009

---

## 2. Instructor Utilization Analysis

 Workload Balance & Productivity Ledger
| Instructor ID | Name | Home Base | Aircraft Qualifications | Historical Duty Hours | Sortie Flown Hours | Active Load % |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| I001 | Name1 | B03 | C152 | 167.0 | 13.33 | 8.0% |
| I002 | Name2 | N/A | DA40, C172 | 132.0 | 12.38 | 9.4% |
| I003 | Name3 | B02 | C152, PA28 | 124.0 | 7.50 | 6.0% |
| I004 | Name4 | B03 | C172 | 151.0 | 7.13 | 4.7% |
| I005 | Name5 | B03 | C172 | 88.0 | 16.73 | 19.0% |
| I006 | Name6 | B03 | DA40 | 93.0 | 12.52 | 13.5% |
| I007 | Name7 | B01 | DA40, PA28 | 128.0 | 6.93 | 5.4% |
| I008 | Name8 | B03 | DA42 | 116.0 | 18.95 | 16.3% |
| I009 | Name9 | B01 | C152 | 156.0 | 18.48 | 11.8% |
| I010 | Name10 | B02 | PA28 | 123.0 | 15.20 | 12.4% |

### Instructor Dispatch Flags
* **Overloaded Instructors (>15 Flight Hours):** I005, I008, I009, I010
* **Underutilized Instructors (<10 Flight Hours):** I003, I004, I007
* **Qualification Mismatch Risks:** Identified **44 sorties** where instructors flew airframes outside their explicit qualification criteria.

---

## 3. Dispatch Reliability & Interruption Metrics

### Core Reliability Dashboard
* **Total Scheduled Sorties:** 100
* **Completed Sorties:** 85
* **Cancelled Sorties:** 15
* **Delayed Sorties:** 31
* **Syllabus Completion Rate:** 85.00%
* **Operational Cancellation Rate:** 15.00%
* **Systemwide Average Delay:** 7.82 Minutes

### Primary Interruption Engines (Cancellations)
| Interruption Reason | Incidents Logged | Proportion (%) |
| :--- | :--- | :--- |
| Airspace Restricted | 5 | 33.3% |
| Aircraft Defect | 4 | 26.7% |
| Instructor Unavailable | 3 | 20.0% |
| Cadet Medical | 2 | 13.3% |
| Weather | 1 | 6.7% |

### Delay Telemetry Trends

 Delay Metric by Airbase Location
| Base ID | Average Operational Delay (Minutes) |
| :--- | :--- |
| B01 | 6.61 Mins |
| B02 | 5.79 Mins |
| B03 | 11.14 Mins |

### Delay Metric by Lesson Syllabus Type
| Lesson Configuration Type | Average Operational Delay (Minutes) |
| :--- | :--- |
| Circuit | 12.00 Mins |
| Formation | 16.19 Mins |
| General Handling | 4.09 Mins |
| Instrument Flying | 7.06 Mins |
| Navigation | 0.00 Mins |
| Night Flying | 3.14 Mins |

### Daily Delay Moving Timeline (Sample Period)
| Date Timeline | Average Registered Delay (Minutes) |
| :--- | :--- |
| 2026-05-01 | 0.00 Mins |
| 2026-05-02 | 2.75 Mins |
| 2026-05-03 | 1.67 Mins |
| 2026-05-04 | 3.00 Mins |
| 2026-05-05 | 15.80 Mins |
| 2026-05-06 | 0.00 Mins |
| 2026-05-07 | 12.60 Mins |
| 2026-05-08 | 6.50 Mins |
| 2026-05-09 | 4.12 Mins |
| 2026-05-10 | 12.40 Mins |

---
*End of Operational Analytics Dispatch*
