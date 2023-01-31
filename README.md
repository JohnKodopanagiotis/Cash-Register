# Cash-Register
Cash Register for freeCodeCamp part of JavaScript Algorithms and Data Structures certification.
This project accepts a purchase price as the first argument (price),payment as the second argument (cash) and cash-in-drawer (cid) as the third argument.

It returns {status: "INSUFFICIENT_FUNDS", change: []} 
if cash-in-drawer is less than the change due, or if you cannot return the exact change 

It returns {status: "CLOSED", change: [...]}
with cash-in-drawer as the value for the key change if it is equal to the change due.

Otherwise returns {status: "OPEN", change: [...]},
with the change due in coins and bills, sorted in highest to lowest order, as the value of the change key.
