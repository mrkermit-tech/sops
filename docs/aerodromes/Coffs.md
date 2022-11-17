---
  title: Coffs Harbour (YCFS)
---

--8<-- "includes/abbreviations.md"

## Positions

| Name | Callsign | Frequency | Login Identifier |
| ---- | -------- | --------- | ---------------- |
| Coffs Harbour ADC | Coffs Harbour Tower | 118.200 | CFS_TWR |
| Coffs Harbour ATIS | N/A | 130.300 | YCFS_ATIS |

## Airspace

<figure markdown>
![CFS TWR Airspace](img/ycfs_airspace.png){ width="700" }
  <figcaption>CFS TWR Airspace</figcaption>
</figure>

Refer to [Class D Tower Skills](../../controller-skills/classdtwr/) for more information.

## Surveillance
CFS TWR is permitted to use Surveillance standards for separation. Surveillance coverage can be expected to be not available below **2800 feet** in the CFS CTR.  
For simulation purposes, visual separation is assumed to exist below the cloud base, and within 5nm. Visual separation can still be used to separate from aircraft on an instrument approach, below the cloud base.

CFS TWR must establish a [Procedural Standard](../../controller-skills/classdtwr/#standards) prior to losing surveillance identification of an aircraft.

!!! caution
    An aircraft becoming identified, or maintaining identification, *below* 2800 feet, cannot be assumed to be able to maintain identification at that level. A procedural and/or visual standard **must** be put in place for all aircraft below 2800 feet.
## Instrument Approaches
Only one aircraft is permitted to conduct an instrument approach at any time, due to limited surveillance coverage. CFS TWR must ensure that all aircraft are procedurally separated from any portion of an instrument approach and missed approach that is conducted below **2800 feet**.  

If required, CFS TWR can pass amended tracking/level instructions to an aircraft for a missed approach for separation purposes, as long as the aircraft can be issued **uninterrupted climb** to the LSALT/MSA once identified.

## Coordination
### Departures
#### Taxi Call
A taxi call shall be made to INL/ARL(MNN), for all aircraft entering INL/ARL(MNN) Class C airspace, as an aircraft is given taxi clearance. AINL/ARL(MNN) will respond by acknowledging the callsign.

!!! example
    **CFS TWR** -> **MNN**: "Taxi, QJE1573 for YMML via BANDA"  
    **MNN** -> **CFS TWR**: "QJE1573"  

#### Next Call
A next call is made for all aircraft when they are next to depart and will be departing within two minutes. INL/ARL(MNN) will respond by acknowledging the callsign.

!!! example
    **CFS TWR** -> **MNN**: "Next, QJE1573"  
    **MNN** -> **CFS TWR**: "QJE1573"  

### Arrivals
INL/ARL(MNN) will coordinate the sequence to CFS TWR.

!!! example
    **INL** -> **CFS TWR**: "New Sequence of 2. Via GAMBL, RXA9904, Number 1. Via TUCAB, LYM, Number 2”  
    **CFS TWR** -> **INL**: "RXA9904, Number 1. LYM, Number 2"  

## Standard Assignable Levels

Aircraft departing from Coffs Harbour shall be assigned `A070` or `RFL` if lower.

Aircraft arriving into Coffs Harbour shall be assigned `A080` by INL/ARL(MNN).