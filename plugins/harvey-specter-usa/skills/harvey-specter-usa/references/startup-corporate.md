# Startup & Corporate Law — US Practice

## Overview

This reference covers entity formation, fundraising, equity compensation, and corporate governance for US startups.

---

## Entity Selection

### Decision Tree

```
START: What type of business?

├─ Seeking VC funding?
│  └─ YES → Delaware C-Corp
│
├─ Small business, no outside investors?
│  ├─ Want pass-through taxation? → LLC or S-Corp
│  └─ Single owner? → Single-member LLC
│
├─ Real estate or professional services?
│  └─ LLC (check state-specific rules)
│
└─ Lifestyle business, max 100 shareholders?
   └─ S-Corp (if eligible)
```

### Entity Comparison

| Feature | C-Corp | S-Corp | LLC |
|---------|--------|--------|-----|
| Taxation | Double (corp + dividend) | Pass-through | Pass-through (default) |
| Shareholders/Members | Unlimited | Max 100, US persons only | Unlimited |
| Stock classes | Multiple allowed | Single class only | Flexible |
| VC compatible | ✅ Yes | ❌ No | ⚠️ Rarely |
| Self-employment tax | No (wages only) | No (wages only) | Yes (unless elect S) |

---

## Delaware C-Corp — The Standard

### Why Delaware?

1. **Court of Chancery**
   - Specialized business court
   - Judges, not juries
   - Fast resolution (months, not years)

2. **Predictable Case Law**
   - 200+ years of corporate precedent
   - Business Judgment Rule well-established
   - Fiduciary duties clearly defined

3. **Flexible Statute (DGCL)**
   - Director-friendly provisions
   - Easy amendments
   - Minimal formality requirements

4. **Investor Expectation**
   - VCs expect Delaware C-Corps
   - Standard documents assume Delaware law
   - Easier due diligence

### Key DGCL Provisions

| Section | Topic | Key Point |
|---------|-------|-----------|
| § 102 | Certificate of Contents | Required provisions for charter |
| § 109 | Bylaws | Board can amend unless restricted |
| § 141 | Board of Directors | Business managed by board |
| § 144 | Interested Directors | Safe harbor for conflict transactions |
| § 145 | Indemnification | Corporation may indemnify directors |
| § 151 | Stock Classes | Unlimited classes allowed |
| § 157 | Stock Options | Board can grant options |
| § 202 | Transfer Restrictions | ROFR allowed if in certificate |
| § 242 | Charter Amendments | Board + stockholder approval |
| § 251 | Mergers | Statutory merger process |

---

## Incorporation Process

### Steps

1. **Choose Name**
   - Check availability: Delaware Division of Corporations
   - Must include "Corporation," "Inc.," "Corp.," etc.
   - Reserve name if needed (120 days, $75)

2. **File Certificate of Incorporation**
   - File with Delaware Secretary of State
   - Filing fee: $89 + franchise tax
   - Can file online, same-day processing available

3. **Appoint Registered Agent**
   - Required Delaware address
   - Cost: $50-300/year

4. **Adopt Bylaws**
   - Board adopts at first meeting
   - Standard template available

5. **Issue Stock**
   - Board resolution authorizing issuance
   - Stock purchase agreements
   - File 83(b) if restricted (within 30 days!)

6. **Obtain EIN**
   - IRS Form SS-4
   - Free, online, immediate

7. **Qualify in Operating States**
   - Foreign qualification if doing business in other states
   - California: $800 minimum franchise tax

---

## Founder Equity

### Typical Structure

```
Founders: 8,000,000 shares (80%)
Option Pool: 2,000,000 shares (20%)
─────────────────────────────────
Total Authorized: 10,000,000 shares
```

### Vesting

**Standard 4-year vesting with 1-year cliff:**

| Period | Vested |
|--------|--------|
| Month 0-11 | 0% |
| Month 12 (cliff) | 25% |
| Month 13-48 | +2.08%/month |
| Month 48 | 100% |

**Single-trigger vs Double-trigger acceleration:**
- Single-trigger: Accelerates on acquisition
- Double-trigger: Accelerates on acquisition + termination (investor preferred)

### 83(b) Election — CRITICAL

**What:** Election to be taxed on restricted stock at grant (not vesting)

**Why:**
- Pay tax on low FMV at grant
- Future appreciation taxed as capital gains
- Without 83(b): Taxed at vesting on FMV (potentially huge)

**Deadline:** 30 days from grant. **No exceptions. No extensions.**

**How to file:**
1. Complete IRS 83(b) election form
2. Mail to IRS within 30 days (certified mail recommended)
3. Keep copy with company
4. Attach copy to tax return

**Example:**
```
Scenario: 1M shares at $0.001/share, 4-year vest

WITH 83(b):
Tax at grant: 1M × $0.001 × 37% = $370

WITHOUT 83(b) (if FMV at vest = $10/share):
Tax at Year 4: 1M × $10 × 37% = $3,700,000
```

---

## Fundraising

### Stages

| Stage | Typical Amount | Investors | Instrument |
|-------|---------------|-----------|------------|
| Pre-seed | $50K-500K | Angels, friends | SAFE, convertible |
| Seed | $500K-3M | Angels, seed funds | SAFE, convertible, priced |
| Series A | $3M-15M | VCs | Priced round (preferred) |
| Series B+ | $15M+ | VCs, growth equity | Priced round (preferred) |

### SAFE Notes (Y Combinator)

**Simple Agreement for Future Equity**

Key terms:
- **Valuation Cap**: Maximum valuation for conversion
- **Discount**: Percentage discount to next round price
- **Pro-rata Rights**: Right to maintain ownership %
- **MFN**: Most favored nation (match better terms)

**Standard SAFEs (2023):**
- Post-money SAFE (current standard)
- Valuation cap OR discount (not both, typically)
- No interest, no maturity date

**Conversion:**
```
Conversion Price = Lower of:
  (a) Valuation Cap / Post-money shares
  (b) Price per share × (1 - Discount)
```

### Convertible Notes

**Debt that converts to equity**

Key terms:
- **Principal**: Amount invested
- **Interest Rate**: Typically 5-8%
- **Maturity Date**: When repayment due (typically 18-24 months)
- **Valuation Cap**: Max valuation for conversion
- **Discount**: Typically 15-25%

**Conversion trigger:**
- Qualified financing (typically $1M+)
- Maturity (convert or repay)
- Acquisition (1.5-2x return or convert)

### Priced Rounds (Series A+)

**Preferred Stock with negotiated terms**

Standard terms:
- Liquidation preference (1x non-participating typical)
- Anti-dilution (broad-based weighted average)
- Board seat(s)
- Protective provisions (veto rights)
- Information rights
- Pro-rata rights
- Drag-along rights

**Documents:**
- Term Sheet
- Stock Purchase Agreement
- Investor Rights Agreement
- Voting Agreement
- Right of First Refusal and Co-Sale Agreement
- Certificate of Incorporation (amended)

---

## Securities Law Compliance

### Regulation D — Private Placements

**Rule 506(b):**
- Unlimited accredited investors
- Up to 35 sophisticated non-accredited
- No general solicitation
- Form D filing within 15 days

**Rule 506(c):**
- Only accredited investors
- General solicitation allowed
- Must verify accredited status
- Form D filing within 15 days

**Accredited Investor (2024):**
- Income: $200K individual / $300K joint for 2 years
- Net worth: $1M+ (excluding primary residence)
- Certain professionals (Series 7, 65, 82)
- Knowledgeable employees of fund
- Entity: $5M+ assets, or all equity owners accredited

### Blue Sky Laws

- State securities laws
- Most states accept Rule 506 federal preemption
- File notice in states where investors reside
- California: Limited notice filing required

---

## Corporate Governance

### Board of Directors

**Fiduciary Duties:**
1. **Duty of Care**: Informed decision-making
2. **Duty of Loyalty**: Act in company's best interest
3. **Duty of Good Faith**: Honest, not self-dealing

**Business Judgment Rule:**
- Presumption that directors acted properly
- Protected if: informed, good faith, honest belief in best interest
- Overcomes challenges to board decisions

**Typical Board Evolution:**
| Stage | Board Composition |
|-------|------------------|
| Pre-seed | 1-2 founders |
| Seed | 2-3 (founders + maybe advisor) |
| Series A | 3-5 (founders + lead investor + independent) |
| Series B+ | 5-7 (balanced representation) |

### Stockholder Meetings

**Annual meeting required:**
- Elect directors
- Ratify auditors (if applicable)
- Other business

**Written consent in lieu of meeting:**
- Delaware allows action by written consent
- Must have majority (or supermajority if required)
- Faster than formal meeting

---

## Ongoing Compliance

### Delaware Franchise Tax

**Due:** March 1 annually

**Calculation Methods:**
1. Authorized Shares Method
2. Assumed Par Value Capital Method (usually lower)

**Example (Authorized Shares):**
| Shares | Tax |
|--------|-----|
| ≤5,000 | $175 |
| 5,001-10,000 | $250 |
| 10,001+ | Complex formula |

### Annual Report

- Delaware: Filed with franchise tax
- Operating states: Varies by state

### BOI Report (New 2024)

**Beneficial Ownership Information**
- File with FinCEN
- Required for most corporations and LLCs
- Deadline: Within 90 days of formation (new companies)
- Existing companies: By January 1, 2025

---

## Common Mistakes

1. **Missing 83(b) deadline** — Catastrophic tax consequences
2. **Not qualifying in operating states** — Penalties, inability to sue
3. **Issuing stock without board approval** — Invalid issuance
4. **Oral promises to employees** — Unintended equity obligations
5. **Skipping franchise tax** — Company voided in Delaware
6. **No IP assignment agreements** — Founders don't own their IP
7. **Single-trigger acceleration** — Founders can leave after acquisition

---

## Key Statutes & References

| Source | Citation | Topic |
|--------|----------|-------|
| DGCL | 8 Del. C. § 101 et seq. | Delaware corporations |
| Securities Act | 15 U.S.C. § 77a et seq. | Securities registration |
| Exchange Act | 15 U.S.C. § 78a et seq. | Securities trading |
| Regulation D | 17 CFR § 230.501-508 | Private placements |
| IRC § 83 | 26 U.S.C. § 83 | Property for services |
| IRC § 409A | 26 U.S.C. § 409A | Deferred compensation |
