

(This guy explains clearing pretty well [http://gendal.wordpress.com/category/clearing/](http://gendal.wordpress.com/category/clearing/)

# Depository Trust Corporation Company Breakdown
(note to the reader: none of this should be easy to understand. It is a complex and confusing 'black box' system). Before reading this, one should familiarize themselves with a glossary of all terms used in this industry (see Appendix C.)

## Functions:
DTC is a custodian of securities, and a securities settlement services. They do not actually dematerialize securities, but rather just immobilize them . They provide account holders with both a securities account and a USD cash account to facilitate payments. They do not provide any trade settling services, but this is rather carried out by their other company NSCC. It is important to note that they do all these activities in-house, not outsourcing any part of it.

They also facilitate lending and borrowing transactions among their participants of securities.

## Explanation of the lending capacity:
Securities lent by one Participant to another can be delivered by book-entry either free or against payment. DTC's payment order service provides a vehicle for the transfer of cash between securities borrowers and lenders to account for adjustments in the market value of the borrowed securities during the period the loan is outstanding.

## Custodial Services:
Now there is a whole group of functions DTC provides while they hold your securities in custody (known as custodial service activities), b/c securities require a fair amount of maintenance: dividends, voting rights and transference.

- Dividends: DTC collects and distributes dividends and interest to its participants.
  - They also have a sub program that allows you to reinvest dividends and shares back into more stocks

- Tender and exchange offers: Participants can accept these and transfer them to the offerer within DTC. 
  - Other rights such as warrants, puts, conversions and rights to purchase more shares are conveyed through DTC while they hold your securities

- Security maturation: DTC presents the security for redemption and distributes the proceeds to the holder
- Voting Rights: this is handled by DTC's proxy service-Cede & Co.-assigns each participant the voting rights on whatever securities they hold
- Taxes on dividends: they have arrangements with the tax authorities of different countries to have the holder of the security receive reduced withholdings, rather than a refund at a later date. 
- Underwriting (insurance): DTC permits underwriters of new and secondary issues of securities to distribute them by book-entry against payment through the depository.

## Types of Securities DTC Holds:

### DEBT (in addition to Government and Municipal Debt)
* Asset Backed Securities
* Auction Rate Notes
* Bank Notes
* Certificates of Deposit (Retail & Institutional CDs)
* Collateral Mortgage Obligations (CMOs)
* Commercial Paper (CP)
* Consumer Price Index-Linked Bonds (CPI Bonds)
* Convertible Debt
* Corporate Bonds
* Deposit Notes
* Discount Notes
* Insured Custodial Receipts
* Medium Term Notes (MTNs)
* Notes/Tender Rate Notes- 5 -
*  Variable Rate Demand Obligations (VRDOs)
* Zero Coupon Bonds

### EQUITY
* American Depositary Receipts (ADRs)
* Auction Rate Preferred Securities
* Closed End Funds
* Common Stock
* Limited Partnerships
* Preferred Stock
* Rights to Purchase Securities
* Unit Investment Trusts (UITs)
* Units
* Warrants

### GOVERNMENT SECURITIES
* Brady Bonds
* Non-U.S. Government Debt
* U.S. Treasury, Federal Agency and Government Sponsored Enterprises
* Issues

### MUNICIPAL SECURITIES
* Auction Rate Notes
* Insured Custodian Receipts
* Municipal Bonds
* Municipal Notes
* Variable Rate Demand Obligations (VRDOs)



# Operations:
DTC's functions are clearly outlined-it is important to note that they are part of a much larger system that is all intertwined by the same company. This post will explain the much larger picture as to [how, and why a central securities deposit exists](http://gendal.wordpress.com/2014/01/05/a-simple-explanation-of-how-shares-move-around-the-securities-settlement-system/).  See Appendix A. to gain more insight as to how they fit into the system.

# Membership Levels:

- Full Service Members-"Participants"
  - required to make a minimum deposit to the Participants Fund

- Membership for certain services- "Limited Participants"
  - May not be required to make a deposit/contribution to the Participants Fund

# Membership Admittance Requirements:

- demonstration that it meets reasonable standards of financial responsibility, operational capability, and character. 
- Capital and financial stability- DTC does NOT admit anyone with less than $500,000 in net capital or banks with less than $2 Million in equity. These requirements are reviewed quarterly by the DTC compliance dept. 
- Operational Capacity: must have personnel and data processing capacity to meet technical demands of interfacing with DTC's depository. 
- There are a plethora of reasons as to why the DTC can terminate membership.

# Transactions:

- The DTC receives instructions from the central counterparty, which has done the process of matching, to which they then 'settle' the transaction. 
- When a participant deposits a security, they are given an immediate credit for it in their account that they can use to affect book-entry transactions. Those securities are then sent to DTC's nominee, Cede & Co, who essentially hold all the physical securities. It would seem that DTC runs the bookkeeping and transactions of securities held there. Cede & Co are technically owned by DTC participants to fit a loophole. Essentially, it allows them to order transfers of stock registered in the name of the partnership without the need of presenting a separate corporate resolution to the stock issuer's transfer agent or stock registrar to validate the authority of the transfer.
- For most registered securities issues, a Participant with securities on deposit within the DTC system can withdraw the securities physically and have them reregistered in the name of the Participant, its customer or another party. On the instructions of the withdrawing Participant, DTC debits the securities from the Participant's account and instructs the transfer agent to register the transfer of the securities into the name designated by the Participant. The reregistered securities are then sent to the Participant or its customer
  - And how this is all done is by basically crediting and debiting accounts, much like how payment processing work within the banking industry: 
    - ■■Transfers of securities within the DTC system are processed by debits and credits to Participants' accounts. Some transfers are processed in batches, and other transfers are processed on a real-time basis. The source of the transfer instructions determines whether a batch method or real-time method is used. For example, transfer instructions received early in the processing day from NSCC or from a trade matching service provider such as Omgeo are processed at that time in batches (much like the blockchain). Transfer instructions received from Participants during the day are processed on a real-time basis. Securities settlements occur daily. Transfers of securities delivered against payment are effective simultaneously with payment.
      - And in further detail: DTC does not maintain cash accounts for its Participants. but rather a settlement account. During the day, debits and credits are entered into the Participant's settlement account. The debits and credits arise from securities transfers against payment made and received by the Participant and from other transactions such as principal and income payments received in respect of securities credited to the Participant's securities account. At the end of each day, the debits and credits in the Participant's settlement account are netted. Then, DTC and NSCC net the settlement balances of each DTC Participant that is also a member of NSCC. After netting with NSCC, DTC pays any net credit balance in the account to the Participant, and the Participant pays any net debit balance to DTC. Payments are made to and from DTC's account at the Federal Reserve Bank of New York through the Federal Reserve System's money transfer system (sometimes called the Fedwire system). Each Participant must engage a Settling Bank, which is a DTC Participant bank with access to the Fedwire system, to act on the Participant's behalf in settling with DTC. A Participant which qualifies as a Settling Bank may act as its own Settling Bank. A Settling Bank is not required to pay DTC a debit balance on behalf of a Participant and is not required to advance funds to a Participant.

- They use a DVP system, or Delivery versus Payment, where the delivery will only occur IF a payment is made before or simultaneously. This is to eliminate the risk for the other participant in the transaction and DTC itself in the case that one party goes bankrupt/cannot pay. This is a crucial part of their operations. 
  - securities transfers are non-reversible, and their finality does not depend on what type of security is being transferred. 
  - The receiving participant may dispose of their securities (read: trade them again) prior to the money settlement at DTC. 

- Participants can maintain 'short' positions within the DTC. They charge a fee for having this capacity-and there are a slew of operational standards around this that are outside the scope of this report. 
- See here for a deep dive into DVP



# Legal/Regulatory:

All below is under NY state banking and state regulation.

DTC is a limited-purpose trust company organized under NY state 'banking law', or more specifically a 'banking organization'. They are also a member of the Federal Reserve System. DTC is also classified as a 'clearing corporation' under the meaning in the NY Uniform Commercial Code. Under the SEC, they are registered as a 'clearing agency' under the  provisions of Sections 17A and 19(a) of the Securities Exchange Act of 1934, as amended (the "Exchange Act").

They have oversight by: the Fed Board of Governors, the SEC, and the NY State Banking Dept.

There is a list of rules outlining the responsibilities and rights of all participants under DTC that are provided to participants only.

All liabilities to participants vary. It is outlined in the contract between the member and the DTC.

Under the authority of the U.S. Dodd-Frank Act, the U.S. Financial Stability Oversight Council designated, among others, DTCC subsidiaries National Securities Clearing Corporation (NSCC), The Depository Trust Company (DTC) and Fixed Income Clearing Corporation (FICC) as [Systemically Important Financial Market Utilities](http://www.federalreserve.gov/paymentsystems/designated_fmu_about.htm) (SIFMUs). This designation requires the company to meet prescribed risk management standards and subjects it to heightened oversight by U.S. regulatory authorities.



[Financials](http://www.dtcc.com/~/media/Files/Downloads/legal/financials/2013/DTC_2013_2012_Annual_Financial_Statements.pdf):

(see above link for actual balance sheet/statement of income/retained earnings/cash flow documents FY 2013)

Here we will outline some of the basic financial information of DTC as it relates to how they operate the company (all below is as of 2001 from a report issued in **2002** :

- Paid-in Capital/retained earnings: $77.8 Million
- Guarantees/Insurance/Other Coverage
  - $650 million on premises coverage under Blanket Bond/All-Risk policies.
  - $650 million in-transit coverage under Blanket Bond/All-Risk policies for securities in transit while in the custody of messengers or a- 13 - transportation company; additional transit coverage is available for non-negotiable securities.
  - $800 million in-transit coverage provided by the insurer of the

armored car carrier service used by DTC. DTC's coverage under the

Blanket Bonds/All-Risk policies provides secondary coverage for

securities lost while in the custody of an armored carrier.

- 
  - $1 million under Mail Policy covering registered securities lost after having been sent via first class mail.
  - $25 million under Mail Policy covering registered securities lost after having been sent via registered or express mail or express courier.

- Lines of Credit:
  - $1.75 Billion LOC from a group of banks in the case one of its members fails to pay its daily money settlement obligation to DTC
  - $50 Million LOC from a bank to provide liquidity for distributing principal and income payments to its participants when the payments are received too late to allocate them on the date payable. 

[Leadership (DTCC)](http://www.dtcc.com/about/leadership.aspx):

It should be noted that DTCC/DTC is owned and run by financial industry moguls. More specifically, the DTC is owned by the banks they serve.

Board of Directors:

Robert Druskin - Executive chairman of DTCC

Michael C Bodson - President and CEO of DTCC; DTC

Robert L.D. Colby - Chief Legal Officer of FINRA

Paul H. Compton - CAO of JPMorgan Chase

Chris Concannon - Partner and VP of Virtu Finance LLC

Management Committee:

Robert Druskin - Executive chairman of DTCC

(Previously lead director at E\*trade and SMG at Citigroup)

Michael C Bodson - President and CEO of DTCC; DTC (also in charge of NSCC, FICC)

(Came from SMG at Morgan Stanley as global head of institutional, retail and asset management)

Noel Donohoe - Executive Managing Director and Group Chief Risk Officer

Paul Garrison - Managing Director and Chief Information Officer at DTCC

Andrew Gray - Managing Director, Core business mgt and Chairman of the European Central Counterparty Ltd. (subsidary of DTCC)

Donna Milrod - Managing Director and Chief Admin Officer

Thoughts:

There is a problem: if a company cannot get DTC eligibility, then essentially thier stocks cannot be traded. Would it be viable, at all, to pursue ineligible companies? see here [http://taurusfp.com/dtc-eligibility/](http://taurusfp.com/dtc-eligibility/) for more information the issue.

Appendix:


Appendix B.

DTC answering questions about thier framework: [http://www.bis.org/publ/cpss20r3.pdf](http://www.bis.org/publ/cpss20r3.pdf)

Appendix C.

A comprehensive glosseryof terms used in understanding the depository and clearing industry: [http://www.bis.org/publ/cpss00b.pdf](http://www.bis.org/publ/cpss00b.pdf)

Appendix D

an incomplete google book written on the DTC by a DTC board member:

[http://books.google.com/books?id=xyzEiM1WVnYC&printsec=frontcover#v=onepage&q&f=false](http://books.google.com/books?id=xyzEiM1WVnYC&printsec=frontcover#v=onepage&q&f=false)


Important info on DTCC and NSCC

explaining the below is [http://www.bis.org/publ/cpss105\_us.pdf](http://www.bis.org/publ/cpss105_us.pdf)

Data Repositories:

DTCC Data Repository (US) LLC (DDRL US) is a wholly owned subsidiary of the Depository Trust & Clearing Corporation (DTCC) that operates a multi-class swaps data repository for the over-the-counter (OTC) equities, credit, interest rate and foreign exchange derivatives markets. DDRL US plans on supporting commodities derivatives in the future. DDRL US maintains an electronic database containing authoritative and timely data on derivatives contracts for the asset classes that it serves.

DDRL US is part of DTCC's global trade repository (GTR) service that supports cleared and uncleared OTC equities, credit, interest rate, foreign exchange and commodity derivatives.The GTR service is utilised by two other trade repositories in addition to DDRL US: (i) DTCC Derivatives Repository Limited (DDRL Ltd), a UK company; and (ii) Global Trade Repository for Commodities BV (GTRfC), a Dutch company. GTR is serviced by other DTCC subsidiaries, including the Warehouse Trust Company, a state-chartered, limited-purpose trust company in New York and a member of the Federal Reserve System, that provides post-trade lifecycle event processing to trade repositories servicing the credit default swap market. DDRL US also has links to the DCOs that choose to satisfy CFTC swap transaction reporting requirements under the Commodity Exchange Act.

DTCC also has a bit of a monopoly on the post-trade processing chain:

National Securities Clearing Corp (NSCC)-they provide **central counterparty clearing** and settlement services for securities transactions in the US and are owned by DTCC. they clear transactions for a number of exchanges and trading venues like the NASDAQ and OTC markets of broker-to-broker trades involving: equities, bonds, ETF's and investments trusts. As an example of their power: they processed 20 billion transactoins valued at $218 Trillion.

**How they operate:** Trading activity, regardless of trade source, enters NSCC on trade date (T) and final settlement occurs three days after (T+3).21 In its clearing process, NSCC conducts a multilateral net of its members' trade positions, resulting in a net long (buy) or net short (sell) position in each traded security for each member and a single overall net funds position for each member. NSCC maintains a settlement account at the Depository Trust Company (DTC) to allow settlement of net securities obligations.

On settlement date (T+3), NSCC's continuous net settlement (CNS) system instructs DTC to deliver available securities from members with net delivery obligations to NSCC's settlement account and then deliver those securities to members with net receive obligations. These securities deliveries are made free of payment within DTC and are provisional intraday (with respect to the receiver) until end-of-day payment (approximately 16:30 ET) is made over NSS.23 The DTC and NSCC end-of-day net funds settlement process is executed over a single NSS file. Each DTC and NSCC member must designate a settling bank that participates in the DTC-NSCC NSS arrangement. DTC and NSCC calculate a net-net funds settlement obligation for their common members by netting their separate DTC and NSCC net funds obligations.

How NSCC Cover's their liabilities:

They hold a risk of having some member going broke and not being able to actually pay up a transaction, so they must hold funds to make sure if anything goes wrong, people still get their money. This is a HUGE requirement.  They resources, primarily in the form of member's fund deposits, to cover the failure of a member having the largest net debit in extreme but plausible market conditions. Their clearing fund is calculated by looking at the daily mark to market changes (measured by the unrealised profit or loss in a members portfolio using contract prices versus market prices of the securities they are clearing.

Also in this resource fund are member cash contributions and the cash that would be obtained from their committed liquidity facility. When they have to draw from these resources, they collateralize it with the participant securities contributions and unpaid long allocations of the defaulting member.

If a member does not pay its net funds obligation to the NSCC, the central counterparty is obliged to make payment to the other members for the securities they delivered to the NSCC.

