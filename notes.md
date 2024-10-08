## SME Proposal Template

Variables:
<<technology>>: specific technology within networking, str value
    - examples: SD-WAN, SD-Access, Campus, Wireless
<<client>> : # name of customer; str value
<<date>>: insert current date, mm-yy format; str value
<<sme_days>>: total business days for SME (ex: 15); integer value 
<<remote_onsite>>: 3 possible answers; 1) remote, 2) onsite, 3) remote and onsite, str value
    - if onsite, then need to define # of days onsite 
    - <<onsite_days>>: # of days onsite; if previous answer is option 1 - remote, then leave this blank, integer value
<<start_date>>: will be 45 days from whatever is today's date, needs to be calculated. str value
<<end_date>>: will be a duration value for which time the SME service is available, needs to be calcuated, str value
    - end date calculation:
        - If SME hours are for 40 > x < 80; then duration is for up to 1 month.
        - If SME hours is 80 -> 10 days; then duration is for up to 3 months.
        - If SME hours are 200 -> 25 days, then duration is for up to 6 months.
        - If SME hours are 200 > X < 1000; then duration is for up to 12 months.
<<duration_months>>: duration in months between start date and end date


## SDWAN Proposal Template
<<client>> : # name of customer; str value
<<date>>: insert current date, mm-yy format; str value