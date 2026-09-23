# TAKAI UNIVERSAL COMMITMENT CALCULATOR

## Purpose

This calculator prices work based on the total commitment placed on the vehicle.

It is used for:

- Same-day long movements
- Overnight bookings
- Multi-day bookings
- Custom vehicle commitments

It is not a replacement for the public standalone rate card.

---

## Inputs

### 1. One-Way Distance

Enter the estimated one-way distance in kilometres.

### 2. Transit

Default transit calculation:

**One-way distance × 2**

This represents the vehicle travelling to the destination and returning.

### 3. Trip Type

Choose:

- Same-Day
- Overnight
- Multi-Day
- Custom

### 4. Commitment Days

Number of days the vehicle is committed to the client.

### 5. Local Running

For commitments longer than 2 days:

**50 km local running per commitment day**

### 6. Accommodation

Accommodation nights:

**Commitment days − 1**

Default driver accommodation:

**KES 3,000 per night**

---

## Operating Assumptions

Fuel:

**KES 217 per litre**

Fuel efficiency:

**9 km per litre**

Maintenance:

**KES 8 per km**

Driver allowance:

**KES 1,500 per working day**

Miscellaneous:

**KES 500**

Driver accommodation:

**KES 3,000 per night**

---

## Margin Rules

Internal minimum margin:

**25%**

Target margin:

**35%**

Minimum charge:

**KES 10,000**

---

## Core Principle

The quote must account for:

- Fuel
- Maintenance
- Driver cost
- Accommodation
- Miscellaneous costs
- Vehicle commitment
- Opportunity cost
- Business margin

Do not price purely by destination.

Do not use passenger count as the main pricing variable.

Do not create destination-specific pricing hacks.

---

## Quote Logic

### Same-Day

Calculate the operational vehicle movement and apply the required margin.

### Overnight

Calculate:

Operational vehicle cost  
+ Driver accommodation  
+ Required margin

### Multi-Day

Calculate:

Operational vehicle cost  
+ Local running  
+ Driver costs  
+ Accommodation  
+ Required margin

The longer the vehicle is committed, the more important vehicle opportunity cost becomes.

---

## Decision Rule

The final quote should normally sit between:

**Internal minimum**

and

**Target commercial price**

A quote below the minimum acceptable margin requires a deliberate business decision.

---

## Example

Example:

4-day commitment

Operational distance:

306 km

Accommodation:

3 nights

Recommended commercial quote:

**KES 51,000**

Final manually approved quote:

**KES 57,800**

The calculator provides the commercial baseline.

Human judgment determines the final quote.

---

## Version Control

Any change to:

- Fuel assumptions
- Maintenance assumptions
- Driver costs
- Accommodation
- Margin
- Minimum charge
- Local running
- Pricing logic

must be documented and committed to GitHub.

The calculator is a living business system.
